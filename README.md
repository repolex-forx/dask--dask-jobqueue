# Repolex Knowledge Graph of dask/dask-jobqueue

RDF knowledge graph data for [dask/dask-jobqueue](https://github.com/dask/dask-jobqueue), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download dask/dask-jobqueue
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 55b972741f2cb0a8a9702637d335f89e5345c7af
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 55b972741f2cb0a8a9702637d335f89e5345c7af
│           └── chunk-001.nq.gz
├── blob
│   ├── 037544eb2a140bcef30348c577430bede4b09f91.nq.gz
│   ├── 04267c36769829ec577d5447dc3ef058112d1944.nq.gz
│   ├── 06dfdbc3de4ca6b870e2dbd72f4c22730fedba93.nq.gz
│   ├── 0c62aaa9628bfa2bd39f6b3fb5e702f34e6cf90f.nq.gz
│   ├── 0d6fa9f7c97343d1b2ef2e27defda771c9b3a694.nq.gz
│   ├── 0da13de3732f6aeffc4d9328b77b523e3bba9812.nq.gz
│   ├── 1040f3c609f28145e7969c29597542bb75a62acc.nq.gz
│   ├── 1247a592381002d9c2583ad60aef409b7ec91fae.nq.gz
│   ├── 143a97fa36b3d5f1a9d47bc47eaba9142a68bde8.nq.gz
│   ├── 16b37fef621c873833b81cc74449ff57197687ae.nq.gz
│   ├── 18487d663faf83a5d2d7a061c1bad9445bbecba7.nq.gz
│   ├── 1af3bdf8326e9e7401efb7d1d420757f11bfd06e.nq.gz
│   ├── 1ea7852353f8bc6ed40f60a187be0f162776add4.nq.gz
│   ├── 1f6f427c4d18461eed94d00aa738d812ea66cde3.nq.gz
│   ├── 2157a8d0daefed61a01f03d8a2abf09370049276.nq.gz
│   ├── 22e69e55799b27511fb1658fb51043f4ce7500d5.nq.gz
│   ├── 2652294cd04a2b2a3596cfd4d870531954cfd957.nq.gz
│   ├── 2781a5faadb45fab6a5975b549a1bdf8c0178d05.nq.gz
│   ├── 2d933db90333b3e9f7b6dfd8ffcafab59c32e623.nq.gz
│   ├── 2e5eaa250353548397f77ef2168ecf09e983c43f.nq.gz
│   ├── 2efaf0d709338f32e0f8f4fdb36fb2809cbd50c7.nq.gz
│   ├── 3265a7360da0f065303481aef0f9d981343b5b33.nq.gz
│   ├── 32c236922fa1b6cdf89ccf4ce91a158f9968feb1.nq.gz
│   ├── 330ea1523f38b47b8a2a88fd48e49f33b6a42b9e.nq.gz
│   ├── 358aafba53c7f288025821c90a46c37152d36dce.nq.gz
│   ├── 3660caeebe34db80510b263727c77ed3cb080cd0.nq.gz
│   ├── 3a745c4840ae39bdaae1f65d1fc73ddec074ed2d.nq.gz
│   ├── 4257712cf46c8f2f3707524dba544f592ad74651.nq.gz
│   ├── 447b0c08dde5c2c4f1f5abfc10896b757782a0e0.nq.gz
│   ├── 454469bace076fb3f3244d28c6635a8341be8494.nq.gz
│   ├── 46c112dd8b3b48296c4b7553ad44dc3216d40881.nq.gz
│   ├── 497ceeb5e33ab17fbb70cd623ffc9f6b1190f24b.nq.gz
│   ├── 4bd11a26fd2df73b91fd5c1f2bd4b3fde547596a.nq.gz
│   ├── 4fcf4d082ff075cd15f6aa6969eec8b0cf7bfb95.nq.gz
│   ├── 4febda46efc69e2656e63a09d1569369549f1802.nq.gz
│   ├── 51c604c6e5ca1663c9a6014759d4e51781353ad8.nq.gz
│   ├── 550c7ae9ab6f5de6d73c455b8f3294af2bfa1e7f.nq.gz
│   ├── 5606264dcf140003dd94240d002c517ef94ee2ee.nq.gz
│   ├── 5718eba3cb96d057d7ad71ca3b2b41f40e6f5298.nq.gz
│   ├── 58d9d873909bef0a39b0cc69885788cca244d69c.nq.gz
│   ├── 5ab242218a27000e81ee155bd45eb0c261c1c5f9.nq.gz
│   ├── 5aee646d9ff02fd7d1e41f4fb9be5c54b5707462.nq.gz
│   ├── 5f8c743577aeddeedd12ce726f035f3ab9aad209.nq.gz
│   ├── 601dad6a0b24e31afd7eba63ae808f6c1f78abf0.nq.gz
│   ├── 61c162f71bde3ea34452c75cc5203c5e4e1eb7c7.nq.gz
│   ├── 644ee6c4975191e69ca919cb48ed2ae36e99e622.nq.gz
│   ├── 64bb1b4d636874ffa2693f27ed2fb648de34ee4f.nq.gz
│   ├── 65d1c6a6aca03f0387fb6c17e196823c820449bd.nq.gz
│   ├── 688eeae5a39725a59231eea61fd13dd65fee0a90.nq.gz
│   ├── 68a7246863d1cc068a3b9933a8e74c10ede2d561.nq.gz
│   ├── 68e98c71b0a5502f72e48715e208d4563324e878.nq.gz
│   ├── 691a79374a16fd81080511733de472205db12616.nq.gz
│   ├── 69d7e1cfc28b1c039b9dfae47687cff7c59522f7.nq.gz
│   ├── 6b07623b0551eca45fc936d2bc27caaa4b15f029.nq.gz
│   ├── 6b74c2d83f98fcb3dcb949be2d84154ccc46a0af.nq.gz
│   ├── 70d6ee22ccad698a8c82025481cdf7eeb963099b.nq.gz
│   ├── 719fd9ce42d2bac9fe4f29682c0080ba00e5dd0a.nq.gz
│   ├── 7b8032d12ddeeb4ad28750e83c02a47aba753069.nq.gz
│   ├── 814fcde2f880ea51dfb67bec25bbe3209620f022.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8e0d0a81b1e0593d618b577f2b94ced5ea70449d.nq.gz
│   ├── 91ee22bdb17fc304740c19ad1853560a50589d30.nq.gz
│   ├── 98f3e2e9cde8f19ff1ef8aa5229e716596991039.nq.gz
│   ├── 9ab2636871ed61eea42c1607c10fe31ced1cea1b.nq.gz
│   ├── 9c23d8d05bab7f6ae52d2d394f231b9459b876f8.nq.gz
│   ├── a486b6546533affdb8b9ff11c5a5c06654a347db.nq.gz
│   ├── a4ad4365e63553bbdc8ad372cb431242caec2394.nq.gz
│   ├── a6e860399911954c250ada03d554c9ea1d039638.nq.gz
│   ├── a6f692c9f28a3749961d6388cc467fdbfc1f9ebd.nq.gz
│   ├── a877f62af770e1a3fe50589dfbf3f2a52a44197d.nq.gz
│   ├── a918706f35166c18dcababca79d34ee30b55dfb8.nq.gz
│   ├── aa433187c72de1499cde416afb940f82d2e274aa.nq.gz
│   ├── ac06352af5b2c17182d143300537b6e6f3359b5f.nq.gz
│   ├── ae14ae33d430ada7b3881093906bc07f8dba40b7.nq.gz
│   ├── b250c3ee8307d9624644f1300ae954357d6dfbe9.nq.gz
│   ├── b26ffa23ece33f58a764cb02176f2bb9195c2016.nq.gz
│   ├── b42556f01710c4df8388a33657546ebc78c5a83c.nq.gz
│   ├── b5872b00727235b4f4c379fb164519ccc249108b.nq.gz
│   ├── b6661ffa710a5c888d551b22d865ee2cde8021cc.nq.gz
│   ├── bb588dafe7de71100de0e327f9247e6e6c842c62.nq.gz
│   ├── be71087872e512c49a5a0bb92fe20ad582cdb542.nq.gz
│   ├── becccd5c934185dae3857b01d7596b295db8de1e.nq.gz
│   ├── c666d02e0c0e850d220e3e0a3066c14aa6e36da5.nq.gz
│   ├── c684ea6e8ae756b1af1d1bd8b2c472ab587eb12d.nq.gz
│   ├── c9849d6326c4da87b322b2fd74d28106e08a9ea6.nq.gz
│   ├── cb177d21ddc0026209e0afc78de98197705d8b68.nq.gz
│   ├── cbb88dcac0f46dad072d4cdb862e6454865ce56b.nq.gz
│   ├── cd9ff12e7877aef467b30af4594c975b51180932.nq.gz
│   ├── ceadd12685e8ece19b75cde8ace729d42ce7418e.nq.gz
│   ├── d0302dbc80c9e529413882610ae7592bb5dcc435.nq.gz
│   ├── d06fcb8d2f490d49fe2006fa420ec19857512642.nq.gz
│   ├── d48c6203df009bb985fab454f048e3d3e3fb2534.nq.gz
│   ├── d84afbf75239fb468ec27a0998a977d4b38d9a2f.nq.gz
│   ├── dc01b468289bd50ecfdf8d5572c4b1518b7d57da.nq.gz
│   ├── de97d9042ce12adc2594b401834611427d3fb1aa.nq.gz
│   ├── dec19a80c6875cb1e31fd1b06218471887b7f610.nq.gz
│   ├── e497eaa5d191d7943a8e4c5b37772bc5cbba53b2.nq.gz
│   ├── e6841073123b7c4c4f3258bac6328dd6e94b3d3d.nq.gz
│   ├── e7a008841bb623f8d57eff6deef1240294b0a664.nq.gz
│   ├── ed9d83f74b4c8716296cc523b75f72b97c49b0d7.nq.gz
│   ├── ee150465c8fc3ab9a0ebc869766a6f79560ef724.nq.gz
│   ├── f69c6259b17a46c443e65996a1a522b0fc317f70.nq.gz
│   ├── fb8e1b444e315b58d21b497139ceebe2293b885b.nq.gz
│   └── fe1557d37b889573dbae70a7be576ab11af10a86.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 55b972741f2cb0a8a9702637d335f89e5345c7af.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 112 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[dask/dask-jobqueue](https://github.com/dask/dask-jobqueue)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
