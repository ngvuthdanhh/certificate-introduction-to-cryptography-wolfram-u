# ⚔️ Playbook: Cryptographic Attacks & Defenses

This playbook explains common cryptographic attacks and how to mitigate them.

---

## 1. Replay Attacks
- **Attack:** Reuse of valid encrypted messages.
- **Defense:** Use **nonces** or **timestamps** in protocols.

---

## 2. Padding Oracle Attacks
- **Attack:** Exploit error messages in block cipher padding.
- **Defense:** Apply **constant-time error handling** and **AES-GCM/ChaCha20-Poly1305**.

---

## 3. Side-Channel Attacks
- **Attack:** Exploit timing, power consumption, or EM leaks.
- **Defense:** Use **constant-time implementations** and **hardware protections**.

---

## 4. Weak Hash Collisions
- **Attack:** Forge documents with same MD5/SHA-1 hash.
- **Defense:** Use **SHA-256/3** or **SHAKE** (from Keccak family).

---

## 5. Man-in-the-Middle (MITM)
- **Attack:** Intercept and alter communications.
- **Defense:** Enforce **certificate pinning**, **HSTS**, and strong **mutual authentication**.

---

✅ **Key Lesson:** Cryptography is only as strong as its implementation and protocol design.
