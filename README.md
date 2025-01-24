# Solana Anchor Project

This project demonstrates the use of Anchor in the Solana blockchain to manage accounts. It allows users to create accounts containing messages of up to 150 characters and update them using predefined instructions.

## Features

1. **Account Creation**: Initialize a new account with a custom message (up to 150 characters). The message is stored securely on-chain.
2. **Message Update**: Modify the message of an existing account, adhering to the same character limit.
3. **Data Validation**: Ensures that all messages conform to the defined size constraints, providing error handling for overly long inputs.

## Getting Started

To deploy and interact with this project:

1. Install Anchor framework.
2. Clone this repository.
3. Build and deploy the program using `anchor build` and `anchor deploy`.
4. Use the provided scripts or a Solana client to initialize and update accounts.

## Use Cases

This project is ideal for learning about account management and on-chain data handling in Solana. It provides a foundational structure for developers to build more complex applications on the Solana blockchain.

Feel free to extend or adapt this project to suit your specific needs!
