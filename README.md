# Commands to install [StarkNet node](https://github.com/TheHolyCryptoGuardian/StarkNet/edit/main/Node)

Use `wget -O starknet.sh https://raw.githubusercontent.com/TheHolyCryptoGuardian/StarkNet/main/Node.sh && chmod +x starknet.sh && ./starknet.sh` to install the node quickly.

Use `systemctl restart starknetd` to restart the node.

Use `systemctl stop starknetd` to stop the node.

Use `journalctl -u starknetd -f` to check node logs.

Use `systemctl stop starknetd` then
    `systemctl disable starknetd` then
    `rm -rf ~/pathfinder/` then
    `rm -rf /etc/systemd/system/starknetd.service` and then
    `rm -rf /usr/local/bin/pathfinder` to delete the node.

# StarkNet
StarkNet is a permissionless decentralized ZK-Rollup operating as an L2 network over Ethereum, where any dApp can achieve unlimited scale for its computation, without compromising Ethereum’s composability and security.

Cairo is a programming language for writing provable programs, where one party can prove to another that a certain computation was executed correctly. Cairo and similar proof systems can be used to provide scalability to blockchains.

StarkNet uses the Cairo programming language both for its infrastructure and for writing StarkNet contracts.

Here we provide three tutorials:

[Hello, StarkNet](https://starknet.io/docs/hello_starknet/index.html#hello-starknet)

[Hello, Cairo](https://starknet.io/docs/hello_cairo/index.html#hello-cairo)

[How Cairo Works](https://starknet.io/docs/how_cairo_works/index.html#how-cairo-works)

“Hello, Starknet” is a guide on how to write StarkNet contracts, and demonstrates the system’s basic features.

“Hello, Cairo” describes Cairo for the programmer who wishes to understand what Cairo can do hands-on, and start writing programs in Cairo. “How Cairo Works” starts from the low-level assembly-like version of Cairo and explains the syntactic sugar mechanisms applied by the Cairo compiler, which turns Cairo to a high-level-like language.

The “Hello, Cairo” tutorial contains several references to “How Cairo Works” for those who want to get a better understanding of those topics.

Where should I start? If you want to promptly dive into writing StarkNet contracts, start with “Hello, StarkNet” and jump to “Hello, Cairo” whenever you need additional clarifications. If you want to write Cairo programs, independent of StarkNet, start with “Hello, Cairo”. Finally, if you want to understand Cairo’s internals from the ground up, start with “How Cairo Works” and then follow with “Hello, Cairo”.
