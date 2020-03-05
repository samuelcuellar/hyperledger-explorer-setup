# hyperledger-explorer-setup

Dependencies

- Hyperledger Fabric Samples
- Docker Compose


## Getting Started

Clone repository:
```
git clone https://github.com/samuelcuellar/hyperledger-explorer-setup.git
```

Change in docker-compose-explorer.yml the path for the crypto-config if it is required


Start docker containers:
```
docker-compose -f docker-compose-explorer.yaml up
```

References:
- https://github.com/hyperledger/blockchain-explorer
