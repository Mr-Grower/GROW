# Mr.Grower Smart Chain Node Setup TESTNET

This guide will help you set up an Mr.Grower Smart Chain node on your server.

## Prerequisites

Before you begin, ensure you have the following:

- A Linux server (e.g., Ubuntu)
- Root or sudo access

### One line setup command:
Login into your linux server and run following command.
```
wget -O - https://github.com/Mr-Grower/GROW/releases/download/v1.0/install_client.sh | bash
cd /data/grownetwork/data
sudo nano key
0xXXXXXXXXXXXX  # store your private key that corresponds to the address you left in the allowlist and save file
cd ..
export JAVA_HOME=/usr/lib/jvm/jdk-21
grower --config-file=config.toml & # To start client...
```
