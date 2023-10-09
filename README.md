# CIP-95 Cardano DApp Wallet Connector

Currently corresponding CIP-95 commit: [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md).

| Tag | CIP-95 Commit | Feature Details | demos Wallet Tag | Deployed Currently? |
| --- | ------------- | --------------- |----------------- | ------------------- |
| [1.4.0](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.4.0) | [1f75f99](https://github.com/Ryun1/CIPs/blob/1f75f990c4e8fdf308c3ed209bac723a84822931/CIP-0095/README.md) | [Here](./CHANGELOG.md#140) | [1.4.0](https://github.com/Ryun1/cip95-demos-wallet/releases/tag/1.4.0) | **No** |
| [1.5.0](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.5.0) | [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md) | [Here](./CHANGELOG.md#150) | [1.5.x](https://github.com/Ryun1/cip95-demos-wallet/tags) | No |
| [1.5.1](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.5.1) | [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md) | [Here](./CHANGELOG.md#151) | [1.5.x](https://github.com/Ryun1/cip95-demos-wallet/tags) | No |
| [1.5.2](https://github.com/Ryun1/cip95-cardano-wallet-connector/releases/tag/1.5.2) | [6153866](https://github.com/cardano-foundation/CIPs/blob/6153866bbafe874e196431f736d6bf6691359988/CIP-0095/README.md) | [Here](./CHANGELOG.md#152) | [1.5.x](https://github.com/Ryun1/cip95-demos-wallet/tags) | [Yes](https://ryun1.github.io/cip95-cardano-wallet-connector/) |

## CIP-95/Conway Features Supported Notes

See [CHANGELOG.md](./CHANGELOG.md) for feature details on older tags.

### 1.5.4
- CSL Alpha v8
- Fixed New Const Gov Act

### 1.5.5 (In progress)
- signData
- Other gov action submission

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