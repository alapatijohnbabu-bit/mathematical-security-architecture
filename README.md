# A Mathematical Security Architecture for Authentication, Key Management, and Message Integrity

A university mathematics project about modelling secure messaging with discrete mathematics.

## Project overview

The project uses the example of Ravi sending a message to Priya through a secure campus network. It is organised into six modules that explain how mathematical ideas can describe security requirements and the accept/reject decision.

## Objectives

- Model acceptance rules using propositional logic and proofs.
- Represent users, roles, permissions, and mappings using sets, relations, and functions.
- Use counting and combinatorics to reason about key-space size and collisions.
- Explain modular arithmetic and number theory in cryptography.
- Represent communication nodes and routes using graph theory.
- Introduce algebraic structures used in cryptographic operations.

## Six modules

1. **Logic and proof:** define the conditions for accepting or rejecting a message.
2. **Sets, relations, and functions:** model users, roles, permissions, and authorised actions.
3. **Combinatorics and counting:** calculate key-space size and explain finite-space collisions.
4. **Number theory:** explain modular arithmetic and its role in cryptographic methods.
5. **Graph theory:** model communication nodes, links, and routes.
6. **Algebraic structures:** explain mathematical foundations of cryptographic operations and key exchange.

## Core decision rule

A = authentication valid; P = permission valid; K = key condition valid; R = route valid; I = message integrity valid.

**ACCEPT = A AND P AND K AND R AND I**

A message is accepted only when every required condition is true. If any condition fails, it should be rejected or revalidated.

## Case study: Ravi sends a message to Priya

1. Verify the sender's identity.
2. Check the sender's permission.
3. Check the key conditions.
4. Check the communication route.
5. Verify message integrity.
6. Accept only if all required checks pass.

This is a conceptual model for the university project, not a claim that a deployed system has passed a security audit.

## Project links

- **Live website:** https://strong-sorbet-1fbd13.netlify.app/
- **Website QR code:** [assets/website-qr.png](assets/website-qr.png)
- **Original 30-slide presentation:** [presentation/merged_presentation_choladeck.pptx](presentation/merged_presentation_choladeck.pptx)
- **Android APK:** Not uploaded yet. A direct download link and APK QR code can be added after the APK file is provided.

## Repository contents

- `README.md` — project overview and links.
- `presentation/merged_presentation_choladeck.pptx` — original presentation.
- `assets/website-qr.png` — website QR code.

## Conclusion

Discrete mathematics gives a structured way to describe secure messaging: logic defines the decision rule; sets and relations model access; counting analyses key spaces; number theory supports cryptographic methods; graph theory models routes; and algebraic structures explain cryptographic operations.

**Academic note:** Real systems should use established cryptographic libraries and be independently tested before protecting real data.
