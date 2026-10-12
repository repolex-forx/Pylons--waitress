# Repolex Knowledge Graph of Pylons/waitress

RDF knowledge graph data for [Pylons/waitress](https://github.com/Pylons/waitress), parsed by [repolex](https://repolex.ai).

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
rlex download Pylons/waitress
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2b43237e9caa66f906d0f652f2519cc79ef969a5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2b43237e9caa66f906d0f652f2519cc79ef969a5
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ff2878747881de28691d83a35d2bd7bb7270e0.nq.gz
│   ├── 09d56c95e5f12fcb3dbad0662d818baae4f949ad.nq.gz
│   ├── 122d79e89581e4bda1b2066af46f4972c62d1347.nq.gz
│   ├── 146736ff81600e05e8197ff26f0010f9c88ad2cd.nq.gz
│   ├── 1c428cbff5a04b91443150d1e2f9493ec6e8f8a4.nq.gz
│   ├── 1d66ad1ccace7774ab24b91862bc0444b0787b33.nq.gz
│   ├── 1f7addd601016148c74b7df31a8af71f85b11abc.nq.gz
│   ├── 213930e9350b45a4e0d677b7c9bc970b4f1f240e.nq.gz
│   ├── 218fdb215098265bcb749fe4dd223eb4c23d33be.nq.gz
│   ├── 24067de4193e6dd68cfb8719c129ebb0cf36acb1.nq.gz
│   ├── 24e4cbf6712083ede8dc0de5042b83ca254f6228.nq.gz
│   ├── 278ab538152915f1c441fba356b4ab3ef8a5fb31.nq.gz
│   ├── 2d171d8bead3d670e233c13c4c56b6e0947f695c.nq.gz
│   ├── 32abfcb5a024b2edca7914c895982c87941c6798.nq.gz
│   ├── 3da64c38fc75fc8d1678d2607760350889ec0c99.nq.gz
│   ├── 3f8dee99dbbe7bf1ce9449b6eae540fb7bd9d3e9.nq.gz
│   ├── 40b7685da6091765f35432835d1477cd7fbffa72.nq.gz
│   ├── 4af3dd97c79d23577fa40a5a658fccebfec1ceef.nq.gz
│   ├── 4e61ad39deeceb0f61bcdcd32236419c03fd7cda.nq.gz
│   ├── 5309845046bdd20d8e8fa0ccae85959335cec974.nq.gz
│   ├── 5579ce52b70004d77ca866a3cbd9e55138aa66c8.nq.gz
│   ├── 55d993c3261c9e92fb060eaacda3b5bd628ecf19.nq.gz
│   ├── 5737055179c779b424f85fe92776d847c5e82905.nq.gz
│   ├── 58b5c2e1d5d29af0f9165ae70d7a23ca5e4d2596.nq.gz
│   ├── 5afb1c5425361c50aa9dd7d72e9628da93802380.nq.gz
│   ├── 63483a31f4a18965fc9d3298e32ebded875856e2.nq.gz
│   ├── 6391e0eef4c639fac0beccaa05dbe009e1fc5190.nq.gz
│   ├── 6490e3d7f3df30ed55c300cc86b7f7aec60316bc.nq.gz
│   ├── 67543b9cadd17243be50c2e4f04745394aef56d0.nq.gz
│   ├── 69af84607492ab5500d61b76a04c89136e3d0fa3.nq.gz
│   ├── 73ac31c31e2744b0994107713a7529152e1b1516.nq.gz
│   ├── 79859e06010bf4967c5b4b044afea6ef39742938.nq.gz
│   ├── 799b75d6aec9ce24b7ab6299e942a48d09b14acb.nq.gz
│   ├── 8191cde1319feeb3118f611c3800f8b2fe858643.nq.gz
│   ├── 8497562107e6172dc377c7f4a124fdb24b141605.nq.gz
│   ├── 86bf5ded87f732b71a08901a8ea6b3d22186dfc4.nq.gz
│   ├── 8948422c5749b90b97ee8dde1625196bb051f26f.nq.gz
│   ├── 8b26eb87c2f2d2c64c9e37c098d48ce60d976e5a.nq.gz
│   ├── 8be487f9f73f20c00ac9a990030903779ea63966.nq.gz
│   ├── 90f610ea01d69dbc11181bce27aaaa3526b67f22.nq.gz
│   ├── 96420fe271e32c8ee754bc2b92b359dac3702d9c.nq.gz
│   ├── 97f9a5c3dfe1dafa5b16aacc48a8f807491a8d6d.nq.gz
│   ├── 9a2b143502f9a19adf05650db6339c8a9200872c.nq.gz
│   ├── 9bcd07e59cbb4eabc41561785a0e1ca6a3e2a33e.nq.gz
│   ├── a0f36d2cc4bf31b25e3203eb77115b50652830a1.nq.gz
│   ├── a5f3a73f0e9331aaf129377a27ed2da23fc64a51.nq.gz
│   ├── aba6b5973bbb7681b7fed7a1dcb1e9c8af7485d8.nq.gz
│   ├── ad56c4dd5d514b6fa02c52ebab45a8698af7b486.nq.gz
│   ├── ae94e4cd7a412bc6f854e8228844f52e8d81627a.nq.gz
│   ├── af8dfa4a018754e30ad5ead086fa459211ff0f85.nq.gz
│   ├── b0f0c58484dec257a22b222b23343c0c4ade9bff.nq.gz
│   ├── b2657706548f7faa867ef549be521a9517db2098.nq.gz
│   ├── b711d3609fdefd7664f2982d225d96f5e53be9c0.nq.gz
│   ├── b86909758def8056543dd26da922c1e5ac9b6e1f.nq.gz
│   ├── b8a856aa7e1b6ae8e3d643bc545d8c649640e953.nq.gz
│   ├── b8ab829a5ca9cf3b168bec99395aeb8d30cde9b3.nq.gz
│   ├── bb1b1f510945706e7b14d0d34e40f68f14941d79.nq.gz
│   ├── bb5b39c4bbb6e76317adcfa875c88e5f782e1817.nq.gz
│   ├── bbb99da0307e42a90207077f02cee485e8e255c3.nq.gz
│   ├── bcd18e0d50e31d76a0a739a241a29a26555fb0d1.nq.gz
│   ├── bda3ae506b4a506d5f2205f4bd2e99319a6d6a89.nq.gz
│   ├── c03da8a77d42eca35f5f28e6700f0b7f8dbd3bb2.nq.gz
│   ├── c0d13eff1f83beae0a6ef060dd1ca53f87040a22.nq.gz
│   ├── c56530a06e135a862dc2d1a637a28b73a2fd4723.nq.gz
│   ├── cd119877198b3763d8c6f5fe2c37a5e13a7c7cd1.nq.gz
│   ├── cede49a7d41afc7e6585bfb4cf77bf88715c216b.nq.gz
│   ├── d128d969e9779256529b4e3ba017d63fb52d871a.nq.gz
│   ├── d138fdd85459277dcfce5430aab6bd1dbc1f584a.nq.gz
│   ├── d614798ed5b5519eee7b01527c8ec0026fa9caef.nq.gz
│   ├── dd0b78b882792315d65d4c2780858ca15d17eea6.nq.gz
│   ├── e0f953e2c6b6da6feb9d7c6d4482cef445045116.nq.gz
│   ├── e1d2792e65bae8b941167bb5bb35e960c2ad98e6.nq.gz
│   ├── e1f9ad7b3b48377bfbfaa1b380c384ddea24060f.nq.gz
│   ├── e682046b383ce93f67925408ee6068e317b9949b.nq.gz
│   ├── f215a2b9079b7598a84097bb9e609fb647304038.nq.gz
│   ├── f4a465984b447c6aa009358af92fb91f13a296b1.nq.gz
│   ├── f4af227029ba97f72f545b5ac817462678b966d4.nq.gz
│   ├── f57a8b2380b55bfaaa1ae4007af5f4688771a072.nq.gz
│   └── fff896a4501f5c125aa247d7817c0cf30429df3a.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2b43237e9caa66f906d0f652f2519cc79ef969a5.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 87 files
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

[Pylons/waitress](https://github.com/Pylons/waitress)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
