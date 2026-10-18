# Repolex Knowledge Graph of ionelmc/python-lazy-object-proxy

RDF knowledge graph data for [ionelmc/python-lazy-object-proxy](https://github.com/ionelmc/python-lazy-object-proxy), parsed by [repolex](https://repolex.ai).

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
rlex download ionelmc/python-lazy-object-proxy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1030dfa676508f8f0cdc30fcaf04aa391b162e0f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1030dfa676508f8f0cdc30fcaf04aa391b162e0f
│           └── chunk-001.nq.gz
├── blob
│   ├── 08936d99094e1b728f76a1a13bc81ce1cdbe0cb7.nq.gz
│   ├── 092ed8ff29611de7c0afd1f550bda3ed411b742a.nq.gz
│   ├── 09a3355e091ed05ab9090f152bf938d11ce2d75f.nq.gz
│   ├── 0f0bd3b27e98f98b8498fcf4fb4b4363ec80440b.nq.gz
│   ├── 1dc893d9c6abfa7532f6957d7c81bda0a9d5bbf5.nq.gz
│   ├── 2c0af2c7915534918166677ea8eeca36fbe6b2fe.nq.gz
│   ├── 2d82389e2e3bd274a6154ce30203a199f7cbdd06.nq.gz
│   ├── 386498105e30cd1291e10164997ff10be8384e3d.nq.gz
│   ├── 3b83e53700d42857da9377643252eff226b79d27.nq.gz
│   ├── 3eb9cb2e6306867c392c23ea5d087ef5bac1e369.nq.gz
│   ├── 436cb55aba0661d8beaf1e8b0d875be343c8db1c.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 5958f05e91fa6a12394e096958400cc2f1ee6544.nq.gz
│   ├── 5f7d05ed43b81792236ccdad97367f566a0aece5.nq.gz
│   ├── 646ca42a866d788b6b4bb9202d1c005489be74de.nq.gz
│   ├── 704f0edab78a74d928e1357a19d918fa1e5ee34c.nq.gz
│   ├── 720d768eda46f164737992a9fc89b4c77ea45586.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 7ae009c8d085498944b3ab0ab731e595cc6c7c72.nq.gz
│   ├── 7d7b9b8be744f0803aeff48d4cacad1ea35ed489.nq.gz
│   ├── 827d95831257a9f38bb139ac3abf8f03dad3877c.nq.gz
│   ├── 8fb235d7045be0330d94bcb3abd2ac43badaa197.nq.gz
│   ├── 90c1cde8fd36afd0eacc57e85f545bd22bda2664.nq.gz
│   ├── 9d238511afbdc271b0596c68a90a6132fccf11ad.nq.gz
│   ├── a2d480bb79405d1371da3c20e8fe0f3999995624.nq.gz
│   ├── a6938416b72124caad903638dba62e6d7cf10003.nq.gz
│   ├── a8338acd4e1dc515ec4f0b7e2415d12a952b52b0.nq.gz
│   ├── a94cb2f8c249bf0b4dfc46a28f3008ab0b9e1b1c.nq.gz
│   ├── b5c833436c2184641e7d644fc2dd6add27c3fe4c.nq.gz
│   ├── b9a10eef4da30573fda8bbd3bf7ac4ddbf01fdc2.nq.gz
│   ├── c03e307ab39cd6807b9bc0d8f404e716707c2533.nq.gz
│   ├── c1a280731498687c7c31c989352de02af0ada697.nq.gz
│   ├── cbccd346d1ffeba686e3c28126e09fd3a5b0f7d8.nq.gz
│   ├── d9ebde5b8377bbbae9658d4d4e75492b7e0cb606.nq.gz
│   ├── da9c516dd744b6c88dd8c91f58f7bcf8f7e8341b.nq.gz
│   ├── dd552b644671e3347403be45929bebf19d99f5bb.nq.gz
│   ├── e122f914a87b277e565fc9567af1a7545ec9872b.nq.gz
│   ├── e499d439f96203f9a38ae7a5e77626a7a175b8d3.nq.gz
│   ├── e582053ea018c369be05aae96cf730744f1dc616.nq.gz
│   ├── e642211365f960e9478ebf5b353eb9d616705125.nq.gz
│   ├── f34e5366983f9e1e9dbe1f89531aa6ccc6722ca2.nq.gz
│   ├── f69d0bf2fa5b2bf8dbf93402031513cdea20e5fd.nq.gz
│   ├── f95eb78d8a603b0fe5d17560d0dd04877d55c71c.nq.gz
│   ├── fbe1f06b1044bb24b03752858776bb9f6a28b19b.nq.gz
│   └── ff5e5429e5163cd4be3c00fe9094750d63cd58c2.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1030dfa676508f8f0cdc30fcaf04aa391b162e0f.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 53 files
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

[ionelmc/python-lazy-object-proxy](https://github.com/ionelmc/python-lazy-object-proxy)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
