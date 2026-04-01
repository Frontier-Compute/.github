## Zcash attestation infrastructure

Open-source protocol and tooling for structured on-chain commitments via Zcash shielded memos. MIT licensed.

### Protocol

- [`zap1`](https://github.com/Frontier-Compute/zap1) - ZAP1 attestation protocol. BLAKE2b Merkle commitments, Orchard shielded anchoring, 9 binaries, 102 tests, 57 automated checks. [ZIP draft PR #1243](https://github.com/zcash/zips/pull/1243).

### Verification

- [`zap1-verify`](https://github.com/Frontier-Compute/zap1-verify) - Merkle proof verification. Rust + WASM. [crates.io](https://crates.io/crates/zap1-verify).
- [`zap1-js`](https://github.com/Frontier-Compute/zap1-js) - JS/TS verification SDK. [npm](https://www.npmjs.com/package/@frontiercompute/zap1).

### Ecosystem tooling

- [`zcash-memo-decode`](https://github.com/Frontier-Compute/zcash-memo-decode) - Universal Zcash shielded memo decoder. Text, ZIP 302 TVLV, ZAP1, binary, empty. Zero deps. [crates.io](https://crates.io/crates/zcash-memo-decode).

### Explorer and simulator

- [`zap1-explorer`](https://github.com/Frontier-Compute/zap1-explorer) - Attestation browser
- [`zap1-simulator`](https://github.com/Frontier-Compute/zap1-simulator) - Interactive lifecycle simulator

### Mainnet

4 anchors. 16 leaves. Protocol info: https://pay.frontiercompute.io/protocol/info
