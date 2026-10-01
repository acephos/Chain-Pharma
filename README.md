# Chain-Pharma: historical pharmaceutical supply-chain coursework

A Solidity/Truffle learning snapshot based on [kamalkishorm/Blockchain_SupplyChain](https://github.com/kamalkishorm/Blockchain_SupplyChain). Upstream workflow/design and team material are retained in [README.upstream.md](README.upstream.md). This snapshot is not a smart-contract audit, deployed traceability service, or independently original implementation of all upstream functionality. The available history does not establish individual team contribution shares.

`Chain-Pharma` is the canonical historical contract reference; `ChainPharma` is a related snapshot, and `ChainPharmaUI` is its Angular frontend. These repositories are retired together so duplicate snapshots do not become separate maintained products.

The contracts use Solidity 0.5-era APIs and the wallet-provider dependency is obsolete. Remote network configuration and embedded wallet/provider literals have been removed from the maintained tree. The remaining Truffle configuration targets only a disposable local RPC at 127.0.0.1:8545. Do not use these contracts with real funds or production data. Earlier Git history may retain removed deployment material.

No modern deployment or contract-test coverage is claimed. A revival would require a deliberate contract/toolchain migration, role and state-transition tests, and environment-managed deployment configuration before use. Historical setup instructions in the upstream README describe the old environment, including retired networks.

Existing author/license metadata is preserved rather than assigning new rights to team/upstream code. Verify upstream and asset permissions before redistribution or reuse. Source remains available as coursework history.
