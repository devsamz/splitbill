# My Token Contract

- **Name:** Split Bill Token
- **Symbol:** SBT

## Descripion

This is an ERC-20 called `Split Bill Token` with symbol `SBT`. The Contract inherits OpenZeppelin ERC20 standard, with extra implementation to mint, burn and transfer.

## Getting Started

### Executing program

To run this program, you can use Remix, an online Solidity IDE. To get started, go to the Remix website at https://remix.ethereum.org/.

Once you are on the Remix website, create a new file by clicking on the "+" icon in the left-hand sidebar. Save the file with a .sol extension (e.g., HelloWorld.sol). Copy and paste the code into the file


To compile the code, click on the "Solidity Compiler" tab in the left-hand sidebar. Make sure the "Compiler" option is set to "0.8.20" (or another compatible version), and then click on the "Compile token.sol" button.

Once the code is compiled, you can deploy the contract by clicking on the "Deploy & Run Transactions" tab in the left-hand sidebar. Select the "SplitBill" contract from the dropdown menu, and then click on the "Deploy" button.

Once the contract is deployed, you can interact with it by calling the mint, burn and transfer function.


## Contract Details

### Constructor

During Constructor time, The ERC-20 token name and symbol is set. Also the deployer become the owner of the contract.

### mint

The mint function allows new tokens to be generated and sent to a specified address. This function can only be called by the contract owner.

### transfer

Allows holders of the token to transfer an amount of the token to another address provided that their balance is greater than that amount.

### burn

This function allows the holders to burn a specified amount, hence erasing it from the total supply. Holders must have sufficient amount to burn

## License

This project is licensed under the MIT License