# My Token Contract

- **Name:** Split Bill Token
- **Symbol:** SBT

## Descripion

This is an ERC-20 called `SplitBillToken` with symbol `SBT`. The Contract inherits OpenZeppelin ERC20 standard, with extra implementation to mint, burn and transfer.

## Contract Details

**Contract Address:** https://sepolia.etherscan.io/address/0x4b7856f3a829a14cb93e237d23e4fbde6be4e79c

**Loom 2 (etherscan):** https://www.loom.com/share/c9f44b40c8e54fa2b163886ba2ceb650?sid=42dc1f0d-2d36-489f-926e-998a25580bde

### Constructor

Upon deploying the contract, The ERC-20 token name and symbol is set. Also the deployer become the owner of the contract.

### mint

The mint function allows new tokens to be generated and sent to a specified address. This function can only be called by the contract owner.

### transfer

Allows holders of the token to transfer an amount of the token to another address provided that their balance is greater than that amount.

### burn

This function allows the holders to burn a specified amount, hence erasing it from the total supply. Holders must have sufficient amount to burn

## License

This project is licensed under the MIT License