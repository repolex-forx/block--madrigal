# Repolex Knowledge Graph of block/madrigal

RDF knowledge graph data for [block/madrigal](https://github.com/block/madrigal), parsed by [repolex](https://repolex.ai).

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
rlex download block/madrigal
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b3f511828462ac854d18dce011de638a45d6191d
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── b3f511828462ac854d18dce011de638a45d6191d.nq.gz
│   └── repolex
│       └── b3f511828462ac854d18dce011de638a45d6191d
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ff6894e62427a6d36d2d9c2d4f37fa7cf3b5af.nq.gz
│   ├── 02f79ccfaa51670eb449d139c48ed59761656b77.nq.gz
│   ├── 05435e9590c819ae56fa4aa8cdcf252533b500c0.nq.gz
│   ├── 05bb52d67235de4dee1b75d1f0c044c3e81dc7a5.nq.gz
│   ├── 077bd5c74ac6214e21c5cb90fe9af2aed02caec0.nq.gz
│   ├── 07cbe13b57331fa9c669ec7064dc89b99613a5aa.nq.gz
│   ├── 0ba9db25329d0b336e39ca8cde8470c5b7bc45eb.nq.gz
│   ├── 0ebf173c89a86c8a064501ccf5c4a474b96b7ad7.nq.gz
│   ├── 10304b571b20d34f655167a74d5f47227ca0701e.nq.gz
│   ├── 109c135d22efda05dfc4e2e5ac2e62102af86971.nq.gz
│   ├── 113072a4d232706b1870661abc7e48689f847e9a.nq.gz
│   ├── 1167de1bb8db96f380b3ed62145c123ddfd2ff93.nq.gz
│   ├── 12065492e19456c95513cd215aa4382116c0e1d0.nq.gz
│   ├── 16ff8d04a405034d0f3c4751d0766dc0eaa7db67.nq.gz
│   ├── 19d87e6e7de4e108f0ebcd6ea017ee4032bdc04b.nq.gz
│   ├── 1a06ca864dd549fc7405f6ebc20e27d1ecdb223e.nq.gz
│   ├── 1a4a71c652387c5475a349f261b32152e2a7fa95.nq.gz
│   ├── 1a771d80d79566c57b39608f5097e70ca57c8823.nq.gz
│   ├── 1aa215de413ddf0643fa91ded2514fb7f6aab680.nq.gz
│   ├── 1aab063afea78c07125e952b8d5803275c9e549a.nq.gz
│   ├── 1c311e2acd8330b35e5336d010dd8ef2a20ecbfd.nq.gz
│   ├── 1f6b3a2d3cf38ed4859848f9ad1e9ab6f0bca3e9.nq.gz
│   ├── 215ecd79402d15e75498cadaedc2c9e3180e0756.nq.gz
│   ├── 22231dedabf346b49c6879a810387dc8179b6284.nq.gz
│   ├── 25f0bc5ed80683a81f46e6bfd1cf8ea0b56c6807.nq.gz
│   ├── 29b4dd0012d3c829d241cc274534f8b3a85e3679.nq.gz
│   ├── 35ad0930a2dace7296ac0f45af7d9431c5d1348e.nq.gz
│   ├── 35f276aaf6bcba8bdefba68ff4d5f40732d9d559.nq.gz
│   ├── 38952326e6fa71af7cf99df4713d96f57d46f292.nq.gz
│   ├── 3c08ee3cf92c7b1a1342097da6fb3e09006b3d96.nq.gz
│   ├── 3e1acb32ebb6ba49b259732f22dcb3b9cb3ff8e2.nq.gz
│   ├── 42833ad1b263ba934e7be216f5969b1f4a3e642c.nq.gz
│   ├── 4875fe1ae10c9a443dc44767e2caeb45dd69f050.nq.gz
│   ├── 490330116460d5135e78333d325848e51a8503b8.nq.gz
│   ├── 4be8547dc067b3ff5813e4a0dba891047a5d6f90.nq.gz
│   ├── 4f3d133ed38f4f18b4b462ce114e7e62e068e038.nq.gz
│   ├── 4f4de5047f7c8405c4d435b0e90259b572136a41.nq.gz
│   ├── 4fa60373589a61e96578b4fdde73d5a3ded20082.nq.gz
│   ├── 5040a581ebe9b4a41b0e5af4c95f672219753b4f.nq.gz
│   ├── 5163e1f2a83d90fc97c7c8315728f61953803ae2.nq.gz
│   ├── 51869b535509eccf81b78f9fecb1fca3d1b441ad.nq.gz
│   ├── 518b29e0fe67769d787b8c9957c2ac46675661e8.nq.gz
│   ├── 539b556ca620415b63ae03e4ce753919489d13d3.nq.gz
│   ├── 5442f56ac77ed7095d5a02010f0b09cd68f95fb1.nq.gz
│   ├── 564c30c1648144350e20a0befe36ea1227513781.nq.gz
│   ├── 5668553c073b622efa0ebbe9f0bf9af026999057.nq.gz
│   ├── 57098ec0752ca5a33a3617fb60d75925d15e4d91.nq.gz
│   ├── 588c4677b627d7db82304f4652c6bcd47df0c78c.nq.gz
│   ├── 5a1cf728930b7bd17e47a2176cf2daeb59c89d52.nq.gz
│   ├── 5ac47d2d16555af2922d59cf7ddedaba8963d7cc.nq.gz
│   ├── 5b607edefc48ab2652ef0c64e7cd3f348be3a9d5.nq.gz
│   ├── 5b8c6d16cd4e26f50bd8ff42c67db278b3c9dd65.nq.gz
│   ├── 5d7cce7b2688d2fda6094e2ad1ff81293af98924.nq.gz
│   ├── 5e64820c416f738869ec1f920277f2e969f6c7e2.nq.gz
│   ├── 5e7d6cc974dae159c8288ba928047aad8851b66a.nq.gz
│   ├── 60ceee76224ec01f07862aacdc475f6199e65439.nq.gz
│   ├── 672d600acd9c8acd83923827b4e2f6234743fad4.nq.gz
│   ├── 673f60a07f5134c4da9c4ac8ebdcc8a1c8802675.nq.gz
│   ├── 6bccf43368fd7c96d9c659562a5142b8b8cb98a1.nq.gz
│   ├── 6ef7b0d5381a6c39c26c60b5c20e5f4cf5285540.nq.gz
│   ├── 705f0f0d05911f8df3baad969c7589de1254da85.nq.gz
│   ├── 70dfdf78ae94633066551ed4edec633ee5a60c81.nq.gz
│   ├── 7296d3e6cdd7e8d3c7c94d553a1f11f2cab83f5a.nq.gz
│   ├── 7731bc1e222b0cdc00601412a0d4a6364321d34a.nq.gz
│   ├── 78e6ebd06a79f92417830e97ec5072766e87c9bb.nq.gz
│   ├── 79c2d61ca71e25c77fe0ad5cc3f3e9a00cb4b517.nq.gz
│   ├── 7cb25c2c6ee8737652b88d29fa528201825ddc50.nq.gz
│   ├── 7cc3a3608f5d437a6a97e393d137a67d4390d3c5.nq.gz
│   ├── 7d503dada533ec2cc943a49d9b7a913bdd95cccc.nq.gz
│   ├── 7d88839d8c2ce0a9f1961596eab54e3b66c93dbb.nq.gz
│   ├── 7ec43a946681a56fc18d19c4b10b38f004abb261.nq.gz
│   ├── 7ed093626491be0dc79696c867cfd56d30abe87e.nq.gz
│   ├── 80dacf292bd16dc1f883f3ff562e7712ba23eece.nq.gz
│   ├── 814bf1526242317897de29a920de4500910e91b5.nq.gz
│   ├── 853e284b0326aa6d5db44eb8001bbb244e660485.nq.gz
│   ├── 85c82fdca7187dddca5e2b1d17bc1819cd6a1a39.nq.gz
│   ├── 862ee3c28647e7a58801a75236855c269c1448ae.nq.gz
│   ├── 8666648c67624bfc786ad8d903479847abcd2c63.nq.gz
│   ├── 897572a209f03901cb14ee3019a87f6cb72403e6.nq.gz
│   ├── 8edb46cc82dcc58e5087aa2873b1420880bfcf7f.nq.gz
│   ├── 9168947dc46793d673179d0df7169b057e4c1438.nq.gz
│   ├── 9174f7d658c175f1130c358abc43f2a8e8649894.nq.gz
│   ├── 92687b2992f4d3f180f3948addaa8e878cce6bc4.nq.gz
│   ├── 92b28cd262d43098c6da0471aa8b0f4ed0d750af.nq.gz
│   ├── 94bfa71569479a1c3a1738472a352bafcc0fac03.nq.gz
│   ├── 9582fc588754f78d9875691a3bd5e674295436b3.nq.gz
│   ├── 998dc35ce9aca961473449582c35654d370c18f9.nq.gz
│   ├── 9ca4d3ab6476f283a22322fa3bd15cb1cc9af334.nq.gz
│   ├── a03b4df065d3bd70c3e0d45565f1009e50a204e3.nq.gz
│   ├── a10c7559c6f681214935b1b28887786200e24952.nq.gz
│   ├── a1e9d25a35cc66ef750df1540f943ff6803d847a.nq.gz
│   ├── a5ef193506d07d0459fec4f187af08283094d7c8.nq.gz
│   ├── aacb49aade6e8017fd2249702778db97047ce6c3.nq.gz
│   ├── aaf3b0bb3a40b6e895d0aab2adad6290a8548660.nq.gz
│   ├── acac8497c9e116634fed86745cd24884d50c8df4.nq.gz
│   ├── ae79b22615ffc2638035dbf782e14f7a9670adff.nq.gz
│   ├── b10f724ffb2d97eadd524a84a8941bf34c21d116.nq.gz
│   ├── b29be4babd836b0e555e9f0754bc952cd4bd17fa.nq.gz
│   ├── b5e1b2153d170f578718f703a095559e405288ab.nq.gz
│   ├── b61bee68f4e4f3882b877f9eb6bcd4e62183bb1a.nq.gz
│   ├── b9625638c7c657dcfd22181ed59009b886ccf5d1.nq.gz
│   ├── bf3899088714dff9fbd958fd23e8130865029f92.nq.gz
│   ├── c4142d94576a656c14a87468be901950e78aff62.nq.gz
│   ├── c46d377cb797db92943f2fc55c8f79f50f1ccc63.nq.gz
│   ├── c59b3a1f3265df358f0b8f87d7b2c9a37a6e4844.nq.gz
│   ├── c79fa68df4172483c7f70db8078b3035490b1b0a.nq.gz
│   ├── c982a3a6f7e7645b86edbd903d134e559b8bd3b4.nq.gz
│   ├── cf0584ebe28078f9d8baa6bd285d652d2e33a0af.nq.gz
│   ├── d0dae237de79bdfa54a52ef5e5db811ff660518b.nq.gz
│   ├── d36efe16bc4ea7989720b4a54d739aa5cbd15dc8.nq.gz
│   ├── d584ccd8ecafa1ff1619de2fcb5a99367d652253.nq.gz
│   ├── db53ea0bf4148315adf653c88db612208059aafb.nq.gz
│   ├── db54eb5214b3c9f7a2094afe3a9f3f019c7ba5ae.nq.gz
│   ├── db58c24cfb4c44180bc060ff6ead1f8da1e85dfe.nq.gz
│   ├── dcc0e0ecb30051f0d2bd0043e6a27a7598a6863e.nq.gz
│   ├── ddb93827892d97490d66a14cd46b683e0f9e93f0.nq.gz
│   ├── e1ff9af944f00782316d3a4c0518423a7b67ab77.nq.gz
│   ├── e2acaaf1bc2a923010289b0792a7deb276092d4d.nq.gz
│   ├── e38a1f85ff0ecbf41bb4547e41574b0ce618238d.nq.gz
│   ├── e3e204a6eb540532d2dd2d73353c4e0ade0d03e6.nq.gz
│   ├── e76f3294fa15f535a7d81b7fa5cb0654ea99ff1c.nq.gz
│   ├── e8e1945b9541fdac79e932c9c3d8556c40e8cce7.nq.gz
│   ├── e92b84938dc41b7c0d92ee00266cd1fde3d2197b.nq.gz
│   ├── e931241c3c80cd5aba1c7995fa13a2a6801ffe36.nq.gz
│   ├── ea0d149c7c138ca9cd48547da2e148c93d670e5f.nq.gz
│   ├── eed4b50ba9c23137c0504b1865792ac205e50e0b.nq.gz
│   ├── f10c98ba4ff4d201e463a397380edb661971ebc2.nq.gz
│   ├── f326798f00d820bd6466fcca9742bcaff4862615.nq.gz
│   ├── f888caa4a2580be756bff539a55998128911cad5.nq.gz
│   ├── f981c0fa40d11387a217090cc64623e6023eb868.nq.gz
│   ├── fc0fdc6ba195329a01af032bf1408bdbcce69376.nq.gz
│   └── fd1bc53c9a2b9d7153202005411c2d4ae5d59668.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── b3f511828462ac854d18dce011de638a45d6191d.nq.gz
├── filetree
│   └── b3f511828462ac854d18dce011de638a45d6191d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 142 files
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

[block/madrigal](https://github.com/block/madrigal)

---
*Parsed on 2026-10-01 by [repolex](https://repolex.ai)*
