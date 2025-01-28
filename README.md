# InkySwap Mainnet Token List

This repository contains the official token list for the InkySwap Mainnet. The token list is used by the InkySwap platform to display and interact with various tokens on the network.

## Token List

The token list is defined in the `inkyswap-mainnet.tokenlist.json` file. It includes details such as the token's name, symbol, address, chain ID, decimals, and logo URI.

### Example Token Entry

```json
{
  "chainId": 57073,
  "address": "0x4200000000000000000000000000000000000006",
  "symbol": "WETH",
  "name": "Wrapped ETH",
  "decimals": 18,
  "logoURI": "https://storage.inkypump.com/storage/v1/object/public/images/c253d7c5d4203783e31bde1d33e143f6a9ce1defac24ab5e06948847696b80a1.png"
}
```

## Adding Your Token

To add your token to the InkySwap Mainnet Token List, please follow these steps:

1. **Fork the Repository**: Create a fork of this repository to your GitHub account.

2. **Edit the Token List**: Add your token details to the `inkyswap-mainnet.tokenlist.json` file. Ensure that your entry includes the following fields:
   - `chainId`: The chain ID where your token is deployed (e.g., 57073 for Ink Mainnet).
   - `address`: The contract address of your token.
   - `symbol`: The symbol of your token (e.g., "WETH").
   - `name`: The full name of your token (e.g., "Wrapped ETH").
   - `decimals`: The number of decimals your token uses. (eg., default is 18)
   - `logoURI`: A URL to your token's logo image.

3. **Submit a Pull Request**: Once you've added your token, submit a pull request to this repository. Please ensure your pull request includes:
   - A clear description of your token.
   - Verification that the token address and details are correct.

4. **Review and Merge**: The maintainers will review your pull request. If everything is in order, your token will be added to the list. Please allow up to 12 hours for your token to be added to the list, don't ping the maintainers to merge your PR.

## Contact

For any questions or issues, please open an issue in this repository or contact [@EmperorOfTheInk](https://t.me/emperoroftheink) on TG.
