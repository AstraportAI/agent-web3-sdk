# agent-web3-sdk

TypeScript SDK for interacting with Agent-Web3.

## Purpose

Allow developers and agents to interact with Agent-Web3 using a simple API.

## Example

```ts
const agent = new AgentWeb3({ apiUrl })

await agent.transfer({
  to: "0xabc",
  amount: "0.5",
  asset: "ETH",
  chain: "sepolia"
})
```

## Role in Agent-Web3

Primary developer interface.
