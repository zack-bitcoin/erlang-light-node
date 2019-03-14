Amoveo erlang light node
==========

Amoveo is a blockchain meant for enforcement of investment and insurance contracts.
[You can learn about Amoveo here](https://github.com/zack-bitcoin/amoveo)

[consider using the javascript light node instead](https://github.com/zack-bitcoin/light-node-amoveo)

The erlang light node is meant to be hosted on a server. It stays in sync with the network the same way the full node does.
You can use this light node to verify proofs of any part of the consensus state. For example: checking the balance of an account.

Some advantages of using a light node over a full node:
* you can sync the node in seconds.
* less bandwidth requirements.
* For most hard updates, the erlang light node will not change. So you don't have to participate in almost any updates.



Development status:
It does sync headers, but only slowly.
once headers are synced, it can sync peers.