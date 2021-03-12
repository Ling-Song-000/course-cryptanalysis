# Cryptanalysis

Learn about cryptographic attacks and how to apply this knowledge to design secure cryptographic primitives.

## Lecturer

### Ling Song

![ling_picture](./PageResources/ling_song.png)

## Calendar and schedule/ 校历和课表

* Time: 18:30 - 20:10 Wednesday
* Calendar / 校历 [Open](./Time-Schedule/2020-2021Calendar.pdf)
* Class schedule / 课表 [Open](./Time-Schedule/20-class-schedule.pdf)
* Week 01 - Week 16: lecture
* Week 17 - Week 20: seminar and presentation

## Goals and Contents

This course aims to give you in-depth knowledge about the cryptographic attacks, focusing on cryptanalysis of symmetric ciphers and asymmetric ciphers. More precisely, this course covers the following topics:

* Introduction to Cryptanalysis
  * Kerckhoffs' principle
  * Notions of security: confidentiality, integrity, authenticity and more
  * Models of attack
  * Targets of attack
  * Theoretical attacks vs. practical attacks
  * Lessons learned from classic ciphers
* Cryptanalysis of block ciphers
  * Meet-in-the-Middle attack & TMTO
  * Basic differential analysis
  * Basic linear analysis
  * Wide-trail strategy and AES
  * More (optional)
    * Integral cryptanalysis
    * Truncated differential attack
    * Higher order differential attack
    * Boomerang and rectangle attacks
    * Impossible differential attack
    * Multi dimensional linear attack
    * Zero-correlation linear attack
    * Division property
    * Demirci-Selcuk MitM attack
    * Subspace trail cryptanalysis
* Cryptanalysis of stream ciphers
  * Guess-and-determine attack on stream ciphers
  * Time-Memory-Data trade off attack
  * Linear distinguisher and correlation attacks
* Cryptanalysis of hash functions
  * Birthday attacks
  * MD and Sponge
  * Differential cryptanalysis and collision attacks
  * Meet-in-the-Middle Pre-image attack
* Computer-aided cryptanalysis
  * MILP-based cryptanalysis
  * SAT-based cryptanalysis
* Algebraic cryptanalysis
  * Interpolation attack
  * Cube attacks and Higher order differential attack
  * Linearization
* Merkle-Hellman Knapsack
* Diffie-Hellman Key Exchange and MitM
* Discrete Log algorithms
  * Baby-step giant-step
* Factoring algorithms  
  * Dixon’s Algorithm
  * Quadratic Sieve
* Quantum algorithms

## Material

### Slides

Todo

### Exercises

* Exercises after each section
  * [Homework 1](Exercises/Exercise1/Exercise1.pdf)

### Four Projects

* Search for the best differential trails with MILP/SAT
* Search for the integral distinguishers based on division property using MILP/SAT
* Search for the cube attacks on stream ciphers with MILP/SAT
* Search for cubes for Keccak
* Find parameters for the guess-and-determine attacks with MILP
* Implement Wiener's attack on RSA
* Implementing the dark-side and nested attacks on RFIC cards

### Suggested Topics for Seminars (choose one)

* Designs of stream ciphers with small states
* RSA and Shor's algorithm
* Differential analysis of keyless permutations
* Search for differential trails with MILP/SAT for pSP
* Machine learning-based symmetric cryptanalysis
* Hybrid approaches including:
  * Differential-Linear Attack
  * Algebraic-Differential Attack

### Textbooks

#### Applied Cryptanalysis: Breaking Ciphers in the Real World

![applied_crypto_stamp](./PageResources/applied_cryptanalysis_stamp.png)

[Website](http://www.cs.sjsu.edu/~stamp/crypto/)

#### Algorithmic Cryptanalysis

![algorithmic_cryptanalysis](./PageResources/agorithmic_cryptanalysis_joux.png)

#### Techniques for Cryptanalysis of Block Ciphers

![techniques_for_cryptanalysis_of_block_ciphers](./PageResources/techniques_for_cryptanalysis_of_block_ciphers.jpeg)

[Website](https://www.springer.com/gp/book/9783642172311)

#### The Block Cipher Companion

![block_cipher_companion](./PageResources/block_cipher_companion.jpg)

[Website](http://www2.mat.dtu.dk/people/Lars.R.Knudsen/bcc/)

#### An Introduction to Mathematical Cryptography

![into_to_mathematical_crypto](./PageResources/intro_to_mathematical_crypto_hoffstein.jpg)

#### A Salad of Block Ciphers

![a_salad_of_block_ciphers](./PageResources/a_salad_of_block_ciphers_avanzi.png)

[Download book](./Books/a_salad_of_block_ciphers.pdf)

It is available on Cryptology ePrint Archive:

[https://eprint.iacr.org/2016/1171](https://eprint.iacr.org/2016/1171)

#### A Self-Study Course in Block-Cipher Cryptanalysis

![bruce_schneier](./PageResources/bruce_schneier.png)

Studying cryptanalysis is difficult because there is no standard textbook, and no way of knowing which cryptanalytic problems are suitable for different levels of students. This paper attempts to organize the existing literature of block-cipher cryptanalysis in a way that students can use to learn cryptanalytic techniques and ways to break new algorithms.

[Download book](./Books/paper_self_study.pdf)

It is publicly available via the following link:

[https://www.schneier.com/wp-content/uploads/2016/02/paper-self-study.pdf](https://www.schneier.com/wp-content/uploads/2016/02/paper-self-study.pdf)