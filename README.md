# SHA-256 Cryptographic Implementation

## Overview

This repository contains a complete implementation of the SHA-256 cryptographic hash algorithm as specified in FIPS 180-4 (Federal Information Processing Standards Publication 180-4). The project demonstrates the mathematical foundations and step-by-step construction of SHA-256, from basic bitwise operations to the complete hashing function.

## Repository Structure
```
.
├── README.md           # This file
├── problems.ipynb      # Main Jupyter notebook with all problems
├── requirements.txt    # Python package dependencies
└── .gitignore         # Git ignore file
```

## Problems Completed

### Problem 1: Binary Words and Operations
Implements the seven core bitwise functions used in SHA-256:
- Parity, Ch (Choice), Maj (Majority)
- Sigma0, Sigma1 (uppercase - compression functions)
- sigma0, sigma1 (lowercase - message schedule functions)

### Problem 2: Fractional Parts of Cube Roots
Generates the 64 round constants (K) used in SHA-256 by calculating the first 32 bits of the fractional parts of cube roots of the first 64 prime numbers.

### Problem 3: Padding *(In Progress)*
### Problem 4: Hashes *(In Progress)*
### Problem 5: Passwords *(In Progress)*

## Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- NumPy library

## Installation

1. Clone this repository:
```bash
git clone <your-repository-url>
cd <your-repository-name>
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Launch Jupyter Notebook:
```bash
jupyter notebook
```

4. Open `problems.ipynb` and run the cells in order.

## Running the Code

**Important:** Always restart the kernel and run all cells in order to ensure proper execution:

1. In Jupyter: `Kernel` → `Restart & Run All`
2. Or press the "Restart & Run All" button in the toolbar

All imports are in the first code cell of each problem. Make sure to run cells sequentially.

## Dependencies

- **NumPy** - For 32-bit unsigned integer operations (uint32) and mathematical functions
- **Jupyter** - For interactive notebook environment

See `requirements.txt` for specific versions.

## References

- **FIPS 180-4: Secure Hash Standard**
  - National Institute of Standards and Technology (NIST)
  - URL: https://nvlpubs.nist.gov/nistpubs/FIPS/NIST.FIPS.180-4.pdf
  - Official specification for SHA-256 algorithm

- **Wikipedia - SHA-2**
  - URL: https://en.wikipedia.org/wiki/SHA-2
  - Accessible explanations and visual diagrams

## Author

Mohammad - Computer Science Student

## License

This project is for educational purposes as part of coursework requirements.

## Acknowledgments

- NIST for the FIPS 180-4 specification
- Course materials and lecture notes