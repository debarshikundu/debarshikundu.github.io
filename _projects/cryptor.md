---
title: "cryptor"
summary: "A small Python encryption and decryption tool built to understand how cryptographic primitives behave in practice."
status: "Maintained"
role: "Developer"
stack: ["Python", "Cryptography", "CLI"]
repo: "https://github.com/debarshikundu/cryptor"
featured: true
order: 2
---

## Why I built it

Reading about encryption is not the same as using it. I wanted a tool small enough to read end-to-end, where I could see exactly what happens to data between "plaintext in" and "ciphertext out" — and where mistakes would be mine rather than hidden behind a framework.

## What it does

`cryptor` is a Python command-line tool for encrypting and decrypting data. It handles the unglamorous parts that are easy to get wrong: converting between bytes and text, handling keys, and failing loudly instead of silently producing garbage.

## What I learned

- **Encoding is not encryption.** A large share of beginner mistakes happen before any cipher is involved.
- Key handling and error messages are part of the security surface, not an afterthought.
- Rolling your own crypto is a great way to learn and a terrible way to ship. The educational value is in understanding why the recommended primitives exist.

## Using it

Clone the repository and run it locally:

```bash
git clone https://github.com/debarshikundu/cryptor
cd cryptor
python cryptor.py --help
```

For anything real, use a vetted library such as `cryptography` or `libsodium` rather than this project. The point here is the learning, not the production deployment.
