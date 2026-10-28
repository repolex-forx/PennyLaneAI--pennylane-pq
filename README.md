# Repolex Knowledge Graph of PennyLaneAI/pennylane-pq

RDF knowledge graph data for [PennyLaneAI/pennylane-pq](https://github.com/PennyLaneAI/pennylane-pq), parsed by [repolex](https://repolex.ai).

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
rlex download PennyLaneAI/pennylane-pq
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 854f103f0c21fcff6ffa83b0b1db365c4f5714a9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 854f103f0c21fcff6ffa83b0b1db365c4f5714a9
│           └── chunk-001.nq.gz
├── blob
│   ├── 0c0a43a8e42b99c28f53401d5c9df5658675491b.nq.gz
│   ├── 1ca4fba0b609f2cc6b8399d9d0fcb52ce93f0cdf.nq.gz
│   ├── 25269e21a47bb4d93ce80deaab6b95ccf7b2edd8.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2ad508a2b3acb619d064608d6fee05eb9ff1ce18.nq.gz
│   ├── 417de4b55ee5b8f0733c826c369817c15f0dc3a8.nq.gz
│   ├── 41de9885c578ed3240ffa8244f7e76ba9cfcd7f2.nq.gz
│   ├── 452222b0295f707bd453dd20acdde51369b19684.nq.gz
│   ├── 469e6b93aa66af69c739ae064a2fcaee0adc764e.nq.gz
│   ├── 46f7684bf86f111c7b6703c7e1483195c3a448c5.nq.gz
│   ├── 4a1bc99591d5903fb43b1df5225859dc0ad88c7d.nq.gz
│   ├── 4de5643206e0323b1232495aafd664c742fc106b.nq.gz
│   ├── 6250553d21bb8e83774db95a24f81cf09b991858.nq.gz
│   ├── 6af958d9f2828525ecb16653872ce93ffb911049.nq.gz
│   ├── 6f05ef4b57f53631812e1331c57312f039f9186f.nq.gz
│   ├── 6f9e005b8c172b734d433f5eb753ec45a8206de5.nq.gz
│   ├── 6fe54ded8910e5617ebfbdc83a4a505ceb035b55.nq.gz
│   ├── 7047a605a0f222c1ec272c7c18db35c47fb1de3b.nq.gz
│   ├── 70e16617aa36b3aa5cacb9492795d68bf7028014.nq.gz
│   ├── 734dc40efffbdeae9dd2e9f1856ec4d32812535f.nq.gz
│   ├── 7441a785d273122df326e4f0bdb75616ee593a66.nq.gz
│   ├── 78bb39f74d682dce393c1d7ab0ef56cec28f25ea.nq.gz
│   ├── 8078c3f1a16f8a48ca9aeca1d2e009583794dbec.nq.gz
│   ├── 81043eb4a00e4eeefe544ad535f91d38ad2ec118.nq.gz
│   ├── 856e174454dfc522770d959b815004fc72b009bf.nq.gz
│   ├── 87ea55357468d3a0130d88125e1b25e35b4a5248.nq.gz
│   ├── 88ca9a7fda464b30e1235472e9cebb4245a12f6d.nq.gz
│   ├── 88ee5c274182189b0486e1a63147068eaf6acc4c.nq.gz
│   ├── 91b8c3d2445ecace4df870196179b7df8dfba46b.nq.gz
│   ├── 9eb2ad5f12b3bec44d6ab1adba9ea899af54ebb5.nq.gz
│   ├── a472005536c349d58b045cd4f79d553f8a4e47d3.nq.gz
│   ├── aa9952c95564d3e24694230f9704777797bddc8d.nq.gz
│   ├── b0b7d0963415da7938f5107b65f95c9bbce66444.nq.gz
│   ├── b69348d97da3e161718a410312935f4746b6cb54.nq.gz
│   ├── bef23c1d1fc1ec6b64dc11c1b2693e7ae8d91eba.nq.gz
│   ├── bfe76c0e9b609deab0afdd0aee8df189404257e3.nq.gz
│   ├── c01adef96667b9fe248921a57b55e05cb412c6be.nq.gz
│   ├── c1abf5ce880a2cf740a44abc033326098d8524f3.nq.gz
│   ├── c51b21f94ad40933b6a7ae315ac80dd9853b347d.nq.gz
│   ├── ca7810970a39395e3364cbe2a688a073a5f3f431.nq.gz
│   ├── cb7f51be30a12b0c5d59994337692dff4e18cd15.nq.gz
│   ├── cca6d8e0747cb19f3e1fb6f1f545564ced4b94a0.nq.gz
│   ├── cf510d1b3ccda19d64692a87b998b1b0b134747a.nq.gz
│   ├── cf571f1032d71d97c904c8951ea3ac1d6579fde4.nq.gz
│   ├── d757d0464bca37359cf0d305faf5bc212f4af51e.nq.gz
│   ├── d9a259015802350bb2e9b9ea963b8b95cc1d61f8.nq.gz
│   ├── dbaaaa6a6c1f7529d879c1d6c9bb84ed55e99451.nq.gz
│   ├── dbfdf634be67e30360c8712852f91218ed553e9b.nq.gz
│   ├── e5772c53cf17b1fc656b898586520d83a719365e.nq.gz
│   ├── e6cc842ae8e3d4e880a93e627826a01d7588e62e.nq.gz
│   ├── f3fcfbf670d5d3ec7731fbb4fd3f04aacf4c2f57.nq.gz
│   ├── f67bec815653a41d9d6bb7cda75b00f728640fe0.nq.gz
│   └── f9f73d852ce5393a5f1efcd47bfea20d3b3dba69.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 854f103f0c21fcff6ffa83b0b1db365c4f5714a9.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 61 files
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

[PennyLaneAI/pennylane-pq](https://github.com/PennyLaneAI/pennylane-pq)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
