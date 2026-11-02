# Repolex Knowledge Graph of apple/ml-cross-entropy

RDF knowledge graph data for [apple/ml-cross-entropy](https://github.com/apple/ml-cross-entropy), parsed by [repolex](https://repolex.ai).

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
rlex download apple/ml-cross-entropy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3de376c106a1916bc5e1b619f9c77c87a461ee1c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3de376c106a1916bc5e1b619f9c77c87a461ee1c
│           └── chunk-001.nq.gz
├── blob
│   ├── 03d1cbfb00dbf790b77ff5c90e6dcb7ed4616881.nq.gz
│   ├── 0a1b777a771ca1cd0ce4d964769a9be583365c5d.nq.gz
│   ├── 0e723720db6858e32154eb5ef7562913a17ebcab.nq.gz
│   ├── 160f60a215cda88732b6a8933a5b282051c9dc41.nq.gz
│   ├── 1ac9913a9a2e7e4ae77d48527a1be56515c81bc3.nq.gz
│   ├── 1ba5bb82a686ea325ab7e2044e0cb501fd987541.nq.gz
│   ├── 1eb0e467e078b70a763ec77e047c5c2054fe240c.nq.gz
│   ├── 2ab2cfac43b700f0e7a7e5e966c3f24587be2f15.nq.gz
│   ├── 2c4251a401d1ba0e97d351ccc02609b779b640ac.nq.gz
│   ├── 2ca75b5daa127d9b041ce04bfea0025939cc9e18.nq.gz
│   ├── 3ae2707f246aa7d14f5b8c890e134721587e55bb.nq.gz
│   ├── 3d43c40d2b294ea33400443f9d43910d72bfc3b8.nq.gz
│   ├── 3d79b63d26cdc818c54249554a45eb2a493f1272.nq.gz
│   ├── 3e6b610309424833d19f8abd50ead410482f4614.nq.gz
│   ├── 41113ff547626cb45aea7b4a67b5d41983e88eb4.nq.gz
│   ├── 462664b03f878e0eba38f6af427895f2ab98086e.nq.gz
│   ├── 4cc0720dbadc2eaabc342c4d51f4afc91009f204.nq.gz
│   ├── 4e0e138184d23690542cc405a622bb8d25a93c7b.nq.gz
│   ├── 5d5c9e7ca5598c900a85c86e047b717d5d63e6cd.nq.gz
│   ├── 5d81e9f3a4633d4c69d45296c22b004ac24675f7.nq.gz
│   ├── 67d846132dd68854b6c4eec51fc6f0ce9701ba64.nq.gz
│   ├── 71f4e6a323dc84afeb74fce9e982b9056a506df6.nq.gz
│   ├── 74005dec8e4e06460953d00b90919dfa9aa90968.nq.gz
│   ├── 7ab90b7d9c42053f611e5390041b7541236c18b9.nq.gz
│   ├── 800a366e8246780f61d6fd76440c8df5ac4ef5e8.nq.gz
│   ├── 83266352addc4b22aa528ce564db793238b88ebe.nq.gz
│   ├── 860ace814082904116f1fa8745b4d8165a5b726b.nq.gz
│   ├── 8808370f78336f931e03370ca8ce3889a0253739.nq.gz
│   ├── 8c2c3af7af0a84e9dcacd0c662efcd6d9e8dd6b5.nq.gz
│   ├── 8e0e7ca9edabbaccd5189b2ae65ba9d41242eac9.nq.gz
│   ├── 98f75d0c6ad9e11c2036a8ea6ae0dd2aa5d1b4b9.nq.gz
│   ├── a02ebe455f1572da9fb6f53b9a9c2e82125b5d94.nq.gz
│   ├── a11be643e12cf4081061dc42b1438016be923f63.nq.gz
│   ├── a8aaf291617b56c2df4edfecbec520dc0d3d9ed7.nq.gz
│   ├── aee4c32fea2b2546dd6346d36c282c1639dcbaeb.nq.gz
│   ├── b825c490ab7c7621dc210c253883a5d5679c0c5f.nq.gz
│   ├── c84e2ad281ecd2e1700c603985487c5d516ec7b0.nq.gz
│   ├── cbaf7a062bb4c541baa25b14b8bdbc0c14d1dcd5.nq.gz
│   ├── d1aa73c17713409eab7f69d5085bde67679ec8af.nq.gz
│   ├── dc297a609becf924d745ba8e4bbd73366f580b42.nq.gz
│   ├── e17d1123e51873801fde040b0052398bd1d230d6.nq.gz
│   ├── e610a7bf3601e83c5af2924f1a9cee3de4ac968f.nq.gz
│   ├── e6f6ed544c4b5fe9fd4b0239e3f7a1572b92cc49.nq.gz
│   ├── e73c8154b8cd1cb2c0051e71fc6c1ee15d6d2afa.nq.gz
│   ├── e858faa51df55c3bdcecc264cb97469ec4bb2960.nq.gz
│   ├── f7cac23c4fafdbab1e21616d7ca7e467a3a8d96d.nq.gz
│   └── fdb83e12fe08805ee2e57b626f1677c7717d0c6b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 3de376c106a1916bc5e1b619f9c77c87a461ee1c.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 53 files
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

[apple/ml-cross-entropy](https://github.com/apple/ml-cross-entropy)

---
*Parsed on 2026-11-02 by [repolex](https://repolex.ai)*
