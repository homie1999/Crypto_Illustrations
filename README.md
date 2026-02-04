# Crypto Illustrations

Visual guides to cryptographic algorithms, designed to make complex security concepts more accessible and understandable.

## Current Illustrations

### AES (Advanced Encryption Standard)
Block cipher encryption process visualization.

![AES Illustration](/images/AES.png)


Visual breakdown of the AES encryption process showing the four main transformations: SubBytes (substitution via S-box lookup table), ShiftRows (permutation by shifting rows), MixColumns (mixing columns through polynomial multiplication in GF(2⁸), and AddRoundKey (XOR with round key). Illustrates the round structure for different key sizes (128-bit: 10 rounds, 192-bit: 12 rounds, 256-bit: 14 rounds) and the key expansion process using shifts, 8-bit polynomial arithmetic, and exclusive OR operations.

### S-DES (Simplified DES)
Educational cipher demonstrating DES principles.

![S-DES Illustration](/images/S-DES.png)

Complete walkthrough of Simplified DES encryption demonstrating all stages: Initial Permutation (IP), the Feistel structure with 16 rounds, the Mangler Function (expansion permutation, S-box substitution, P-box permutation), and Final Permutation. Includes detailed subkey generation algorithm showing permutation P10, circular shifts (LS-1), P8 transformations, and how the 10-bit master key produces subkeys K1 and K2. Shows a concrete example with plaintext (00111110), key (1011000110), and resulting ciphertext, with step-by-step transformations through the entire algorithm.

## Purpose
These illustrations are created to help students, developers, and security enthusiasts understand how cryptographic algorithms work at a conceptual level. Each diagram emphasizes clarity and accuracy while remaining accessible to those learning cryptography.

## Usage
Feel free to use these illustrations for educational purposes, presentations, or documentation with proper attribution.

## License
This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

![CC BY 4.0](https://i.creativecommons.org/l/by/4.0/88x31.png)
