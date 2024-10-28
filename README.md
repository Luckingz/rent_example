# Rent Example using Steel and Poseidon

## Overview
This example demonstrates how rent works on Solana. It shows how to check if an account has enough balance to be rent-exempt.

## Dependencies
- [Anchor](https://www.anchor-lang.com/docs/installation) (v0.26 or higher)
- [Solana CLI](https://docs.solana.com/cli/install-solana-cli-tools) (v1.10 or higher)

## Setup Instructions
1. Clone the repository and navigate to the example directory.
2. Install dependencies:
   ```bash
   anchor build
   anchor deploy
   ```

## Run Instructions
1. To deploy:
   ```bash
   anchor deploy
   ```
2. Run the example test:
   ```bash
   anchor test
   ```

## Testing
The test checks if an account is rent-exempt and passes if it has sufficient balance.
