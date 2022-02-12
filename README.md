# Crypto World

# Abstract

# Contents
- [Introduction](#Introduction)
- [Cryptoanalysis](#Cryptoanalysis)
- [Lessons](#Lessons)

## Introduction

### What is *cryptography* ?
Cryptography is **ciphered text** that can be understood only who owns **key**.

### Which is the context?
* **Cryptography**: study of all principle and methods to encrypt a plain text
* **Cryptoanalysis**: study of all principle and methods to decrypt ciphered text without knowning key
* **Cryptology**: all study of Cryptography and Cryptology

Context of this repo is **cryptoanalysis** with little knownledgment of **cryptography**. 

### Definition of terms
It's important define terms to be not ambiguous.

| Terms | Description |
| ----- | ----------- |
| Plaintext     | Original text |
| Ciphertext    | Coded text    |
| Cipher        | Algorithm for trasforming plaintext to ciphertext |
| Key           | Info used in the cipher known only by sender/receiver |
| Encipher (encrypt) | Convert plaintext to ciphertext |
| Decipher (decrypt) | Recover plaintext from  ciphertext |

## Cryptoanalysis 

### Kerckhoffs's principle

A cryptosystem should be secure even if everything about the system is public knowledge, except the **key**.

### Cryptoanalysis Context
What does the attacker know?

| Label | Description |
| :---- | :---------- |
| Ciphertext-only   | Only chipertext is known |
| Known-Plaintext   | Know or suspect partial or full plaintext and known chipertext | 
| Chosen-Plaintext  | Encrypt arbitrary plaintext and obtain ciphertext (with same key) | 
| Chosen-Chipertext | Decrypt arbitrary chipertext and obtain plaintext (with same key) |
| Chosen-Text       | Encrypt/Decrypt arbitrary Plaintext/Ciphertext (with same key) |

Attacker could apply different methods based on attacker context.

## Lessons
| Lesson                                | Date        | Description |
| :----:                                 | ----        | ----------- |
| [Classical Cryptografy](./Classical.ipynb)   | 11/03/2021  | Transposition and substitution ciphers |
| [Symmetric Cryptografy - Block Cipher](./Symmetrical/Block%20Cipher.ipynb)   | 25/03/2021  | Block Ciphers: DES/AES and Cipher Modes.  |
| [Symmetric Cryptografy - Stream Ciphers](./Symmetrical/Block%20Stream%20Cipher.ipynb)   | 08/04/2021  | Symmetric ciphers: RC4 |
| [Symmetric Cryptografy - Random Number Generator](./Random%20Number%20Generator.md)   | 08/04/2021  | Random Numbers Generators: TRNG, PRNG and PRF |
| [Asymmetric Cryptografy - Math](./Asymmetrical/Math.ipynb)   | 14/04/2021  | Theory of Numbers and finite fields |
| [Asymmetric Cryptografy - RSA](./Asymmetrical/RSA.ipynb)   | 14/04/2021  | **R**ivest–**S**hamir–**A**dleman Cryptosystem |
| [Asymmetric Cryptografy - Diffie Hellman Exchange](./Asymmetrical/Diffie_Hellman.ipynb)   | 21/04/2021  | Diffie–Hellman key exchange |
| [Hash Cryptografy ](./Hash/SHA.ipynb)   | 08/04/2021  | Hash Functions: MD5 and SHA |

