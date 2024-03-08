# 🏗 Scaffold-ETH 2

## Smart Wallet Scaffold ETH

This codebase is as an integration on top of [Scaffold-ETH 2](https://scaffoldeth.io/). I learned about Smart Wallets at Base House ETH Denveer, and got really excited to set this up and share with everyone!

## About Smart Wallet

- Provides capability to create wallets using passkey ([ERC-4337](https://eips.ethereum.org/EIPS/eip-4337))
- Removes hassle of remembering seed phrases and private keys

## Wallet Demo

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/F82n7ePUo6M/1.jpg)](https://youtu.be/F82n7ePUo6M)

## Quickstart

Quickstart for Scaffold ETH Users:

1. Clone Scaffold ETH Repo
    ```
    git clone https://github.com/scaffold-eth/scaffold-eth-2.git
    cd scaffold-eth-2
    ```
2. Specify resolution to use the wallet SDK beta version in `package.json`
   ```
   {
    "resolutions": {
        "@coinbase/wallet-sdk": "npm:@coinbase/wallet-sdk@4.0.0-beta.0"
    }
   }
   ```

3. Install dependencies
   ```
   yarn install
   ``` 

4. Start NextJS App
   ```
   yarn start
   ```

5. Test it on your localhost!

## 📖 Documentation

For more documentation on Smart Wallets, check out the [docs](https://docs.cloud.coinbase.com/wallet-sdk/docs/sw-setup) from Base here.

Visit  [Scaffold-ETH 2 docs](https://docs.scaffoldeth.io) to learn how to start building with Scaffold-ETH 2.

To know more about its features, check out our [website](https://scaffoldeth.io).

## Contributing to Scaffold-ETH 2

We welcome contributions to Scaffold-ETH 2!

Please see [CONTRIBUTING.MD](https://github.com/scaffold-eth/scaffold-eth-2/blob/main/CONTRIBUTING.md) for more information and guidelines for contributing to Scaffold-ETH 2.
