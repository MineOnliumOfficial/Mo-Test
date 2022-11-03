# MO TEST

Deploy the MineOnlium testnet.

## Local Network

* `git clone https://github.com/MineOnliumOfficial/Mo-Test.git && cd Mo-Test/`
* replace my address with yours in the `.env` file and in the `Mo-Test/genesis/genesis.json` file.
* `docker compose up` 
* Create a new Metamask Network:
  Name: Mo-Test
  RPC URL: http://localhost:8545/
  Chain ID: 12345
  Symbol: MO
  Block Explorer: http://localhost:4001
* ...profit?

## Connecting to Public Testnet
* Coming Soon!

# Services Rendered:
* BlockExplorer: http://localhost:4000
* BlockExplorer API: http://localhost:8081
* Stratum Mining Server: http://localhost:50001
