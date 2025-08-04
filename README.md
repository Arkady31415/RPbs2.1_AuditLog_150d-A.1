# 🔐 RPbs2.1 — Offline Safe & Sophie Prime Generator

### Ultra-fast, offline discovery of cryptographically strong primes — no external libraries required.

---

## 🧬 What is RPbs2.1?

**RPbs2.1** is a custom-built Python algorithm designed to generate **Safe** and **Sophie Germain primes** from scratch — **offline**, with **no third-party libraries**, and at speeds that rival or outperform traditional brute-force methods.

This project is ideal for:
- Cryptography researchers
- Security engineers
- Blockchain developers
- Anyone needing fast, verifiable, large primes without external dependencies

---

## 🎯 Features

- ✅ Generates Safe and Sophie Germain primes
- ✅ Supports custom digit lengths (e.g. 150 to 1233 digits and beyond)
- ✅ Fully offline — no APIs or internet access needed
- ✅ Zero external libraries (no SymPy, GMP, OpenSSL, etc.)
- ✅ Built-in primality testing (multi-round Miller-Rabin)
- ✅ Multi-core parallelism for speed
- ✅ Companion-aware logging and SHA256 verification

---

## 🚀 Performance Example

| Digits | Primes Found | Attempts   | Runtime  | Efficiency      |
|--------|---------------|------------|----------|------------------|
| 150    | 100           | 13,066,872 | 13 sec   | ~937,739 attempts/sec |

Typical brute-force prime discovery at 150 digits:
> ~400,000 – 1,000,000 attempts per Safe/Sophie prime

**RPbs2.1 average:** ~130,000 attempts/prime ✅

---

## 🔒 Why Safe & Sophie Primes?

Safe and Sophie Germain primes are essential in:
- 🔐 Diffie-Hellman key exchange
- 🔒 RSA and ECC protocols
- 🧮 Lattice-based cryptography
- 🧾 Digital signatures and secure hashing





