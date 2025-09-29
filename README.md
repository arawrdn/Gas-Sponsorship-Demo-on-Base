# Gas Sponsorship Demo (Base)

## Description
Gas Sponsorship Demo allows users to interact with a smart contract **without paying gas fees**. Owner provides ETH to cover gas.  

### Features
- Single click interaction, no input required.
- Maximum 15 wallets (FCFS), each wallet can claim only once.
- Gas automatically reimbursed from sponsor's ETH.
- Easy verification on BaseScan (Solidity 0.8.30, optimizer yes, runs 200).

## Usage
1. Compile `GasSponsorDemo.sol` in Remix (Solidity 0.8.30, optimizer yes, runs 200).  
2. Deploy to Base testnet/mainnet.  
3. Owner deposits ETH with `deposit()`.  
4. Users call `doSomething()` → gas reimbursed automatically.  
5. Owner can withdraw remaining ETH with `withdraw()`.  

## Verification
- Copy full Solidity code.  
- Compiler: 0.8.30, Optimization: Yes, Runs: 200.  
- Constructor: none (empty).  
- Submit → contract verified on BaseScan.
