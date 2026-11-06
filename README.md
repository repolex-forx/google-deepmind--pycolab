# Repolex Knowledge Graph of google-deepmind/pycolab

RDF knowledge graph data for [google-deepmind/pycolab](https://github.com/google-deepmind/pycolab), parsed by [repolex](https://repolex.ai).

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
rlex download google-deepmind/pycolab
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6504c8065dd5322438f23a2a9026649904f3322a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6504c8065dd5322438f23a2a9026649904f3322a
│           └── chunk-001.nq.gz
├── blob
│   ├── 00097383c2df226b0bc0911ff6c5ba3d0cc90b64.nq.gz
│   ├── 046333d2b38db3dbfbd7d8cc04f67ece847cfda6.nq.gz
│   ├── 059175725f58e9321ba20852842bd7144c9bf439.nq.gz
│   ├── 0d5553077aa0941ce79f8f1eba837ddaaf57173e.nq.gz
│   ├── 2f0f35c45055ccd48602b346ee1e1017f788a453.nq.gz
│   ├── 36e9b5722d5554e3c8cf3c4de91f5cb8c0b12432.nq.gz
│   ├── 3cab8ffe77922bb34fcb8813c1685dd0cc6eee74.nq.gz
│   ├── 3e908a85b0b3f302f9c21066855a63ddc6800187.nq.gz
│   ├── 41a8e4d460ba9cfb2e4a8692a4ddb8c5c719a714.nq.gz
│   ├── 43115d3706796d78ef2d9f368ce6a38f6d284d64.nq.gz
│   ├── 43841dc1d157b8cd0803279182cd23b8ab00df89.nq.gz
│   ├── 4595c753f3aece7d012d6326defb88e1a2f02c52.nq.gz
│   ├── 4784971f71bc1bd1f3d98c84fdbee4ee26fd75db.nq.gz
│   ├── 4a25afbf63b5a90156568d659f9b7fe52dfe55b0.nq.gz
│   ├── 4b1936894d0d7c41068329d87a3ddf94793b1461.nq.gz
│   ├── 4f3eaf0bb326f0a28b274969e383f9ab707537f8.nq.gz
│   ├── 4fe36f7286321fc25c486eab55bc118e3016e456.nq.gz
│   ├── 51dc810afe2b6a2df21dbd94a980983896e6581a.nq.gz
│   ├── 5201a8723738a0d47dfd63063e643c92aa9ee354.nq.gz
│   ├── 5b67a865e13652cd2b8217fb678979ad066438f8.nq.gz
│   ├── 5fdbd342444349485bd5f0418b0ad91341b298c0.nq.gz
│   ├── 6487af77548f35b046a2b9c4d08bfa42b5982e16.nq.gz
│   ├── 72969ce536bc03cc5092092934d06c20d6a4bac4.nq.gz
│   ├── 78e097815a83c2cb28d4682aab798887749c908f.nq.gz
│   ├── 7a74167a92f3f63e05e7f195a7d0a8f1f2f19166.nq.gz
│   ├── 86ec3a6845591566935712ee03a4bff9f03d0636.nq.gz
│   ├── 8cd32933b752086bb0928be5b0871e1941ccf74f.nq.gz
│   ├── 8d7990d3f1f669b0017d80b14e1d9f0286c1dd0a.nq.gz
│   ├── 942831a9b0318964ed03d7123df7dce6917b4c18.nq.gz
│   ├── 962db36d6eb97030547514b68ad715fb6c342ae1.nq.gz
│   ├── 984d8a9fb5f5215a1587a400916b8632ae69d1de.nq.gz
│   ├── 9b96b61ce337421657f82e67fc5533d526f63a21.nq.gz
│   ├── ae529ca98c2045c2954b0f5e8c496bcd93d9a3b5.nq.gz
│   ├── b48af18b0a3641504c768d5d6e2aae3a08eac965.nq.gz
│   ├── b707d534ec88d9a984284bbb728c103f58ea9f41.nq.gz
│   ├── bbba6bf7f52da986598eb5de127fa6e9f141ce46.nq.gz
│   ├── bc27a02c1ec78300b3b0f5e5972973469e4e2a0a.nq.gz
│   ├── bd0f53ee2ea9a46042f629d06e97215d045d6a0c.nq.gz
│   ├── bec6caf2ac21d79602e9615dada93e0689c7286c.nq.gz
│   ├── c4dfab7e2e4ed821e05c7f94869e614914e2e708.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── e8f3854c2c23a7ab16c0f0778707e8ed3c3fcc04.nq.gz
│   ├── eb135bd32d83e6e347e1525e994f847f7b383850.nq.gz
│   ├── ec79c08bc3a69a6384f4bf81824603973be78b42.nq.gz
│   ├── f104ff6b07f3c6a048b85c59525f1fd2666df765.nq.gz
│   ├── f9d5884e901f8b7554480c032339024a38b2a52d.nq.gz
│   └── ff16465ed565f67262b32e7c9ffc0f8dc8db8007.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6504c8065dd5322438f23a2a9026649904f3322a.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 54 files
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

[google-deepmind/pycolab](https://github.com/google-deepmind/pycolab)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
