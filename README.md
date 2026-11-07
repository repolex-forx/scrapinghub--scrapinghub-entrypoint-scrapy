# Repolex Knowledge Graph of scrapinghub/scrapinghub-entrypoint-scrapy

RDF knowledge graph data for [scrapinghub/scrapinghub-entrypoint-scrapy](https://github.com/scrapinghub/scrapinghub-entrypoint-scrapy), parsed by [repolex](https://repolex.ai).

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
rlex download scrapinghub/scrapinghub-entrypoint-scrapy
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── bf9632c78355b545126363ce557106c1b9c3bb54
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── bf9632c78355b545126363ce557106c1b9c3bb54
│           └── chunk-001.nq.gz
├── blob
│   ├── 0473c2ad10f46a82085692e91921c6e5c3994a59.nq.gz
│   ├── 0d9f7afb38255d4584d5d75429f83e1f649b19bc.nq.gz
│   ├── 105fc5503b871423b3e942928c3f378c30d21f7c.nq.gz
│   ├── 1bde33c8830595b5cd13f4e0e7b80e6b1faa3f7c.nq.gz
│   ├── 1e6f215fb9dee7558799a0572bf1916a66a62c8a.nq.gz
│   ├── 2139c3f54c2dcdca78b400af441e4b8190b9c7e0.nq.gz
│   ├── 251f4fccb30d62b60736c8c6494f64f0dc81c00f.nq.gz
│   ├── 25526b8b48e605c186318e764c3f10714ba94012.nq.gz
│   ├── 2a0fbb3533b2ee97c142546b9f0cea0c50444c58.nq.gz
│   ├── 2ac225e7b97bb51d913325e18eb2f1f1d785c95a.nq.gz
│   ├── 36ba2a93ec1f2d367afeeeb5b622ca5931db628d.nq.gz
│   ├── 40408518a350543087f66c736220069ac308941c.nq.gz
│   ├── 40a96afc6ff09d58a702b76e3f7dd412fe975e26.nq.gz
│   ├── 489f9091f684f1fb6cd83108c6023894ee745ecd.nq.gz
│   ├── 4b5e978d7165a914a2d6b3dd50d9e0c72722470b.nq.gz
│   ├── 51e7a17e54ed76b818154c14177f58492215f157.nq.gz
│   ├── 5b6ac2f8bb542e5858a13bdadf778289035f1aa0.nq.gz
│   ├── 5c2547cb78e1fcf56da62c2e2622d13e8f72279b.nq.gz
│   ├── 5f03a2d197829463e47d351c6a9de3095d799eee.nq.gz
│   ├── 71c5f6716702d9e3309809f1a109ba36d7f761df.nq.gz
│   ├── 737fbfaae515cd1f90c361857a7bca399aface65.nq.gz
│   ├── 89ffd6fe5fa7bcd7e958dc0e42c6426cdcccda3d.nq.gz
│   ├── 8e320dd1f1b1acfcf10caebe18e21dd5fe0a5bc7.nq.gz
│   ├── 9078eb1560926f253531a87f510a327e07152990.nq.gz
│   ├── 91d385b2819d7dcc9e2681028c7caf6c89f0100c.nq.gz
│   ├── 9561aa5eb2f3a26a80efffef13875c936fd16a25.nq.gz
│   ├── 986c6fb08723b618a11b107036f8e424b27d7a97.nq.gz
│   ├── 9c4443838507427dca68fb93ea20b1dc3666d75a.nq.gz
│   ├── a0d1226633fd32fe56ba1d0c0be3bea4795dfce5.nq.gz
│   ├── a13166baa90f225669184394253e3bc8564f6282.nq.gz
│   ├── a348a1ca5509737686bd95b5374fbf1e01ad3dfb.nq.gz
│   ├── a68a7ae78b201b01e3b6b2ab6cc200f43f378479.nq.gz
│   ├── a8fec9fd938adef2c5b5e86585319495a5313fbe.nq.gz
│   ├── bb3ec5f0d4c70ef732aa4d399282a5ddb2a008fd.nq.gz
│   ├── c08d9209c321a3d42944c2ca572ec236a748fae1.nq.gz
│   ├── cc95a17e84bd11c54e9b433600bd95d712f59840.nq.gz
│   ├── dae7f2f448da625827799506b163b0c310328bcc.nq.gz
│   ├── db4456225ced666a13110e63d2f766c522c23914.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb31892bae25c54c1759b1c687658ebf8bd8f747.nq.gz
│   └── fe76f6c2b3174b4982bfd6c1bf1eb7ab6a26fc69.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── bf9632c78355b545126363ce557106c1b9c3bb54.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 49 files
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

[scrapinghub/scrapinghub-entrypoint-scrapy](https://github.com/scrapinghub/scrapinghub-entrypoint-scrapy)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
