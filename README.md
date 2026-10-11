# Repolex Knowledge Graph of pallets-eco/flask-security-3.0

RDF knowledge graph data for [pallets-eco/flask-security-3.0](https://github.com/pallets-eco/flask-security-3.0), parsed by [repolex](https://repolex.ai).

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
rlex download pallets-eco/flask-security-3.0
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b091e7d513301d547a084ad60ae174d89eb89653
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b091e7d513301d547a084ad60ae174d89eb89653
│           └── chunk-001.nq.gz
├── blob
│   ├── 00596cb61f67bc9688753a1d0bd24c7cb2f0af50.nq.gz
│   ├── 016379455b2ae9949e07e5c1aa9b8ff89f10ea20.nq.gz
│   ├── 03c171dad2320bd3ffa7b52c10506bb8c3689c32.nq.gz
│   ├── 043bd958bce2570a06affd36eab5196dd01f65db.nq.gz
│   ├── 0aae4f0ed651fc991eb432b589fb6a899f11651b.nq.gz
│   ├── 0e9ba4545984b2d5253c06527e40fe96d12d45af.nq.gz
│   ├── 15b232a4779695cd650eca22afb4f397e561e4d2.nq.gz
│   ├── 16f61b2caa9e498baada75cddef6dae1f6fc0d4d.nq.gz
│   ├── 1942ebe2953805a2529d17cd00eaeefc73e285d2.nq.gz
│   ├── 19a1962d598b724a540efa2d887588ba2dcde948.nq.gz
│   ├── 1a9bc9ef22926554edf33e1dc8ca40f08a4b5c84.nq.gz
│   ├── 22fa32e7485199396270d3b7f05692efdd94bc1c.nq.gz
│   ├── 24e585d459c2b42bb423bd9f4abab7875cca6ae9.nq.gz
│   ├── 25807fbf32998312ea6b074abb7727237cbd727b.nq.gz
│   ├── 2799f1fcded03591e36e36922a0678cc63c2d5b4.nq.gz
│   ├── 2982f100d04a0c6ad74b0914abf12267cd7fbda2.nq.gz
│   ├── 29a5b5cf7e2ea6d2b93884b936201c8073fc9729.nq.gz
│   ├── 2a012b41bea108721eede2a5d06c9bdd0a5b2f6f.nq.gz
│   ├── 2b1a4f0b9c203602ddb36d0d6ba3939d49e86e11.nq.gz
│   ├── 34a7735f89a845635b690491d551f46ff6eebee8.nq.gz
│   ├── 37dea00481ca9a112724363f9a5d112bd27482c8.nq.gz
│   ├── 3b215edc8c4079dce346d9836b07847dfa148019.nq.gz
│   ├── 3c0f11a963a56e682f046c70fdc00f327a02bf25.nq.gz
│   ├── 415bc3ee4a55052ed6d150fd08ca557f9c907412.nq.gz
│   ├── 450c1c2bb2290604ed7eaf07ab605e6b4dcb34bf.nq.gz
│   ├── 466b979fdf7b9c1c38dd41959f3340e15e2fddb8.nq.gz
│   ├── 46786cf6e978d4110ebb132582045f3623522c58.nq.gz
│   ├── 4f00e4fb566eaf310ecf7a6207d006c450a4a488.nq.gz
│   ├── 533828e1f6101bec04a01d86b2d0a8fdac02f64a.nq.gz
│   ├── 53fdf1b2ebf8d78287a7b2fc1afb2c3c7f7ee0ac.nq.gz
│   ├── 585908fa532beb5532ce99f8a6a9ff986f9e2a48.nq.gz
│   ├── 597aa00e66f7bab1d86619f2da972d198642cf99.nq.gz
│   ├── 5b6f3d8dc28a14e4b542a5154c9ee1a537893acc.nq.gz
│   ├── 5e974ac0e13ecb264be12429c02501687dbd46ff.nq.gz
│   ├── 63c72b3ed023eb04b9cbb7918101c92a9c6d212c.nq.gz
│   ├── 641ce3986c91a88b8b4764da8e7093c97b3a2096.nq.gz
│   ├── 64f71f5b81934814c9b0140ae75514889267751e.nq.gz
│   ├── 724fd06c3e00b655487ca55746503a6b284b3874.nq.gz
│   ├── 7f25544b8a484640491382e7e3973aa6f478c995.nq.gz
│   ├── 80a8dd4f21dab1901f6512e69c0b3ea06e4a4473.nq.gz
│   ├── 81dc6fce7539126330aa629c23f43450b7bf2cd0.nq.gz
│   ├── 89482f45841dfeff0cc48b0c3732a4c8e45ddc9c.nq.gz
│   ├── 8a05a51e8698babbed33230457f17c9073042d81.nq.gz
│   ├── 8b942d4d6bc525d801730a635bb75d92977d4e55.nq.gz
│   ├── 8eecacd39ae2b618a781eb723d61cc27409613b9.nq.gz
│   ├── 9bbf6e9677ecbb59db2983de6ad83023fb7ece7c.nq.gz
│   ├── 9bdd9cd7d588c428cf4f331bf54be999bf99ba50.nq.gz
│   ├── 9eb059ad0dbb98c1ea3ad405a11e6cd48592f898.nq.gz
│   ├── 9ff5f8dd9881be34f7a0f9cde1dfc23d945cb1c5.nq.gz
│   ├── a23c64106d197a49bfd5db07af6a9180f6178905.nq.gz
│   ├── a6df14677160a9838f5867f22c5c3d203c6efb55.nq.gz
│   ├── abcee3a556dfe55bedbf232865c0f5cf6ba70bf1.nq.gz
│   ├── ac93bc189f8b27fee90ab1340f1a8c5b67d516d3.nq.gz
│   ├── acf0994fc38f9e663831c6b619ac06091e9570c5.nq.gz
│   ├── b0e7523b737453392058c9797243c790a2f5f226.nq.gz
│   ├── b202ad33931768269b2b027f3c91df02855324cd.nq.gz
│   ├── b272639336275b3ba603e26764c5f1d5ad9d56bc.nq.gz
│   ├── b4904186195d7f503f77204537f398dd108be6bd.nq.gz
│   ├── b519a882d5cbd636e61aa3845b332e355795970f.nq.gz
│   ├── b5c454c6bb789ca0c79924e5eb50ed539365aa2e.nq.gz
│   ├── b9d3f8c6e71c6426245d0463b73d42224d372e1c.nq.gz
│   ├── ba53d74754b384f9177486c7aac17a420652f761.nq.gz
│   ├── bc72984fa39c798eef6e6e893f015ae505112e34.nq.gz
│   ├── c0377911b9dfdaf0cd2a7d20941cc0dd1be28d57.nq.gz
│   ├── c1cb8114c02643a5d10c87029f723fa1932708a3.nq.gz
│   ├── c29da5d2c338dc615a0b98decdd6c2ba7b0d83c1.nq.gz
│   ├── c56174e759a80c166baef9d05c872fdb6c301485.nq.gz
│   ├── c8109eb81ce69315b64f9a50d0aab0ad0881c3e0.nq.gz
│   ├── ce653c86d6da830c1e29b8d7d02bde67c490a6fc.nq.gz
│   ├── d503d1012ecf6d79f081426a6020d3217635fad5.nq.gz
│   ├── d6d96033613d28ddbc035ffcb73190c4548d9e9e.nq.gz
│   ├── d6fed98756ca089de8a7baac11dd29e1aaa98973.nq.gz
│   ├── d9c125a359a44042aca4402058423b1a08420155.nq.gz
│   ├── da931476f4d14c68cf25de6e04610eba5c074094.nq.gz
│   ├── e35d8850c9688b1ce82711694692cc574a799396.nq.gz
│   ├── ec2edf346cb1ebec8d90b96e60bbcb9a9c4a3524.nq.gz
│   ├── ec5265c608bcf660d74a33225c2bd365e9ea6b34.nq.gz
│   ├── f07d213b415a7241058542729b1d1f224b2fb80f.nq.gz
│   ├── f6025beabd0c4e4bf41a2936a021a70f3b6cbf57.nq.gz
│   ├── f783ca2a79dead4ddefe6a398e9f3e8eae97384f.nq.gz
│   └── fb84d726737a99ccce4a2b8b55ba1132082e7a79.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b091e7d513301d547a084ad60ae174d89eb89653.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 89 files
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

[pallets-eco/flask-security-3.0](https://github.com/pallets-eco/flask-security-3.0)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
