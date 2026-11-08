# Repolex Knowledge Graph of canonical/transition-tracker-operator

RDF knowledge graph data for [canonical/transition-tracker-operator](https://github.com/canonical/transition-tracker-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/transition-tracker-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── be0bd9af2c4857b822d3e5c6cb61a66463f75975
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── be0bd9af2c4857b822d3e5c6cb61a66463f75975
│           └── chunk-001.nq.gz
├── blob
│   ├── 0a98951e89633285257ec006bd9685f29938543a.nq.gz
│   ├── 0cfef032983ea4d9da6318c0eb8d4a4db29375d1.nq.gz
│   ├── 0df21ca3fa2aca32d5cbe48e7a6df4c542e189d8.nq.gz
│   ├── 12a092ddcf6d9f15cb21e5353d3a4b97a6c02816.nq.gz
│   ├── 15a2cac8b3812428ae6969d01079db166c57ced0.nq.gz
│   ├── 206e816de485cdf50d19eaadb426e4b1b85377a5.nq.gz
│   ├── 28dc629051b1941afc4673a14accad31d4c7799a.nq.gz
│   ├── 2dba3d318346f2082fe1b3e26860dad80aaf1356.nq.gz
│   ├── 2e79389c2314c6479179f6808ae36fa4e09bdfc3.nq.gz
│   ├── 3a26184f1af191c5005426d82842df0021c0da57.nq.gz
│   ├── 3d717c2c38d6f14aaf2dba30d531ce28017c8ad8.nq.gz
│   ├── 3df9c5d5e14d3eb8cc9027f6af318b5688309eb5.nq.gz
│   ├── 4155610f4f596852312ffb1523b44d48476552f8.nq.gz
│   ├── 4924d48bf03e24a89de206ea6576b5b180990ff2.nq.gz
│   ├── 4f96da1d8b6b1aded0d12c13a3acda58690cd9c9.nq.gz
│   ├── 5149e7723fbbf9d129fe18559050a88103afba2c.nq.gz
│   ├── 53fb9aef94b4f353a08f0555b709af161173b924.nq.gz
│   ├── 5414b2750f4f1d16fffc7224099124d20fcf352c.nq.gz
│   ├── 59e8f9b8499516c81baa3c7474a491d7043995be.nq.gz
│   ├── 5bb62df98c45f0bca65a4dfafb234b1053847de5.nq.gz
│   ├── 5d6cf91460e6e5652be71119bdd2046955b52229.nq.gz
│   ├── 5db16a51be17a99fc066859425b7ebe98a3ada65.nq.gz
│   ├── 66649de94c98ef7f1e46f41e111b81189077d8bb.nq.gz
│   ├── 67b9c69b5cc30c6426745321b73dd1076aae4098.nq.gz
│   ├── 7440621b485ad2822881c7c9898d408d603ab0d3.nq.gz
│   ├── 75d21e1cf592a72e1c26fb8ecfa711ab3dc29d92.nq.gz
│   ├── 778400a20cc3de2a40643841ff255008a0b905c3.nq.gz
│   ├── 82847ac1e77303281b2d0d89b8658e5d94897e5d.nq.gz
│   ├── 85689b8c17a8fc88e2ea822d6b30774d0fcc0e8b.nq.gz
│   ├── 86199f30baf079e60299c238a4fad6637139f6d6.nq.gz
│   ├── 8847a3f456d5a4155d393f5a7fc0e42a37365322.nq.gz
│   ├── 8a5a0c0b5994ce159c84defbf62c3646e5892d66.nq.gz
│   ├── 8b080928cf7ae836d0a3ab9a5f72ac23c51d1b56.nq.gz
│   ├── 8cc480fe5dce6d354a0de9e5548cf8db7c069a95.nq.gz
│   ├── 919621f972b227fbdd3bd0131a8ae56c5d765760.nq.gz
│   ├── 93fe7d52b5f768f20909825a46488edb0ed3b256.nq.gz
│   ├── 9485d77fa4b3866eeaabe1873b1f55048eb88ece.nq.gz
│   ├── 97adb4f518f613b80d521ff99dd4e317bdbd0f0f.nq.gz
│   ├── 9a968e6c635a2bbad2a8a7d5c8fc153b5975a469.nq.gz
│   ├── a504ce998cd58008de74a6ebfdaf4e36534624e9.nq.gz
│   ├── ac97d401a864cd1e0f49ea30de9da51fe1e57aad.nq.gz
│   ├── af02e90d8aa8cec1ef0f3bf6d51bb75bc0d36ead.nq.gz
│   ├── b6207690f2af8818456fb996f43542d69ecd04a6.nq.gz
│   ├── bf8a9b01db23031b24cde4ac7c90cdee4d491808.nq.gz
│   ├── c53da844df01ba2cfdb2f14d9780e253e9ec3488.nq.gz
│   ├── d0250257433b2f5727d5ae95da1058ee85212771.nq.gz
│   ├── da9608dcc511d8b7beaf6e60469756d05db9917f.nq.gz
│   ├── dfbf329abed211899fd93f7dd4de24e762bf0cef.nq.gz
│   ├── e2bf0461c54597d3912b26451203a2fab738af24.nq.gz
│   ├── e968447a59e31d9a4362dcfeb2c1a5a5a7af9d51.nq.gz
│   ├── eef596cc9cefab8b4d9ccabf89b3c51acf3d66f5.nq.gz
│   ├── f0603da7d668cec27af15b1fa3006b67af4c0796.nq.gz
│   ├── f288702d2fa16d3cdf0035b15a9fcbc552cd88e7.nq.gz
│   ├── f6c7e4d2e26cc7af29077ceccf67e7272c1f9f41.nq.gz
│   ├── f8aabc0f7100c78c31fcac09f49d203041a2dbb5.nq.gz
│   ├── f93b8632edcddcb5e23f05b83117b0b4d9d3e924.nq.gz
│   ├── fa7bdebace1e8f7d911c556e23ec1e90e28333ab.nq.gz
│   └── fc8e7868641ae19b5dab9428dfb407e48d3174e0.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── be0bd9af2c4857b822d3e5c6cb61a66463f75975.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 65 files
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

[canonical/transition-tracker-operator](https://github.com/canonical/transition-tracker-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
