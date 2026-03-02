#  Mathematicians in Cryptography

A chronological, code-first reconstruction of the mathematicians who shaped modern cryptography.

Each entry combines:

- Historical narrative  
- Mathematical foundations  
- Reproducible Jupyter notebooks  
- Modern security relevance  

---

## Classical Foundations

### Al-Kindi (c. 801–873)
→ Frequency analysis, first systematic cryptanalysis  

### Leon Battista Alberti (1404–1472)
→ Polyalphabetic cipher, cipher disk  

---

## Mechanical & Pre-Computer Era

### Charles Babbage (1791–1871)
→ Broke the Vigenère cipher (unpublished at the time)  

---

## WWII & Early Modern Cryptanalysis

### Marian Rejewski (1905–1980)
→ Mathematical break of Enigma before WWII  

### Alan Turing (1912–1954)
→ Bombe machine, Banburismus, early computing theory  

### Claude Shannon (1916–2001)
→ Information theory, formal definition of secrecy  

---

## Birth of Public-Key Cryptography

### Clifford Cocks & Malcolm J. Williamson (1970s)
→ Early secret work at GCHQ (RSA + Diffie-Hellman equivalents)  

### Whitfield Diffie & Martin Hellman (1976)
→ Public-key key exchange  

### Ron Rivest, Adi Shamir, & Leonard Adleman (1977)
→ RSA  

---

##  Elliptic Curves & Modern Algebraic Cryptography

### Neal Koblitz & Victor S. Miller (1980s)
→ Elliptic Curve Cryptography (ECC)  

---

##  Provable Security & Complexity Theory Era

### Shafi Goldwasser
→ Probabilistic encryption, zero-knowledge proofs  

### Oded Goldreich
→ Foundations of modern cryptographic theory  

### Adi Shamir (ongoing contributions)
→ Secret sharing, identity-based crypto, numerous breakthroughs  

### Dan Boneh (contemporary)
→ Pairing-based cryptography, applied cryptosystems  

---

##  Post-Quantum & Future Cryptography

### Peter Shor
→ Shor’s Algorithm (quantum factoring)  

### Daniel J. Bernstein
→ Curve25519, modern and post-quantum cryptography  

---

##  Why This Project Exists

Cryptography did not emerge fully formed — it evolved.

From language statistics to mechanical analysis.  
From information theory to algebraic number theory.  
From computational complexity to quantum computation.

Each era built upon the last.

This project reconstructs that evolution step-by-step using modern Python tooling.

Rather than creating isolated demonstrations, I set out to build a structured, chronological portfolio that mirrors the intellectual progression of cryptography itself.

Across the series, the notebooks explore:

- Statistical reasoning (Al-Kindi, Shannon)  
- Combinatorics and permutation theory (Rejewski, Turing)  
- Number theory (RSA, Diffie–Hellman)  
- Algebraic geometry (Elliptic Curve Cryptography)  
- Complexity theory and provable security (Goldwasser, Goldreich)  
- Quantum algorithms (Shor)  
- Modern curve and post-quantum design (Bernstein)  

Each entry combines historical context, mathematical foundations, and executable implementation — translating foundational ideas into reproducible code.

This project serves as:

- A technical deep-dive into the foundations of security  
- A living reference library of cryptographic principles  
- A demonstration of end-to-end mathematical implementation  
- A long-form portfolio of applied cryptography  


---

##  Tech Stack

- Python 3.x  
- Jupyter Notebook  
- NumPy / Matplotlib / SymPy  
- Minimal external dependencies  

---

##  Educational Notice

All classical cipher implementations are for historical and educational demonstration only.

---
## Usage Notice
This project is for:

- Engineers who want deeper mathematical context  
- Security practitioners who want to revisit first principles  
- Students learning cryptography chronologically  
- Recruiters evaluating depth of technical understanding  

Every notebook is designed to be readable, reproducible, and extensible.