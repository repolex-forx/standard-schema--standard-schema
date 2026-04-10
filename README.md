# Repolex Knowledge Graph of standard-schema/standard-schema

RDF knowledge graph data for [standard-schema/standard-schema](https://github.com/standard-schema/standard-schema), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [lexq](https://github.com/repolex-ai/lexq) query tool using [uv](https://docs.astral.sh/uv/getting-started/installation/).

If you have uv installed, just copy/paste this into your terminal:

```bash
uv tool install git+https://github.com/repolex-ai/lexq
```

This installs lexq onto your system, in your user context. Verify the install:

```bash
lexq --help
```

**lexq is designed to be used primarily by LLMs in a terminal.** Start up your favorite LLM and ask it to use the lexq tool. It's that easy!

To load this repo's data:

```bash
lexq download standard-schema/standard-schema
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2c4e37f6d92e7ddc1d0d0b6bab4173f1d8d41df1
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 2c4e37f6d92e7ddc1d0d0b6bab4173f1d8d41df1.nq.gz
│   └── repolex
│       └── 2c4e37f6d92e7ddc1d0d0b6bab4173f1d8d41df1
│           └── chunk-001.nq.gz
├── blob
│   ├── 004145cddf3f9db91b57b9cb596683c8eb420862.nq.gz
│   ├── 0595f511bfea0f1692ad981d5307674bf81a3891.nq.gz
│   ├── 0997ac90e4c814f22181387a907e147106bd9741.nq.gz
│   ├── 0cd9bf6bf3e0a66844bab64004235fdab86fdf04.nq.gz
│   ├── 18a6d1b0f808144b33ae74da08b506970eeeab1d.nq.gz
│   ├── 18ec407efca710b5d0d1e19dd3e34a27ac6716a1.nq.gz
│   ├── 1939467afb8d44b0e03bb386a3b0738f177f22de.nq.gz
│   ├── 1a69fd2a450afc3bf47e08b22c149190df0ffdb4.nq.gz
│   ├── 1a8e4da904990bd459815a020b19b7e71f327249.nq.gz
│   ├── 1c4b1a6fc6c79c1958c5d442392a8e252f445f9c.nq.gz
│   ├── 262c4c7514d97fd8aa225e36db74a4f1fc9a3c42.nq.gz
│   ├── 2804c73f06f39475fd2c5e8853ce4e9aad23565e.nq.gz
│   ├── 30004b0ffaae9a70449ee817424c6bdbfb91671f.nq.gz
│   ├── 369c5d43f4cf44abbb19d9fad5ae11cb772aad22.nq.gz
│   ├── 383ae19a1a0a6cd2583b302e139c103f05e0d890.nq.gz
│   ├── 3a619724162dec68ffad5a1c554f71206df1c57d.nq.gz
│   ├── 3c2c7621ea58f4c722140a9e32587dcead2f81d6.nq.gz
│   ├── 3dc06df209203b2051ebb398ca4c8c70c35eabc0.nq.gz
│   ├── 3e9d6d32a84c5edf8ee3c8cdf813e3c16fcd0a32.nq.gz
│   ├── 3fa477fddb72c314c3ee92f2705c7167888ad640.nq.gz
│   ├── 40e527b122b2be09021eaed2583a8b728148f1ab.nq.gz
│   ├── 41583e36ca8d2eaf61c855a0500988bb163adc2a.nq.gz
│   ├── 460682842adef8dc6179d7646d0498f31548be68.nq.gz
│   ├── 4749c4b343866b9555047d710a719b42c56d5de6.nq.gz
│   ├── 4a25585c75c3cd821132265299d0cd5b8a56ac07.nq.gz
│   ├── 50a1cad0e6b9914eea4bdf39f157b045f4c9313d.nq.gz
│   ├── 5174b28c565c285e3e312ec5178be64fbeca8398.nq.gz
│   ├── 533bb82359eecd496c90476f82234c8ebf69ab29.nq.gz
│   ├── 567f17b0d7c7fb662c16d4357dd74830caf2dccb.nq.gz
│   ├── 5ef6a520780202a1d6addd833d800ccb1ecac0bb.nq.gz
│   ├── 65d4fcd9ca74240125c5f72cf84c873781141fea.nq.gz
│   ├── 69a2f588dc912b89bccab45dfb2aa248454b3dbc.nq.gz
│   ├── 69a4721a15d97f4b38e7fa69abefc230e202469e.nq.gz
│   ├── 6bd1dcc8be567e56b06f2245b001b0bda9b2a4e5.nq.gz
│   ├── 7395e9a3baf5af46553168efbffca8b69ddcfdf2.nq.gz
│   ├── 753e38ccb4d9111852b8dc49228a0d2eaf49ef6a.nq.gz
│   ├── 77053960334e2e34dc584dea8019925c3b4ccca9.nq.gz
│   ├── 792a93874fcc6cf9f3c322b939f3b42f35e2d2f6.nq.gz
│   ├── 8724769c1a76b6ef434d78eab49f1b3768c675ce.nq.gz
│   ├── 8b6bb3150a8cc83295f51c1768a4d6c0e3b803a8.nq.gz
│   ├── 90133f64ca348c1241832f9be521ad75d454eb35.nq.gz
│   ├── 9298a2b414723b9d20b2adea43225e9126301981.nq.gz
│   ├── 95ef9364656b16d87fbffbebd40faabef40b12c5.nq.gz
│   ├── 9f47d8bfe347663521698318bea1f1a8986837ef.nq.gz
│   ├── a7b12df0a056d38aa512066d81123214c6b7f8ca.nq.gz
│   ├── a8ab7cff79b8ae8fb14c55f56872f302b4c19b71.nq.gz
│   ├── aa1227391d2ff90eb508963fc74c4d856c249135.nq.gz
│   ├── af2ee6d75ec7f0ebf0b3dcecc118b5fc67c52bdd.nq.gz
│   ├── b2b2a44f6ebc70c450043c05a002e7a93ba5d651.nq.gz
│   ├── b3572bbcc1a57e9354b4f4c95baa44a016640bc6.nq.gz
│   ├── b3acdcbad319fde4ec1f2a8f3ae9ad6e5ce93163.nq.gz
│   ├── b55670c3e0b15032343fcca870110b1698a674c9.nq.gz
│   ├── b5f14543870f0bdc1b4d4583490308cb7d359d70.nq.gz
│   ├── bb0b8dac824e8ba94389e26fd0acbe3e8db495b3.nq.gz
│   ├── bde87bba33c04bb775c2be0e921c4a7a34885bbc.nq.gz
│   ├── be674a28a2ebe675d81a95b15d160fed09456e00.nq.gz
│   ├── beb58d60a61409069876719ba61f5602bc11be65.nq.gz
│   ├── c0fa04147236c99ee2ae0d01f840516dcc179795.nq.gz
│   ├── c37c7d8bfedd5c7983946ec4e1c39c7722a34122.nq.gz
│   ├── c691a1416ed0c7398e4c6dc78d178ee63524e609.nq.gz
│   ├── c9bc213caeaf3d2bdcad96e9ff725fa07cd38fa9.nq.gz
│   ├── cc2a097ae3a48b3b1319fd6f7e1420e8f758cb12.nq.gz
│   ├── d1de7be7976903b8b5a15a714018494c20d323ce.nq.gz
│   ├── d1e0f076f1daf978bc944acc2ee9ff5a2b903945.nq.gz
│   ├── d2cf3e00820a6412ddc59f3440030248cf289409.nq.gz
│   ├── d8e9b839629032a8ac48db19e4de89afa174c980.nq.gz
│   ├── daefe93706efca8ca14bce7c736e02d18854fe43.nq.gz
│   ├── df0b3794ed92fd262d45f7df4da8bce0eb82161c.nq.gz
│   ├── e1396825052d424cab330b690a505b70c8a1c6ba.nq.gz
│   ├── e215bc4ccf138bbc38ad58ad57e92135484b3c0f.nq.gz
│   ├── e363f3ecf9f80dd2797a2a1bd0efde3e63dd2fe0.nq.gz
│   ├── e6d819ae17bf027b01646bf1b745df47dd7bf619.nq.gz
│   ├── ea54e0ddad405b2ee635d687a876613214160ba2.nq.gz
│   ├── ecee3bce346b513f40769aae23c88bbca17d8f85.nq.gz
│   ├── f33f29a80c4eba8795323ae9ffe6d058945eec4d.nq.gz
│   ├── f5b76f3927bc663341a409fb8d10a33b02ac1405.nq.gz
│   ├── f5e021a3a0fe064d4e8b8d979466848ac4c44b6b.nq.gz
│   ├── f9813ffa878e7914dc2928ab13db856850e8d83e.nq.gz
│   ├── faf9813ecfe837fba4dc66ebf8a28612d809d0a0.nq.gz
│   └── ff1e75567589fae5c97ad7aadaa6319a99f5288d.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 2c4e37f6d92e7ddc1d0d0b6bab4173f1d8d41df1.nq.gz
├── filetree
│   └── 2c4e37f6d92e7ddc1d0d0b6bab4173f1d8d41df1.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 90 files
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

## Source repository

[standard-schema/standard-schema](https://github.com/standard-schema/standard-schema)

---
*Parsed on 2026-04-10 by [repolex](https://repolex.ai)*
