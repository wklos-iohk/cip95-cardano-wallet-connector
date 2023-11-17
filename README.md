# CIP-95 Cardano DApp Wallet Connector

Currently corresponding CIP-95 commit: [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md).

| Tag | CIP-95 Commit | Feature Details | demos Wallet Tag | Deployed Currently? |
| --- | ------------- | --------------- |----------------- | ------------------- |
| [1.6.0](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.6.0) | [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md) | [Here](./CHANGELOG.md#160) | [1.6.0+](https://github.com/Ryun1/cip95-demos-wallet/tags) | No |
| [1.6.1](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.6.1) | [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md) | [Here](./CHANGELOG.md#161) | [1.6.0+](https://github.com/Ryun1/cip95-demos-wallet/tags) | No |
| [1.6.2](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.6.2) | [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md) | [Here](./CHANGELOG.md#162) | [1.6.0+](https://github.com/Ryun1/cip95-demos-wallet/tags) | No |
| [1.6.3](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.6.3) | [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md) | [Here](./CHANGELOG.md#163) | [1.6.0+](https://github.com/Ryun1/cip95-demos-wallet/tags) | [Yes](https://ryun1.github.io/cip95-cardano-wallet-connector/) |

## CIP-95/Conway Features Supported Notes

See [CHANGELOG.md](./CHANGELOG.md) for feature details on older tags.

### 1.6.3
- Fixed combination certs
- Added CC certs
  
### 1.6.4 (In progress)
- Treasury donations
- Treasury values
- MIR transfer / genesis keys certs
- signData

## To Develop

### Start Dev Env

1. Install modules

```bash
sudo npm install
```

2. Try to start

```bash
sudo npm start
```

This should launch a local dev environment at [http://localhost:3000](http://localhost:3000).

### To Deploy

1. Change the `"homepage" ` field in [package.json](./package.json) to your repo.
   
2. Deploy to github pages
   
```bash
sudo npm run deploy
```

## Live Demo

A demo showcasing all functionalities of the wallet connector:

https://ryun1.github.io/cip95-cardano-wallet-connector/