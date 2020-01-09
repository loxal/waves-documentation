# Alias binary format

> Learn more about [alias](/blockchain/account/alias.md)

| Field order number | Field | Field type | Field size in bytes | Comments |
| :--- | :--- | :--- | :--- | :--- |
| 1 | Entity type | Byte | 1 | Value must be 2 |
| 2 | [Chain ID](/blockchain/blockchain-network/chain-id.md)| Byte | 1 | Value equals:<br> 84 — for [test network](/blockchain/blockchain-network/test-network.md)<br>87 — for [main network](/blockchain/blockchain-network/main-network.md)<br>83 — for [stage network](/blockchain/blockchain-network/stage-network.md) |
| 3 | Number of characters in the alias | Short | 2 | |
| 4 | Alias | Array of bytes	 | From 4 to 30 | | |
