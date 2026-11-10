# Repolex Knowledge Graph of postcss/postcss-selector-parser

RDF knowledge graph data for [postcss/postcss-selector-parser](https://github.com/postcss/postcss-selector-parser), parsed by [repolex](https://repolex.ai).

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
rlex download postcss/postcss-selector-parser
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7591d8d67f42fde79490d5e9c8fac0b8deb43fa2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7591d8d67f42fde79490d5e9c8fac0b8deb43fa2
│           └── chunk-001.nq.gz
├── blob
│   ├── 01ed4244dd86481f6097e5508153814e4072b9e8.nq.gz
│   ├── 054f0a84aa85e1ef6fadfb4741e1a7b18e772550.nq.gz
│   ├── 0f2f3ee970902f4f71b0611998ddffd8baa03da5.nq.gz
│   ├── 0fc0a58f1fc915fde473bc23e345579063397433.nq.gz
│   ├── 191a3eef78e84d47c39c7b84234be953b9fcd392.nq.gz
│   ├── 23845d841a5d377bc50cbb8549787a776a90a67e.nq.gz
│   ├── 24d35be18ac6deca27443465ece0ede20205740b.nq.gz
│   ├── 24dea50cca0cda75af1a5d340676e5d886ee6aa6.nq.gz
│   ├── 2677b900bf425afdd2a7bcb6b643ae754bc568c8.nq.gz
│   ├── 2ff21ec65e57765b168fad23bd56b45092894ec3.nq.gz
│   ├── 358382af1f924a6b3aacbd421dcce6f5d97f2b6f.nq.gz
│   ├── 36e136761930ca5b0f6514dd6d5710d9b18fe82a.nq.gz
│   ├── 377bdd2bbbf92fb803222698627ef6f38ce45add.nq.gz
│   ├── 378076c0c65af29b0b470815fc6c49a4ae3e4b5c.nq.gz
│   ├── 38261fcb4e49ef932c66ea7889b4e31e781ce933.nq.gz
│   ├── 3842064915639e53309157795752d3930be7fe89.nq.gz
│   ├── 3c21f641220bbc144d6d0711977441db86dc8f69.nq.gz
│   ├── 3cf3e180d45a531fffc0387814c78ff4813d5686.nq.gz
│   ├── 3dcfa8e0543f64c6756baedf9a1a9124ab45f0cb.nq.gz
│   ├── 3ead45c5c02d063e12f42fab0c99fd0fc178c554.nq.gz
│   ├── 3ffef11b531caaf64a86fed52307ae099bbbf374.nq.gz
│   ├── 46ceb1a9df850bbd7d88300eb720cfc7d07f710d.nq.gz
│   ├── 49cef40a63e2c4f23dc6f6502a320c0746820694.nq.gz
│   ├── 5fde4153ea7d0a6a19675d097619524b36750e76.nq.gz
│   ├── 679bd15d44b61199134046b73046ba5c10e6030f.nq.gz
│   ├── 70f75b3f5f2b7d188e43f09ec343469a7644ccd8.nq.gz
│   ├── 7363c60e702a07e449dfdab26c9aa0471354062b.nq.gz
│   ├── 74b0272d1c37460d508015e24eba834642020094.nq.gz
│   ├── 7567bbf9c065e3776309ef49a31813555af53b54.nq.gz
│   ├── 781b3624339a30cce9cdf6223ecde271f95e137d.nq.gz
│   ├── 785de2f73ce1cc81707f2457ba59768037915965.nq.gz
│   ├── 7bcbd55454b91f06442dd875c180dda31f031eea.nq.gz
│   ├── 7ce8bcbab2127eb01c8a5805dfe2a4baec23e64f.nq.gz
│   ├── 7d533a60a19b8a3cb1c6e7bb9ded81ef20e77f24.nq.gz
│   ├── 7ea5e03c591488c7a18151d0756969f6b16f1774.nq.gz
│   ├── 7fb6c2d8cf145660337f981b2965bee9cd09f70e.nq.gz
│   ├── 8071a8c8727e9ee4d7c025a3762669096578d675.nq.gz
│   ├── 81e13f413980a89f2307f4d77b93d7a7cc366926.nq.gz
│   ├── 84951177f485570059f271b3556d06059d1e8b16.nq.gz
│   ├── 85f8f1394e7f59814a53828aa04b754af75e43ad.nq.gz
│   ├── 866f6d2b103247d971522ef866827915d1aacc32.nq.gz
│   ├── 8c76abdd9090c3834052e0abb8d8d024c5b9e118.nq.gz
│   ├── 916458db41844de1151f9f4e2a0983b51233296f.nq.gz
│   ├── 946b2a73596a54961228b0057bcad962312d44fa.nq.gz
│   ├── 95081c45b3b3ea3a9509e30ca02b1b46e9128948.nq.gz
│   ├── 98a42a762319f3bd2f1f8c514535f31af80ce0bd.nq.gz
│   ├── 998e672f058af50cb90e6473dfa86611dfe3fbd0.nq.gz
│   ├── 99c0a1be2719015fd74c7bd0c139ede9366604b9.nq.gz
│   ├── a06c4dd924c9bb8f2db3d33807db37f678ada0d3.nq.gz
│   ├── a33b2f03696a331eba45ad86bc3ad40f3bc33219.nq.gz
│   ├── a38dc58ddf03805cf85bb3d840172a55f8a42b34.nq.gz
│   ├── a9edd7b0653adc7e6ad0cd7ed89720d4a0e9d69c.nq.gz
│   ├── bd0720b1817f14f4364b55f921200182ad100034.nq.gz
│   ├── c23f50152cca72850ca8b0869c25966e30ee83e0.nq.gz
│   ├── cd1484b70d9d1495fc307530cc60f0479f0e8b93.nq.gz
│   ├── cda86457b8b0319621df2f5506f89b143abe3310.nq.gz
│   ├── d12a5fd5867a997ec041c74091f126bdb9d4f165.nq.gz
│   ├── d401717a0584d13e250765cc657e1b68052d6d5c.nq.gz
│   ├── d64c20934813d3696c65ac8c5dcc73cf678bf0d7.nq.gz
│   ├── d719901e91a5969c64c43157a85c47ec9fc39e0d.nq.gz
│   ├── dc1cfec70f47ee1a151d89071da5ae08b30334b6.nq.gz
│   ├── df346f047d58bb06db710a2b0e508f27b95a51ed.nq.gz
│   ├── df38941cebe136c7da33faf65b886cce5d4802be.nq.gz
│   ├── e5889a6d2a96e0ea13447154981e9bc2ea1514a2.nq.gz
│   ├── e679d3187762a505b8b3f5acf8e4af77740277bd.nq.gz
│   ├── eaeb74348f484314ee186f5e9a889c07ab76d179.nq.gz
│   ├── ec6d27b9a99de937859ba2e7f173831ae9de3af9.nq.gz
│   ├── ef991c125662469b875c0b957b430174ff072afe.nq.gz
│   ├── efd1a4bc0cd014d0251b066a1cbcdbcdf570f433.nq.gz
│   ├── f1a8ba0282d2273cb48d6fac1da9a6c02de9d47f.nq.gz
│   ├── f9e74855b3d7dbcc3027fd6e2f0443c226c54077.nq.gz
│   └── fd0e863a614fbcfc11bcfd0836975d1f5bfeb191.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 7591d8d67f42fde79490d5e9c8fac0b8deb43fa2.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 80 files
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

[postcss/postcss-selector-parser](https://github.com/postcss/postcss-selector-parser)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
