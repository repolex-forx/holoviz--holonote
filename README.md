# Repolex Knowledge Graph of holoviz/holonote

RDF knowledge graph data for [holoviz/holonote](https://github.com/holoviz/holonote), parsed by [repolex](https://repolex.ai).

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
rlex download holoviz/holonote
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9928494bc2bd36f9261a19a19f97a69bf55f82e5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9928494bc2bd36f9261a19a19f97a69bf55f82e5
│           └── chunk-001.nq.gz
├── blob
│   ├── 0797b74143f8a71d78f10966bede05e359d25747.nq.gz
│   ├── 094005f491780481dccfabb181f776603dee1fa2.nq.gz
│   ├── 0b6cd168a63bd4f83b8638d39e6687c6ee61b781.nq.gz
│   ├── 0c9cacd844b88758cd889cd6753f1149d1e88352.nq.gz
│   ├── 1634dd0ce789a7693aa50fa3a17bea23fcbfaf64.nq.gz
│   ├── 297aa86ff27449f835993f2635ddb2f9942d4360.nq.gz
│   ├── 29b2d72a3c45d068fb1aee6487297b0c8ce56845.nq.gz
│   ├── 2f28ca10e26a7ec2bb15bacba9c2ebded52c361b.nq.gz
│   ├── 30be41272e2ae723b3a0a9cd07bc7793bfd5f4a1.nq.gz
│   ├── 32e8e8c95ccd05930ad108ad94d0611a40165704.nq.gz
│   ├── 33eb702ec395ac71fe3c6fdeb6f837ef12e0b7df.nq.gz
│   ├── 3bce63175aefe16c299065a6b77235ee5dd8cf2f.nq.gz
│   ├── 3e1c02d86d2fd563e16e021649ab55c366746b88.nq.gz
│   ├── 3f28b05b41782f40c97760da6539d64d4ac1aa48.nq.gz
│   ├── 3fb9f0c4071f3dac8a5a2ef066b71cf13c8bfaec.nq.gz
│   ├── 407ab63709c85b470502b7c475f75077c140ce71.nq.gz
│   ├── 425f3c2529f2dd835d57f59b6c0aaaa6f67afb60.nq.gz
│   ├── 4db5f6bc12ac8bae2394ae4ccbe6f5e447f29025.nq.gz
│   ├── 543670cba2f14c934c9e097b0ea4fce756fd07ba.nq.gz
│   ├── 55269bcb1f71797b8b32d5119e9c3bbb74c56825.nq.gz
│   ├── 561c7b68c88d26355381b57bb73a83ed1fe6aced.nq.gz
│   ├── 5a28f015fb2b9a8fd9487bd3ee1da00b62688a1c.nq.gz
│   ├── 5a33d32536df2bdd7e710e22c97126dd49fda26a.nq.gz
│   ├── 5ab65ff74d316c1a6f228a10dd4184fa09e0cbb7.nq.gz
│   ├── 612dd7b43c3aa3f35c8f324a9146033f9783f26f.nq.gz
│   ├── 690c678a955907b06ec44ab5d4ae8645a0439fd5.nq.gz
│   ├── 697c75d3ee48e2fe28d0635e5624896d78d382bc.nq.gz
│   ├── 6e24804c978c9d47a004b8ec156a55825ce0f6cd.nq.gz
│   ├── 7394eec767612180e1345f6dd375e852f5286e3d.nq.gz
│   ├── 7a4b07400184c51ef7621b710c575eee907b0d20.nq.gz
│   ├── 7b57c317f10f4cf76de06e92aee808ae418f6c69.nq.gz
│   ├── 7f70f8836157ac41b28ff7bb2c5d43261c9f1d0d.nq.gz
│   ├── 8848e23501c70fe2cfd0aaf4368d1bc7af277156.nq.gz
│   ├── 89bc3c91a04b8e65fb9b5252776d919a759609b7.nq.gz
│   ├── 90aef9347f94d40aa58aa3a960d886421882ab24.nq.gz
│   ├── 9256f97437542c5bbf5775cfcd5840f31f45e8c6.nq.gz
│   ├── 929e5157ec7f9806b4da70665f0905831855bfc6.nq.gz
│   ├── 93cc07f69d0cc77e1124c626ae1a6a73088cd4f4.nq.gz
│   ├── 94e2ae9a8b940a5e84e3316637a9edcd21fdd221.nq.gz
│   ├── 98a5a66e974c665048b6f8e74581e36eddc1f65e.nq.gz
│   ├── 9b1c0662475f70395867a55a695b998bdabde266.nq.gz
│   ├── a47b876eb5024cc852d8ad5b7a0dba1aa3d2c5fc.nq.gz
│   ├── a797dd60abc88641e8b735a61615889f778ce5a6.nq.gz
│   ├── a81cb8cccb43154ff89321955b390b8816b6b116.nq.gz
│   ├── ae45c1edefd147581533c016949d5d138a7302ab.nq.gz
│   ├── afe05131bcb53d2a805a8161e5bc550ccf3a60db.nq.gz
│   ├── b509d928fa6ca4a0efc436a07d192786bd6b2a50.nq.gz
│   ├── baaed357281fa395f9caa3c8f319717ab227afce.nq.gz
│   ├── bbfbf4745057e428e32a094c24d44ac63f8671da.nq.gz
│   ├── bde3bdcc5b7f4ad3d4c3bf76cd3d120f3c8077aa.nq.gz
│   ├── c09cf753bb784360047b1b0aea5bf14bde2086d5.nq.gz
│   ├── c46e1fa0df94c404e59c0c5dccaca39968af6331.nq.gz
│   ├── c77c15be998d99ad45d603a3ad59ece352712be5.nq.gz
│   ├── c7fe96dbd4c106a5cc00fbdbaa3ca6bcb75e11b3.nq.gz
│   ├── cc69f9b234918f087f1689e71d9839d4e550b4ea.nq.gz
│   ├── d71a53290b2fb18570f03ca46c0cb0308c9e1ccd.nq.gz
│   ├── d97f94223ab76a4edc74d81c82c77dcdc1bc4ba4.nq.gz
│   ├── db01e0e9940525f36879e9125764f359e8c4d943.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e848b9e6935ae56fba79c92e2d9a1cfd04aa9abe.nq.gz
│   ├── ebe0090c6f195a1cdbaf8880077c752d0e89a823.nq.gz
│   ├── ecadd6f9e9452d50c06c74ef97f3bf45a3e6dfd2.nq.gz
│   ├── ef0587d914ffb7b99299d6cfc35e463671796a41.nq.gz
│   └── fe6437368bdd8708477a29dfb27c43ae2530cccb.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9928494bc2bd36f9261a19a19f97a69bf55f82e5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 72 files
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

[holoviz/holonote](https://github.com/holoviz/holonote)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
