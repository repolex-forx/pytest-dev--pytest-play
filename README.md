# Repolex Knowledge Graph of pytest-dev/pytest-play

RDF knowledge graph data for [pytest-dev/pytest-play](https://github.com/pytest-dev/pytest-play), parsed by [repolex](https://repolex.ai).

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
rlex download pytest-dev/pytest-play
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c39a1a7e74d90aebeb30797a61d0e491942557e8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c39a1a7e74d90aebeb30797a61d0e491942557e8
│           └── chunk-001.nq.gz
├── blob
│   ├── 05fc3944ca3cd285e03e7665d08eda76d56d7f35.nq.gz
│   ├── 0c28f38a57cd4a52dec95e8f94fac189b3014e06.nq.gz
│   ├── 0faa08ac2d6808e5340e7b57ff0e10a66ab63975.nq.gz
│   ├── 13693090c08562352dbc9b45f2519f742cc0d46d.nq.gz
│   ├── 142b6ca357fee89f09803fc9ad7ff676500c37cf.nq.gz
│   ├── 156c755d543a6f2093991f23801cbab53a2da43a.nq.gz
│   ├── 157fcc78f14e17324817c62cdb69247cfb49e8fb.nq.gz
│   ├── 16b35a35ffe94d36a348a52d95b5de2092e7e8b0.nq.gz
│   ├── 1704e4fabe2f23529854a66d88f3bd2eeef875ec.nq.gz
│   ├── 1d268f5884d3edaa2ebd73f6bea09ab2e7e7400f.nq.gz
│   ├── 254143bfcc9706a826612ff49e54d9082820416b.nq.gz
│   ├── 28beda17a7a60bf9392ddeffb6ff42eec473fca3.nq.gz
│   ├── 2d87ff4fe1705e2cb13b86e4ede1b40d508b175d.nq.gz
│   ├── 34faad44656926c89b21866fbccea2e2b14978b6.nq.gz
│   ├── 377eb118b9c56021470db1017c776e574e2289ff.nq.gz
│   ├── 43141efa3da740c06f33926f0382825ad5d387a7.nq.gz
│   ├── 484532f054e085bf9f47c2e25f046720271e5da0.nq.gz
│   ├── 4b827e3145865d3223491c08baa5b009beef4581.nq.gz
│   ├── 53c3ba44d1388b89625b98767f96636bd7aa62b5.nq.gz
│   ├── 5cdba9d31d1cd04c47449f82efdf6877f27d736f.nq.gz
│   ├── 5d9f9b04fce55986add9865a36fbbc45f614213a.nq.gz
│   ├── 6374aa9e7312bfa213a29086f5d29bf8330fe786.nq.gz
│   ├── 6668e6ca30136fa9714631b2959ace0b3818f0da.nq.gz
│   ├── 69734dcf0fa9f906c509b60d59bfc8dd0d2f614b.nq.gz
│   ├── 6f911144472c6f86ba73b4b39a1ccbd70c6a69b4.nq.gz
│   ├── 71637b421f8504f272c4d5cecbc5c74ac8f22d96.nq.gz
│   ├── 7235b7d685287570cf5a949e9e69b5d297faadbd.nq.gz
│   ├── 72a33558153fb57def85612b021ec596ef2a51b9.nq.gz
│   ├── 7839ac281a99d02e6d931cb377eb81f5b2103526.nq.gz
│   ├── 7cfd76f72ca88ca1b68eb56f99d4ef6115d48bab.nq.gz
│   ├── 7f8ebd61c48ee65b6609e53174b1c25bd9bfd84e.nq.gz
│   ├── 80983936b7a44eea0d6320917336497f84e7defe.nq.gz
│   ├── 85ece4a4f47f64be32aaed26bd00b9b037980d9e.nq.gz
│   ├── 861777a9c65826708da84479299d68fdd6a45923.nq.gz
│   ├── 92a3af5ac39565d854faec8f84a7149ab31e9725.nq.gz
│   ├── 95e8f540249e6ebc962ea935a931701f4b767640.nq.gz
│   ├── 988efb54e1108bb6adb24ddf46472c6adbb8f9b8.nq.gz
│   ├── 9bda4636858516cec9631b370cc1edc712897441.nq.gz
│   ├── aa8a444eab23cac0dd65966b3ad5e77789642a9c.nq.gz
│   ├── aa8a6fb84fcfabba1bf104091f77ba282184c086.nq.gz
│   ├── aea778938d61812866274b2e2f2b12e75a8972d8.nq.gz
│   ├── b4af6f460fd109e997817ca43e3ef667b1e959ab.nq.gz
│   ├── b5c718b5f7d7500c07a9a1cc2671f2b2e3ad4f08.nq.gz
│   ├── b8aca43e4c812bd0a63fc575af498b4310b31143.nq.gz
│   ├── bb1dbac25dba3810e7a2cee60bd12847b1538da2.nq.gz
│   ├── c228484c97e84e2fd4cca78ecae3c79adede1f26.nq.gz
│   ├── c607a38569e45961300771862c1a4074e79c34f5.nq.gz
│   ├── c755b14399ff0a46bff067dd42df4dd8a3b4d874.nq.gz
│   ├── c88028a5a47327f67e68ad8fa422ba618eddbee2.nq.gz
│   ├── c8f0e124200c87ef360a99bf64b49d309986d323.nq.gz
│   ├── caaafb5c86b46f083cdcea19a098eedf4ca21485.nq.gz
│   ├── cc1eaeb7c140607a77df483ce4c60ce15eeca186.nq.gz
│   ├── cdb214b3b1263405197c66f133938f9a65d15505.nq.gz
│   ├── cf21f9fc1241e82bf680cb5f028dc948a6793dc9.nq.gz
│   ├── d3e3c23d593ae3b9ec0a4d87477b6c953ec5f1db.nq.gz
│   ├── d7d4fb383f5a379332c7445578972e9b3c7eda9f.nq.gz
│   ├── d9e113ec685b92b018297dd2f200341d1fba01f9.nq.gz
│   ├── dbb488f06bad1b8318e64dfe9a91516f3d4d1456.nq.gz
│   ├── e069ba6d38b272832d60b2f03f8b5edfa1fa7547.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ea7fb3c95b78b6bbde8fd11d45d4555d32e251e2.nq.gz
│   ├── eb8b04b3bd0e7b4d38c1fa686e0a33b326a11d09.nq.gz
│   ├── efc810738a9c7c3e6446661c3c561ca270b9ad7b.nq.gz
│   ├── f03ef6082e3398bbc4ca0096d7aedf5c5291f9ec.nq.gz
│   ├── f14e4a8486896c1ea2ade28faafca93faee9cbf9.nq.gz
│   ├── f4894c7eafbdb3a811da5f81dd82c9855bd2da27.nq.gz
│   ├── f4b17b72272f07fc5f885d80f010aea1fee426da.nq.gz
│   ├── f4e4f4d5d2f36c68462385aed90bc30c11110ae9.nq.gz
│   ├── f5a1c551df20f38ffb28fbb853d5fcf353871884.nq.gz
│   ├── f64f965afe8f504b1cd2015ef645ca65c0f35f3a.nq.gz
│   ├── f7735e0f830a585bcceba7725bddcdc9544f6542.nq.gz
│   ├── f8640384243f87dcac5cc8687f3ba08e8495f74d.nq.gz
│   ├── f9a14bcf8b4781a94dd87196c610c72cd8a125eb.nq.gz
│   ├── fa6c84f340df0ab511cbf6a419c4a8ad1e0d24a0.nq.gz
│   ├── fa748e3d1742a3b3ac08f249febea134d161fa01.nq.gz
│   ├── faff4e29d898d2939685e68649e62e97fab784de.nq.gz
│   └── fe3efd06f4a32639f77048c34cb8b162a83ba368.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── c39a1a7e74d90aebeb30797a61d0e491942557e8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 85 files
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

[pytest-dev/pytest-play](https://github.com/pytest-dev/pytest-play)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
