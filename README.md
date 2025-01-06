# Avalanche Token Deployment

This project demonstrates the creation and deployment of an ERC-20 token named `SAT` on the Avalanche network. It includes a Vault contract to manage token deposits and withdrawals.

## Features
- **ERC-20 Token**: Fully compliant with the ERC-20 standard.
- **Vault Contract**: Allows users to deposit and withdraw tokens.
- **Custom Token Name**: `SAT`
- **Minting & Burning**: Tokens can be minted and burned.

## Tools Used
- **Remix IDE**: For contract development and deployment.
- **MetaMask**: To interact with the contracts.
- **Avalanche C-Chain**: Blockchain network for deployment.

## Deployment and Interaction Guide  

### **Deploy the Contracts**  
1. Open the following files in [Remix IDE](https://remix.ethereum.org/):  
   - `contracts/ERC20.sol`  
   - `contracts/Vault.sol`  
2. Connect Remix to the **Avalanche C-Chain** using **MetaMask**:  
   - Add the Avalanche C-Chain to MetaMask if it's not already added.  
   - Switch MetaMask to the Avalanche network.  
3. Deploy the contracts:  
   - Deploy the `ERC20` contract first. Note down the deployed contract's address.  
   - Deploy the `Vault` contract, passing the `ERC20` contract's address as a parameter to its constructor.  

---

### **Interact with the Contracts**  
Using **MetaMask** and Remix IDE, you can interact with the deployed contracts:  

#### **ERC-20 Contract Interactions**  
- **Mint Tokens**:  
  Call the `mint` function with the desired token amount to mint tokens for your account.  
- **Burn Tokens**:  
  Call the `burn` function with the desired token amount to burn tokens from your account.  
- **Transfer Tokens**:  
  Use the `transfer` function to send tokens to another address.  

#### **Vault Contract Interactions**  
- **Deposit Tokens**:  
  Call the `deposit` function with the number of tokens you want to deposit. Make sure you approve the Vault contract to spend your tokens using the `approve` function of the ERC-20 contract.  
- **Withdraw Tokens**:  
  Call the `withdraw` function with the number of shares you want to burn to retrieve the corresponding amount of tokens.  

---

## Demo Video
Watch the demo of this project on Loom:

[![Watch the video](https://www.loom.com/embed/bf6f6294c11d427693e5f5902d5b285e)](https://www.loom.com/share/bf6f6294c11d427693e5f5902d5b285e?sid=313df44a-877b-427c-9ea1-1c86e54cffb6)

---

Alternatively, [click here to view the video](https://www.loom.com/share/bf6f6294c11d427693e5f5902d5b285e?sid=313df44a-877b-427c-9ea1-1c86e54cffb6).
