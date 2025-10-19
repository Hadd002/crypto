# AI Agent Instructions for Crypto Codebase

## Project Overview
This repository contains solutions and implementations for various cryptography challenges from platforms like CryptoHack, Cryptopals, and PicoCTF. The codebase is organized by challenge platforms and topics.

## Repository Structure
- `CryptoHack/` - Solutions organized by cryptographic topics:
  - `Introduction/` - Basic cryptography concepts
  - `Modular_Arithmetic/` - Number theory fundamentals
  - `elliptic_Curves/` - ECC implementations
  - `public_key_cryptography/` - RSA and other PKC challenges
  - `Symmetric_Cryptography/` - AES and other symmetric ciphers

- `Cryptopals/` - Solutions for Cryptopals challenge sets
- `picoctf/` - Solutions for PicoCTF cryptography challenges

## Code Organization Patterns
1. Each challenge solution is contained in its own directory
2. Primary solution files are named `solve.py`
3. Additional helper files may exist for specific challenges (e.g., `decrypt.py`, `source.py`)

## Common Implementation Patterns
1. Modular Arithmetic Functions:
   - Extended GCD implementations in `Modular_Arithmetic/Mod_Arith01/extended_gcd.py`
   - Modular exponentiation in `Modular_Arithmetic/Mod_Arith03/power.py`

2. RSA Implementations:
   - See examples in `picoctf/Mind_your_Ps_and_Qs/solve.py`
   - No padding implementations in `picoctf/No_Padding_No_Problem/solve.py`

3. Classical Ciphers:
   - Caesar cipher variations in `picoctf/ceasar/solve.py` and `picoctf/New_Ceasar/solve.py`

## Development Workflow
1. Solutions are self-contained Python scripts
2. Each solution can be run independently
3. Dependencies are minimal, focusing on standard library cryptography implementations

## Best Practices
1. Maintain challenge solutions in separate directories
2. Include original challenge source files when available
3. Implement reusable cryptographic primitives in dedicated modules

## Key Files for Reference
- `/CryptoHack/elliptic_Curves/elliptic_Curves_00/solve.py` - ECC fundamentals
- `/CryptoHack/Modular_Arithmetic/Mod_Arith01/extended_gcd.py` - Number theory basics
- `/picoctf/Mini_RSA/solve.py` - RSA implementation patterns

## Testing and Validation
Solutions are verified against the respective challenge platforms:
- CryptoHack (https://cryptohack.org/)
- Cryptopals (https://cryptopals.com/)
- PicoCTF (https://picoctf.org/)