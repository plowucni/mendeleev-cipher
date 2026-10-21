# Mendeleev Periodic Table Cipher

Algorithmic text encoder written in **C** that converts alphabetical strings into sequence representations based on atomic numbers of chemical elements (118 elements from the Periodic Table).

## Algorithm & Backtracking

The core encoding engine processes tokens recursively using a **backtracking strategy**:
1. Priority matching for 2-letter atomic symbols.
2. Fallback matching for 1-letter atomic symbols.
3. Backtracks state upon invalid path traversal until full word coverage is resolved.

## Build & Execution

### Compilation
```bash
gcc main.c -o mendeleev_cipher
./mendeleev_cipher
