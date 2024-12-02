```markdown
# El-Gamal and RSA Schemes Implemented with Socket Programming

This program demonstrates socket programming with end-to-end encryption for communication between a client and a server using two encryption schemes:

1. **El-Gamal public-key encryption**
2. **RSA public-key encryption**

## File Descriptions

- **el_gamal.py**: Contains the functions required for the El-Gamal encryption scheme, including:
  - Key generation
  - Encryption
  - Decryption
  - Auxiliary functions for formatting input and output for encryption/decryption processes.

- **rsa.py**: Contains the functions required for the RSA encryption scheme, including:
  - Key generation
  - Encryption
  - Decryption
  - Auxiliary functions for formatting input and output for encryption/decryption processes.

- **client.ipynb**: Contains the client-side code.
- **server.ipynb**: Contains the server-side code.

To select the desired encryption scheme, uncomment the corresponding import statement in either `el_gamal.py` or `rsa.py` in the import section.

## Demonstration Notebooks

- **'El-Gamal Crypto-scheme.ipynb'**: Demonstrates how the El-Gamal encryption scheme works.
- **'RSA.ipynb'**: Demonstrates how the RSA encryption scheme works.

## Technical Details

- The program uses an **84-bit prime number** (25 digits) for encryption.
- **gmpy2** is used for efficient modular arithmetic on large numbers.

## Installation

1. **Install gmpy2**  
   To install **gmpy2**, use the following link:
   [Install gmpy2](https://anaconda.org/conda-forge/gmpy2)

2. **Install pyecm**  
   Download **pyecm.py** from [here](https://github.com/martingkelly/pyecm) for fast prime factorization of large numbers.

## How to Run

1. Choose your preferred encryption scheme by uncommenting the corresponding import statement in the `client.ipynb` and `server.ipynb` files.
2. Run the `client.ipynb` on the client machine and `server.ipynb` on the server machine.
3. The client and server will communicate with end-to-end encryption using the selected encryption scheme.

```
