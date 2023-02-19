# In House CTF 2023

Provided below are a list of ideas for challenges.

## Easy

Listed are challenges that would be easy to implement and are a straightforward application of things taught in the seminars.

### Cryptography (crypto)

- Various ciphers
  - [ ] Caesar cipher
  - [ ] Vigènere cipher
  - [ ] Morse code
  - [ ] One-time Pad but Reused (e.g. `Easy Peasy`)
  - [ ] XOR a bunch of keys and the flag, and decode using the property (`a ^ b ^ b = a`)
- [ ] Simple example for RSA (given `p, q, c`, find `m`).

### Reverse Engineering (rev)

- [ ] Take a Java file that encodes its flag using a set of functions (e.g. `vault-door` challenges)
- [ ] Obfuscated Python file
- [ ] Provide a script which has a glaring security vulnerability (such as being able to read files in its directory). Use that to get the text of the flag in the directory.

### Web Exploitation (web)

- [ ] HTML, CSS, JS, where the flag is located in the source files (e.g. `Insp3ct0r`).
- [ ] SQL Injection (e.g. `Irish-Name-Repo` challenges)
- [ ] Simple XSS (Enter JS code into a form)

### Forensics (foren)

- Hide a flag in various different filetypes
  - [ ] .png
  - [ ] .pdf
  - [ ] .svg
  - [ ] .docx, .pptx, .xlsx (or any other file which is just a .zip in disguise)

### Binary Exploitation (pwn)

- [ ] Crash a program (e.g. `buffer-overflow-0`)
- [ ] Edit some visible part in memory (e.g. `buffer-overflow-1` and `clutter-overflow`)

## Not Fully Explored

Any challenges which are moderately okay to implement and may require pointers for competitors.

- [ ] web: `Insp3ct0r`-esque challenge, but using TypeScript and object maps
- [ ] ???: Given a hash, crack it via john + rockyou.txt
- [ ] rev: Read an assembly file
- [ ] rev: Read a Java bytecode file (`.class`) using a decompiler
- [ ] rev: Read a compiled Python file (`.pyc`) into bytecode using `dis.dis`
- [ ] pwn: Introduce pwntools
- crypto: Possibly adapt scavenger hunt ideas?
  - [ ] 1. Caesar cipher + ASCII
  - [ ] 2. Running Python code
  - [ ] 3. Railfence cipher, Vigènere cipher, book code
  - [ ] 4. Fill in the blank CS trivia (likely not viable)
  - [ ] 5. Programming language word search (likely not viable)

## Far Off

Any challenges which would be difficult to make and also require advanced Googling to solve.

- [ ] pwn: ROP chain
- [ ] crypto: RSA attack, using Coppersmith attack
- [ ] crypto: Basic introduction to elliptic curves
