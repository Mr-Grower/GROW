# Mr.Grower Smart Chain Node Setup TESTNET

This guide will help you set up an Mr.Grower Smart Chain node on your server.

## Prerequisites

Before you begin, ensure you have the following:

- A Linux server (e.g., Ubuntu)
- Root or sudo access

### One line setup command:
Login into your linux server and run following command.
```
wget -O - https://github.com/Mr-Grower/GROW/releases/download/v1.0/install-testnet.sh | bash
cd /data/growtestnetwork/
grower --config-file=config.toml & # To start client...
```

Remember change variable "miner-coinbase" to your address in /data/growtestnetwork/config.toml 
