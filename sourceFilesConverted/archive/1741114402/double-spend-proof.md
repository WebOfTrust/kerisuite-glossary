## Term Definition

Spec-Up-T link: <a href='https://weboftrust.github.io/WOT-terms/docs/glossary/double-spend-proof'>here</a>

### KERI related
The most important feature of a [cryptocurrency](cryptocurrency) is that it must be double spend proof. Because KERI's key event operations are idempotent they do not need to be double spend proofed, so we can greatly simplify the distributed consensus algorithm in KERI. Which makes KERI relatively more attractive for many applications including IoT applications by comparison.  
As a result of the relaxation of double spend proofing, KERI is able to break the distributed consensus algorithm into two halves and simplify it in the process. The two halves are the *promulgation* half (by witnesses) and the *confirmation* half (by valdators).