# Simple README for ERC20 and Vault Contracts

## ERC20 Contract

The ERC20 contract represents a basic implementation of an Ethereum token adhering to the ERC20 standard.

### Features:
- **Transfer**: Users can transfer tokens between Ethereum addresses.
- **Approve**: Allows users to approve another address to spend tokens on their behalf.
- **Transfer From**: Enables approved addresses to transfer tokens on behalf of the token owner.
- **Mint**: Token owners can create new tokens, increasing the total token supply.
- **Burn**: Token owners can destroy tokens, decreasing the total token supply.

### Events:
- **Transfer**: Triggered whenever tokens are transferred between addresses.
- **Approval**: Triggered when token approval is granted for spending.

## Vault Contract

The Vault contract serves as a secure storage solution for ERC20 tokens, facilitating deposit and withdrawal operations while managing token balances internally.

### Features:
- **Deposit**: Users can deposit ERC20 tokens into the vault, receiving corresponding "shares" representing ownership.
- **Withdraw**: Users can withdraw tokens from the vault by burning their "shares," retrieving the equivalent amount of ERC20 tokens.
- **Shares Management**: Tracks total shares supply and individual share balances for users.
- **Efficient Deposits and Withdrawals**: Computes shares dynamically to ensure fair token distribution upon deposit and withdrawal.
