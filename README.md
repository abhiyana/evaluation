# Introduction
This repository contrain Assessment Submission of task given by HogoByte.

## Blockchain Ledger
This is a simple implementation of a blockchain ledger in C++. It allows you to add transactions, create blocks, validate the ledger, and print the ledger.

## Prerequisites
To compile and run this code, you need to have the following installed on your system:

- C++ compiler (supporting C++11 or later)
- OpenSSL library


## Compilation
To compile the code, follow these steps:

1. Clone the repository or download the source code files.
2. Open a terminal or command prompt.
3. Navigate to the directory where the source code files are located.
4. Run the following command to compile the code:
  - g++ blockchain.cpp -o program -lssl -lcrypto  (This command uses the g++ compiler, sets the C++ version to C++11, and links against the OpenSSL library.)
  
## Execution
1. Open a terminal or command prompt.
2. If there are no compilation errors, an executable file named `program` will be generated in the same directory.
   Navigate to the directory where the `program` executable is located.
   - ./program
 
## Usage
Here's a brief description of the available operations:

1. **Add Transaction**: Allows you to add a transaction to the transaction pool.
2. **Add Block**: Creates a new block with the transactions in the transaction pool and adds it to the blockchain.
3. **Validate Ledger**: Checks the integrity and validity of the blockchain.
4. **Print Ledger**: Displays the entire blockchain with block details and transactions.
5. **Exit**: Quits the program.



