# Hardhat DeFi 

*This repo has been revamped to work with Goerli. Due to AaveV2 not being deployed on Goerli, it may not work as intended. Please use a mainnet-fork or local network instead of a testnet.*


## Quickstart

```
git clone https://github.com/abed-1987/hardhat-defi.git
cd hardhat-defi-main
yarn
```

## Typescript

For the typescript edition, run:

```
git checkout typescript
```



Run:

```
yarn hardhat run scripts/aaveBorrow.js
```



# Running on a testnet or mainnet

1. Setup environment variabltes

You'll want to set your `GOERLI_RPC_URL` and `PRIVATE_KEY` as environment variables. You can add them to a `.env` file, similar to what you see in `.env.example`.

2. Run

```
yarn hardhat run scripts/aaveBorrow.js --network goerli
```


# Linting

To check linting / code formatting:
```
yarn lint
```
or, to fix: 
```
yarn lint:fix
```

## Formatting

```
yarn format
```
