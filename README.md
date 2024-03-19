### Smart Contract: Escrow

#### Description:
The Escrow smart contract is designed to facilitate secure transactions between parties by holding funds until predefined conditions are met. It ensures that payments are made only when specified criteria, such as agreement by all involved parties, are fulfilled. This smart contract is implemented in Solidity and can be deployed on the Ethereum blockchain.

#### Functions:
- **Constructor**: Initializes the Escrow contract with the payer's address, payee's address, lawyer's address, and the amount to be held in escrow.
- **deposit()**: Allows the payer to deposit funds into the escrow. The sender must be the payer, and the amount deposited cannot exceed the specified escrow amount.
- **release()**: Allows the lawyer to release funds from the escrow to the payee once the full escrow amount has been deposited and all conditions are met.
- **balanceOf()**: Retrieves the current balance held in the escrow contract.

#### Usage:
1. **Deployment**: Deploy the Escrow contract on the Ethereum blockchain.
2. **Initialization**: Provide the payer's address, payee's address, lawyer's address, and the escrow amount when deploying the contract.
3. **Deposit**: The payer can deposit funds into the escrow contract using the `deposit()` function.
4. **Release**: Once all conditions are met, the lawyer can release the funds to the payee using the `release()` function.
5. **Balance Check**: The current balance held in the escrow contract can be checked using the `balanceOf()` function.

---

### Frontend Application

#### Description:
The frontend application provides a user interface to interact with the Escrow smart contract deployed on the Ethereum blockchain. It allows users to deposit funds into the escrow, release funds, and view the current balance.

#### Components:
- **React Component**: A React component that interacts with the deployed Escrow smart contract.
- **Web3 Integration**: Utilizes Web3.js to connect to the Ethereum blockchain and interact with smart contracts.
- **User Interface**: Provides a simple user interface for depositing funds, releasing funds, and displaying the current balance.

#### Usage:
1. **Setup**: Ensure that Node.js and npm are installed on your system.
2. **Install Dependencies**: Install the necessary dependencies by running `npm install`.
3. **Connect to Ethereum Network**: Configure MetaMask or any Ethereum wallet to connect to the desired Ethereum network.
4. **Run the Application**: Start the application by running `npm start` in the project directory.
5. **Interaction**: Use the provided user interface to deposit funds, release funds, and view the current balance of the escrow contract.

---
