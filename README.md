# clone the sample project
```
git clone https://github.com/JamesShieh0510/uniswap-app
```

# install its dependencies:

```
cd uniswap-app
npm install
```

# forked from a snapshot of Mainnet

alchemy: https://www.alchemy.com

```
npx hardhat node --fork https://eth-mainnet.alchemyapi.io/v2/{YOUR_API_KEY}
```

# test the contract
```
npx hardhat test --network localhost
```

# hardhat local network

RPC url:
http://127.0.0.1:8545/
Chain ID:
31337
