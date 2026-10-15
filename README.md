# A Mathematical Security Architecture for Authentication, Key Management, and Message Integrity

A university mathematics project about modelling secure messaging with discrete mathematics.

## Open the project in a browser

**Live website:** https://strong-sorbet-1fbd13.netlify.app/

[**Click here to open the live website**](https://strong-sorbet-1fbd13.netlify.app/)

Open this link in Chrome, Edge, or another browser on your laptop. The Android APK is a separate mobile app package.

## Project presentation

The shortened presentation has been updated to **9 slides**. Its final slide includes the GitHub repository link, the live website QR code, and the app QR code supplied by the project owner.

**Note:** The updated PowerPoint file still needs to be uploaded to this repository. On GitHub, choose **Add file → Upload files**, select `mathematical_security_project_final_qr.pptx`, and commit the change.

## QR code links

- **Website QR code:** https://api.qrserver.com/v1/create-qr-code/?size=600x600&data=https%3A%2F%2Fstrong-sorbet-1fbd13.netlify.app%2F
- **GitHub repository:** https://github.com/alapatijohnbabu-bit/mathematical-security-architecture

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

**Academic note:** Real systems should use established cryptographic libraries and be independently tested before protecting real data.
