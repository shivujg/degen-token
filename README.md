# DegenToken and DeviceContract

This Solidity code implements smart contracts for managing tokens (DegenToken) and devices (DeviceContract) on the Ethereum blockchain.

## DegenToken

DegenToken is a standard ERC20 token contract with additional functionalities for managing devices.

### Functions:

- **createDevice**: Allows the contract owner to create new types of devices and set a fee for each device.
- **redeemDevice**: Enables token holders to exchange their tokens for devices by paying the required fee.
- **transferTokens**: Allows token holders to transfer their tokens to other addresses.
- **mint**: Enables the contract owner to create new tokens and assign them to specific addresses.
- **burn**: Allows token holders to burn (destroy) a specific amount of their tokens.

### Events:

- **DeviceRedeemed**: Triggered when a token holder redeems a device, indicating the account, device contract address, and total fee paid.

## DeviceContract

DeviceContract represents different types of devices that users can obtain using DegenToken.

### Constructor Parameter:

- **fee**: Specifies the fee required to redeem the device.

## Usage:

1. **Deploy Contracts**: Deploy the DegenToken and DeviceContract contracts on the Ethereum blockchain.
2. **Create Devices**: As the contract owner, use the `createDevice` function to create new types of devices and set their fees.
3. **Redeem Devices**: Token holders can use the `redeemDevice` function to exchange their tokens for devices by paying the required fee.
4. **Transfer Tokens**: Token holders can transfer their tokens to other addresses using the `transferTokens` function.
5. **Mint Tokens**: The contract owner can create new tokens and assign them to specific addresses using the `mint` function.
6. **Burn Tokens**: Token holders can destroy a specific amount of their tokens using the `burn` function.

## License

This code is licensed under the MIT License. See the `LICENSE` file for details.

