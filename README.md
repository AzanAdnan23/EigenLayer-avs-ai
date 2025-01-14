## EigenLayer AVS AI using Llama Guard

### Video Guide:

```
https://youtu.be/XjraoZtpuKk?si=r5Yz92BreLzbBG8K
```

### Steps

- Users can submit text content on-chain.
- Off-chain operators run this content through an AI model (Llama Guard) to check if it's safe.
- Operators then submit their results back on-chain.

### Commands:

```
anvil --chain-id 31337 --fork-url https://eth-mainnet.g.alchemy.com/v2/your-api-key
```

```
forge script script/DeployMyServiceManager.sol --rpc-url http://localhost:8545 --broadcast
```
