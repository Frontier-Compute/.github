## Zcash agent custody infrastructure

Open-source protocol and tooling for structured on-chain commitments via Zcash shielded memos.  MIT licensed.

### ShieldedVault

Agent custody defined by 5 properties:  non-drainable, policy-bound, attested, remembering, killable.

- [`shieldedvault-spec`](https://github.com/Frontier-Compute/shieldedvault-spec) - Agent custody specification.  CC-BY-4.0.
- [`create-shieldedvault`](https://github.com/Frontier-Compute/create-shieldedvault) - Scaffold a 5-property agent.  `npx create-shieldedvault my-agent`.

### Protocol

- [`zap1`](https://github.com/Frontier-Compute/zap1) - ZAP1 attestation protocol.  BLAKE2b Merkle commitments, Orchard shielded anchoring, FROST 2-of-3 threshold signing.  [ZIP draft #1243](https://github.com/zcash/zips/pull/1243).

### Agent tooling

- [`zcash-mcp`](https://github.com/Frontier-Compute/zcash-mcp) - 22 MCP tools for Zcash.  [npm](https://www.npmjs.com/package/@frontiercompute/zcash-mcp).
- [`openclaw-zap1`](https://github.com/Frontier-Compute/openclaw-zap1) - ZAP1 attestation plugin.  14 tools + 8 hooks.
- [`zcash-402`](https://github.com/Frontier-Compute/zcash-402) - HTTP 402 shielded payments for AI agents.
- [`zcash-ika`](https://github.com/Frontier-Compute/zcash-ika) - Split-key custody via Ika 2PC-MPC.

### Verification

- [`zap1-verify`](https://github.com/Frontier-Compute/zap1-verify) - Merkle proof verification.  Rust + WASM.  [crates.io](https://crates.io/crates/zap1-verify).
- [`zap1-js`](https://github.com/Frontier-Compute/zap1-js) - JS/TS verification SDK.  [npm](https://www.npmjs.com/package/@frontiercompute/zap1).
- [`zcash-memo-decode`](https://github.com/Frontier-Compute/zcash-memo-decode) - Universal memo decoder.  [crates.io](https://crates.io/crates/zcash-memo-decode).

### Live

- [Simulator](https://simulator.frontiercompute.io) - Interactive 9-step lifecycle demo
- [Verifier](https://verify.frontiercompute.cash) - WASM proof verification in-browser
- [Explorer](https://explorer.frontiercompute.io) - Attestation browser

### Mainnet

1 anchor.  12 leaves.  9 event types.  6 mainnet chains.  Stats:  https://api.frontiercompute.cash/stats
