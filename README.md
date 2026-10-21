# Repolex Knowledge Graph of networkx/grave

RDF knowledge graph data for [networkx/grave](https://github.com/networkx/grave), parsed by [repolex](https://repolex.ai).

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
rlex download networkx/grave
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 944049f4fa639811b477e50e07ade5b5d1a0a7bb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 944049f4fa639811b477e50e07ade5b5d1a0a7bb
│           └── chunk-001.nq.gz
├── blob
│   ├── 07633cf89c025ee6c39e0aa7b0856501d2656ced.nq.gz
│   ├── 08b39dc6830c2309a68212acfab956c4ceba4cc8.nq.gz
│   ├── 099faab230fe0054adecd41d47fdd087d707eaad.nq.gz
│   ├── 0c28f78b4046cb189381d4bf9d1847fbe39a6d1f.nq.gz
│   ├── 13da4a7d115bc359243607d64d6ec71f6d1fb4a3.nq.gz
│   ├── 1a909fdde8f9e9558bfcc6e4babd626120e69c6e.nq.gz
│   ├── 1bb7a577732c91ee6aa31de8f81045b5622126b2.nq.gz
│   ├── 1bc06c2785f76737ec3df5fb56395b5624b2fe33.nq.gz
│   ├── 1cc7f50eb2947d826bc3184b707fd37550eed84c.nq.gz
│   ├── 20f4dcfffd4ae0e2d00146c283b7dabbf635bcff.nq.gz
│   ├── 2626b3f50351df138e2ff445e365b325b3f854db.nq.gz
│   ├── 26ceb9cdfbf3b1633f236803f8885ab676064dd3.nq.gz
│   ├── 293335f1f3791035d851b43906b1d957274f2823.nq.gz
│   ├── 296e685653af1270f3a9a45d75b3a68210e46962.nq.gz
│   ├── 2ac1606a13c44fea003dc3f1ac05c0e7fb6acd61.nq.gz
│   ├── 2d5aa5ed9d6858794f653ac10d99cef9057b69d1.nq.gz
│   ├── 337670ef877cf46b09800c35e9c2a46833dedd1a.nq.gz
│   ├── 35a1c5bcb0864d809be66bef1210273974dfc005.nq.gz
│   ├── 35c4f19b5e60dc1de60c9bdf1186077b040ee680.nq.gz
│   ├── 369d9553958007e74a46e4bfd08d0d088259832a.nq.gz
│   ├── 37875ea7f9256960fed7b64d8b23876290a8118f.nq.gz
│   ├── 3e185e435779609c81810dfa6be0b0daf015a8c8.nq.gz
│   ├── 3e6dbf292628dc0064d682ed2236bb533b259f8a.nq.gz
│   ├── 3ee3d4c3e1f4e7148259d77bdb93d1297301bbfd.nq.gz
│   ├── 429dd380e791d65c63f20bc65457b565c088e911.nq.gz
│   ├── 44b6104df8b9e7ee3d6c61dacf63ade8d05e143b.nq.gz
│   ├── 473e89128580cc31d62f806062c0b3afe568e363.nq.gz
│   ├── 4a19819e34496e114300d08450350b9e055a16ff.nq.gz
│   ├── 58504099353165762bedd6e7b10739a0d069de88.nq.gz
│   ├── 592877002cb8594aa3340073f0e4ca638b12f780.nq.gz
│   ├── 5f6e2a52ea112dc642467bde918aba19c6aaab3b.nq.gz
│   ├── 62b7f95fb8aebea1f93b55924697e2a1958d3b13.nq.gz
│   ├── 62c75a4f641f4171f6aad7cafb4c902859fba22c.nq.gz
│   ├── 686f54eac6265e9495711950a88a639f68b418b9.nq.gz
│   ├── 69fd6032badae694b4e8c67f7323221bf8a8f612.nq.gz
│   ├── 70829d232e3add382d9a4a24a05d10cf8b44cbf4.nq.gz
│   ├── 710abe08e47797f65483738837bbdde416e9cc4d.nq.gz
│   ├── 75305d191278e43423420c0410bc3e6007643672.nq.gz
│   ├── 7ba161e5e0849e860fc850fcd878a5fd65afd3b4.nq.gz
│   ├── 7ce0ac762a058cdff42013698dbba775aef085ea.nq.gz
│   ├── 830391e7ebc1f19cef2237912de9f6bb392682a1.nq.gz
│   ├── 84acd4cc5af71636139dd66f2f42260913645c19.nq.gz
│   ├── 88809eeadb2ef91be24d781248f16cf6d333ad15.nq.gz
│   ├── 8f027efdbcf9c90d743d68c3092e26d61f74f4cc.nq.gz
│   ├── 92383c05f232dda4c37f957beb37b60ed5899935.nq.gz
│   ├── 958c9c9547746c99282edca0dfede519797f6739.nq.gz
│   ├── 9ab1579b62a5116ea3a778293b2d1c55feb700c2.nq.gz
│   ├── 9b3d664a22adb2407ce597fcaa85aad762b9f0a1.nq.gz
│   ├── a08c9a6b8a0c0348966c068ac9ae949eb7cdffca.nq.gz
│   ├── a23a75e3ea077afe7a141b194f03ed74e8d13267.nq.gz
│   ├── a3d9f596066e83152b2134e5ecd1c1d16933f6e7.nq.gz
│   ├── a43ef25ce73051baa489bc72742c10031b1c4cbf.nq.gz
│   ├── ac7b6bcf35e98139c791cb5c4b94f08849972d65.nq.gz
│   ├── b00022f58b56932eb5685b8cf6baff3072da0b8a.nq.gz
│   ├── b32fb1a3dabb87626efa8a741781e1f9841c8985.nq.gz
│   ├── b4d782fd321bae5717792165ee46a552cadea59e.nq.gz
│   ├── b69a893438915d15b1955770cb69f9f0ef107e46.nq.gz
│   ├── b7e478982ccf9ab1963c74e1084dfccb6e42c583.nq.gz
│   ├── b95404f8002650d72a35a035fe4eef208e677c2f.nq.gz
│   ├── ba803af2384f539454575a8b55d0ca1334c53e4b.nq.gz
│   ├── bdf0496ccbad3b996bc1d35e57ca3748b803ce99.nq.gz
│   ├── c18923a08beb04879b9d34e38346494dd858881a.nq.gz
│   ├── c37e11bb6c98201979313247981cf7911904e3c1.nq.gz
│   ├── c5b910d86342c784e25a5cf2c3514c001e0bf425.nq.gz
│   ├── c67e3702dfca6df40c187c6c74a071841d1f6f3a.nq.gz
│   ├── c7e4a7ba1f13854d52686ee07966b020736d00f9.nq.gz
│   ├── d0580c4268fb6af0f0fabe71a4aa868354f3af9d.nq.gz
│   ├── d0e04134d4d086d0c78c45188848c4a0b71b157d.nq.gz
│   ├── d9b29c8fd86b4dd53b43aa8726f987f368fe5181.nq.gz
│   ├── da779917a9bdd41e149ad9e459a9114ac2b5323c.nq.gz
│   ├── de490433ae323d6f362dd05f692f73c27408367c.nq.gz
│   ├── de7bca297583aab4aad54095dd313a6ffa97dd96.nq.gz
│   ├── e28a818e8ae8ad939e2517a42512965e8737737b.nq.gz
│   ├── e5031681b97bcc3b323a01653153c8d6bcfb5507.nq.gz
│   ├── e5d80e4320731876f3c9ba26d487a587880214db.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7833c7ca71b68f4ec1eb9410a96f9c3625d0188.nq.gz
│   ├── e8b5f860a281f1c04356b771a39e9bc668e4278d.nq.gz
│   ├── f1ce704c87d8248048d5e0f7a1151f376b288088.nq.gz
│   ├── fe04f99d986d1623758c4816565b377761d38075.nq.gz
│   └── fe8c14d4969639a9f59efb04ee9d284c9a638c70.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 944049f4fa639811b477e50e07ade5b5d1a0a7bb.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 89 files
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

[networkx/grave](https://github.com/networkx/grave)

---
*Parsed on 2026-10-21 by [repolex](https://repolex.ai)*
