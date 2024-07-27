# Wallet Manager

## Installation
- Clone the git modules
```bash
git clone https://github.com/binqbit/wallet_manager-backend
git clone https://github.com/binqbit/wallet_manager-smart_contract
```

- Deploy the smart contract, follow the instructions in the [smart contract repository](https://github.com/binqbit/wallet_manager-smart_contract)
- Copy the contract address to [.env file](.env) to the `DISPERSE_COLLECT_CONTRACT_ADDRESS` variable
- Set RPC_PROVIDER_URL to [.env file](.env)

- Run docker containers
```bash
docker compose up -d --build
```

## Testing
- Open [postman collection](./config/postman_collection.json) and import it to postman
