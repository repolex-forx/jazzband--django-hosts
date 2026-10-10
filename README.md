# Repolex Knowledge Graph of jazzband/django-hosts

RDF knowledge graph data for [jazzband/django-hosts](https://github.com/jazzband/django-hosts), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-hosts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ef571d4d39319872532b530b33dc781a45d70a35
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ef571d4d39319872532b530b33dc781a45d70a35
│           └── chunk-001.nq.gz
├── blob
│   ├── 0396da7c39817a50a9da1a8c5bb83bd4685d5879.nq.gz
│   ├── 074c080b05a1e3b0490bc2e5d329e23fe89a0574.nq.gz
│   ├── 08f0958a1b559e2cd038bf34f6fd64e65bc74dd3.nq.gz
│   ├── 0a14bacb2854541b923ba8d61767c1f81e069517.nq.gz
│   ├── 0ac2d272ed3d1da7b7e227dacd4aa7d8446be0e7.nq.gz
│   ├── 0d257f145ffc5093d244d62d0a5c5821e9cb9d04.nq.gz
│   ├── 11d33eb0a8c334f88b63d9936eeddc2dada0dc51.nq.gz
│   ├── 12ce3fcf6cf0eab35c1a1c787cd7b93d601ead6c.nq.gz
│   ├── 16b25405e9930108fa6183de06ab3402c781f682.nq.gz
│   ├── 17ee2be74bf1a59545273633a7daf726ff077737.nq.gz
│   ├── 1b472bb6fbe1d22cd340eb500ce47e92e6578b8d.nq.gz
│   ├── 1d46fefad6e3faa25537d6d706cbf3f7a32d3632.nq.gz
│   ├── 27a1e43f03de3539dab04722f6a1c2f07c935a7b.nq.gz
│   ├── 2fc05d22504e28f7dcd9fdbe25fd110a0460eb6a.nq.gz
│   ├── 2fe0b17a924aa0253331c34b8ee7381226eafc15.nq.gz
│   ├── 37894918b4251f766b7d1edf59efa0d25e71c6e6.nq.gz
│   ├── 423cdee36673f58ce731c9805aa55ae411310b82.nq.gz
│   ├── 4c9eb0822c94862f2e5938fa163969da8dd82c66.nq.gz
│   ├── 4e037899bf9e706948e50d1be795128c6a4fff6d.nq.gz
│   ├── 57756b4775164cb979f92c1f7514344a0dea8315.nq.gz
│   ├── 5ccbb569426861241b9b0cd66721753c9bdfaf22.nq.gz
│   ├── 5d80c14b167dc3f17e95a6eba3743d7af29b525d.nq.gz
│   ├── 637600f58aa4445293fcc008d547253d34470ffe.nq.gz
│   ├── 6453aa175c0affff6d29d77533052aee1ab14088.nq.gz
│   ├── 6537bb609fa82c7ffc9ef58abed8d991c62fb9c4.nq.gz
│   ├── 68542c9029f9882e8219fa97cb1e3daad2a78265.nq.gz
│   ├── 748642415f10da88752ae825259fc622e65607fc.nq.gz
│   ├── 75e4ac64bd595829bb49b0d3294aae49ab71ec1b.nq.gz
│   ├── 7a9732e0285d3b84b0f6aba565f37367870ef088.nq.gz
│   ├── 86886491ee494a7e9c4fc778a44860add5e54ab2.nq.gz
│   ├── 8e7dccf675d83adfb9b3d39e648378d6c6c3ee44.nq.gz
│   ├── 91b3d823dbc68c08a6b17e4ff62db02846c4512b.nq.gz
│   ├── 96af1fdf9d11c3121aa265caf6690952a639545a.nq.gz
│   ├── 9b9a4c82c840013671799a783017b8e84630fda8.nq.gz
│   ├── a1924a04fafc374a874efaa8c1b695139820d2da.nq.gz
│   ├── a6239337c55d6cd9e5d5be129cc000d17e34b268.nq.gz
│   ├── a67363ca0cf73304c153fa2aaa06e03c0f75f425.nq.gz
│   ├── b4de9b4e0dadcf9052f77a7d7d8bdd804b2c5f4e.nq.gz
│   ├── b8046de32b35aba8686d03db8e9aea481d648add.nq.gz
│   ├── b90eeafc6b25a356eb339f809a455de290fb5f2e.nq.gz
│   ├── bdce373943a6daa03cfd5f880e89c2f3bd97c439.nq.gz
│   ├── bfa119869d65e11a757d4734991accb03d88025a.nq.gz
│   ├── bfe5c659fca0f4dfe655f14e9263b516cff54dec.nq.gz
│   ├── c0ea47a7672bbe4219f99217b42a9e1f04c15360.nq.gz
│   ├── c6b2443338b50ae613611749256fca8229542dd2.nq.gz
│   ├── cddf31e84401bbe5e38e22bdf7fdca9f891282c2.nq.gz
│   ├── ce9e6deaaf0a8899b9572bb53f246cee7fe51682.nq.gz
│   ├── d03e74c7d1af097a27c2626eeec26f40fc725a38.nq.gz
│   ├── d230d1eae022794651ab100068a6ccba0d0aa389.nq.gz
│   ├── d37793a0c98729cc7fb9022505d54200c056011d.nq.gz
│   ├── d5d8269e9f4be5b45981e70493e177406a6cded8.nq.gz
│   ├── d75a08897d2254f6ccbe380b3ee0397a5aa0efbb.nq.gz
│   ├── da37fce07cebe755c32df54402ef495b89c7d137.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea51e13076c2d2d03eafd5a5df009ee48da834c1.nq.gz
│   ├── f088d05f84d26d85b9c69560392152a4abc22c57.nq.gz
│   ├── f0dd4ab48a1b945db80c32553ddb0278bbbf1513.nq.gz
│   ├── f1bff76fff5ee3ee1f885c669f1d34f23d62ec16.nq.gz
│   └── ffdddebc1d7ebc9aea056df1d6b3f93a26f532a9.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ef571d4d39319872532b530b33dc781a45d70a35.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 68 files
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

[jazzband/django-hosts](https://github.com/jazzband/django-hosts)

---
*Parsed on 2026-10-10 by [repolex](https://repolex.ai)*
