Ethereum seed balance checker using DeBank API (multinetwork, multithread)
![alt text](https://github.com/gaugaudu45/debank-seed-checker/blob/main/Untitled.png?raw=true)

### About
Multithread seed checker for Ethereum seeds. Software generates addresses for each seed and check them for tokens and balances througth DeBank API. Currently works with Ethereum, Binance, Avax, Matic, Fantom, Optimism, Cronos, Arbitrum networks. Software doesnt check NFTs and DeFi services.

### Setup
Addresses count for each seed - number of addresses which be generated from each seed. Set to 1-10 for stable work.
Number of threads - Set to 1-10 for stable work.
List of seeds - list of seeds to check. Works with 12 and 24 word seeds.

### Compilation
There is compilation error with NBitcoin lib. Use x86 compilation for stable work.

### Todo
These things will be added later:
1. Formatted output.
2. Proxy support.
3. Work with private keys.
4. Check for NFTs.

