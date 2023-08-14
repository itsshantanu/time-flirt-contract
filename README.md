# Time Flirt Capsule

Time Flirt Capsule is a web3 application that allows users to create unique and interactive capsules containing content like videos, notes, memories, and texts. Built with Next.js and deployed on various platforms including Base, Mumbai, Zora, and Mode, the application leverages IPFS for decentralized storage.

## Features

- **Select Chain**: Choose between different chains including Optimism Goerli, Zora Goerli, Polygon Mumbai, and Mode Sepolia.
- **Create Capsules**: Customize your capsule by adding a name, description, recipient address, type, expiration time, and file.
- **Web3 Integration**: Seamlessly interact with blockchain technologies.

## Chain Details

### Optimism Goerli
Deployed on Optimism Goerli for fast layer-2 scalability.

### Zora Goerli
Utilized Zora Goerli for innovative and creative use-cases.

### Polygon Mumbai
Leveraged Polygon Mumbai for efficient and effective transaction processing.

### Mode Sepolia
Integrated with Mode Sepolia for wacky and viral applications, enabling unique experiences that can help onboard users to web3.

## NPM Packages

- [Openzeppelin](https://www.npmjs.com/package/@openzeppelin/contracts)
- [Hardhat-Ethers](https://www.npmjs.com/package/hardhat-ethers)
- [Chai](https://www.npmjs.com/package/chai)
- [Ethers](https://www.npmjs.com/package/ethers)
- [Dotenv](https://www.npmjs.com/package/dotenv)
- [Hardhat-Etherscan](https://www.npmjs.com/package/hardhat-etherscan)

## Tech Stack

- [Node](https://nodejs.org/en/)
- [Hardhat](https://hardhat.org/)
- [Solidity](https://docs.soliditylang.org/)
- [Openzeppelin](https://openzeppelin.com/)

## Run Locally

Clone the project

```bash
  git clone git@github.com:itsshantanu/time-flirt-contract.git
```

Go to the project directory

```bash
  cd time-flirt-contract
```

Install dependencies

```bash
  npm install
```

Compile

```bash
  npx hardhat compile
```

Test

```bash
  npx hardhat test
```

Deploy on any network

```bash
  node scripts/deploy.js --network network_name
```

Verify Contract

You can verify your contract on the desired network using the npx hardhat verify command. Replace <YOUR_CONTRACT_ADDRESS> with the address of the contract you want to verify. If your contract requires constructor arguments, replace <WITH_ARGUMENT_IF_REQUIRED> with those arguments. Note that providing constructor arguments is optional and only necessary if your contract requires them.

For the any network:

```bash
npx hardhat verify --network network_name <YOUR_CONTRACT_ADDRESS> <WITH_ARGUMENT_IF_REQUIRED>
```

Help

```bash
  npx hardhat help
```

## Deploy Contract

- [Optimism Goerli](https://goerli-optimism.etherscan.io/address/0x32ef3be4bb15492ca859e5b1776e55671ed81a79)
- [Zora Testnet](https://testnet.explorer.zora.energy/address/0x662c66962B02Ebd79Fdc204e21065b268A15e920)
- [Polygon Mumbai](https://mumbai.polygonscan.com/address/0xc84eac7f76b17a78ef6bdb915b5d8bfb5c9f10d2)
- [Mode Sepolia](https://sepolia.explorer.mode.network/address/0x9c774Ba3c07D9526c0a658D1e6FE001D0E9fF1B7)

## Support

If you have any questions or run into any trouble, please feel free to open an issue in the repository. We'll do our best to help you out.

Happy Time-Flirting!

---

**Disclaimer:** Please note that this project is for educational purposes and should not be used for any illegal activities. We are not responsible for any losses incurred through the misuse of this code.