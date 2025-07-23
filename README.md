## 🔐 Cryptography in Network Security

This is my project I implmented to provides practical implementations and theoretical insights into **Cryptography in Network Security**, covering both **symmetric** and **asymmetric encryption algorithms**, as well as **hash functions**. The goal is to demonstrate encryption, decryption, and integrity verification using various classical and modern cryptographic techniques.

### 📁 Contents

* `waggari_Additive Cipher.ipynb` – Symmetric cipher using modular addition
* `waggari_Multiplicative Cipher.ipynb` – Symmetric cipher using modular multiplication
* `waggari_DES.ipynb` – Data Encryption Standard using `pycryptodome`
* `waggari_AES.ipynb` – Advanced Encryption Standard implementation
* `waggari_RSA.ipynb` – Asymmetric encryption using RSA
* `waggari_Hash Functions.ipynb` – Hashing with SHA-256 and integrity check


### 🧪 Implemented Algorithms

#### ✅ Symmetric Key Cryptography

1. **Additive Cipher**

   * Algorithm: Shift each character by a fixed key modulo 26 (or ASCII range)
   * Application: Simple substitution, educational purposes
   * Feature: Fast but insecure for modern systems

2. **Multiplicative Cipher**

   * Algorithm: Multiply each character by a key modulo 26
   * Application: Classic cipher technique
   * Limitation: Only works with keys coprime to modulus

#### ✅ Block Ciphers (Symmetric, Modern)

3. **DES (Data Encryption Standard)**

   * 56-bit key, 64-bit block
   * Implemented with ECB mode (for demonstration)
   * Application: Secure legacy systems

4. **AES (Advanced Encryption Standard)**

   * 128/192/256-bit keys
   * Application: Military, financial, and data-at-rest encryption
   * Mode: ECB for simplicity; can be extended to CBC or GCM

#### ✅ Asymmetric Key Cryptography

5. **RSA Algorithm**

   * Key generation, public-private encryption/decryption
   * Application: Secure key exchange, digital signatures
   * Key size: 2048-bit used

#### ✅ Hash Functions

6. **SHA-256**

   * One-way hashing
   * Application: Password security, digital integrity, blockchain
   * Note: Irreversible by design – verified via recomputation


### 📌 Project Goals

* Demonstrate how classical and modern ciphers work
* Accept input from users for encryption/decryption
* Show that **decrypted message exactly matches original plaintext**
* Highlight use-cases and application areas for each algorithm


### 🧭 How to Use

1. Clone https://github.com/Wagarimisganu-github/Cryptograpy-in-Network-Security.git
2. Install dependencies:

   ```bash
   pip install pycryptodome
   ```
3. Open each `.ipynb` notebook in Jupyter
4. Run cells and provide input as prompted


### 🔭 Future Work
### My future direction is on:
* ✅ Add **CBC, GCM modes** for AES/DES for improved security
* ✅ Implement **Elliptic Curve Cryptography (ECC)** for modern key exchange
* ✅ Integrate **digital signatures** using RSA and hashing
* ✅ Add **Diffie-Hellman Key Exchange** simulation
* ✅ Extend the system to support **file encryption**
* ✅ Build a **GUI app** or web interface for real-time encryption tasks
* ✅ Add timing and performance analysis for each algorithm


### 🙌 Author

### Waggari Misganu Ebsa, Certified in Cyber Security.
### Github link: https://github.com/Wagarimisganu-github
#### Email: wagarimisganu12@gmail.com
### Linkedin: https://www.linkedin.com/in/waggari-misganu-ebsa-352601317
 I also Appriceate **Mrs Aster Takele** for her Contribution
#### Aknowledgmnets
 Special Thanks to **Dr Naol B (PHD)**.
