# RSA Encryption and Decryption Implementation

This repository contains a Python implementation of the RSA encryption and decryption algorithm. The implementation includes key generation, encryption, and decryption processes, along with helper functions for primality testing, modular arithmetic, and message encoding/decoding.

## Features

- **Extended Euclidean Algorithm (EEA):** Solves the equation `au + bv = gcd(a, b)` and computes Bézout coefficients.
- **Modular Inverse:** Computes the modular inverse of a number using the EEA.
- **Primality Testing:** Implements a probabilistic primality test to generate large prime numbers.
- **RSA Key Generation:** Generates public and private keys using two large safe primes.
- **Message Encoding/Decoding:** Converts text messages to integers and vice versa for encryption and decryption.
- **Encryption and Decryption:** Encrypts and decrypts messages using the RSA algorithm.

## Usage

1. **Key Generation:**
   - Two large safe primes `p` and `q` are provided.
   - The `key_generation_rsa` function generates the public key `(N, e)` and private key `(N, d)`.

2. **Encryption:**
   - The `encryption` function encodes a message into a numerical format and encrypts it using the public key.

3. **Decryption:**
   - The `decryption` function decrypts the ciphertext using the private key and decodes it back into the original message.
