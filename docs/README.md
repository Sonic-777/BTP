# BTP
## Overview
The BTP project implements a **Verifiable Delay Function** using permutation polynomials. This project provides a set of tools to generate and check permutation polynomials, which are essential for the Verifiable Delay Function.

## Key Modules
| File | Purpose |
|------|---------|
| `pp_binomial.py` | Generates all possible binomials of degree up to n |
| `pp_check.py` | Checks whether a given polynomial is a permutation polynomial |
| `sage_time.py` | Checks whether a given polynomial is a permutation polynomial using Sage |
| `pp1.py` | Main module for permutation polynomial operations |
| `README.md` | Project description and documentation |

## Usage
To get started, use the `binaryToPolynomial` function in `pp1.py` to convert a binary string to a polynomial. For example:
```python
from pp1 import binaryToPolynomial
binary_str = "1010"
polynomial = binaryToPolynomial(binary_str)
print(polynomial)
```