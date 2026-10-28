# Repolex Knowledge Graph of sdispater/populous

RDF knowledge graph data for [sdispater/populous](https://github.com/sdispater/populous), parsed by [repolex](https://repolex.ai).

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
rlex download sdispater/populous
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 292fe8b91fc2ee1295e15225ca15d19bbb85ce71
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 292fe8b91fc2ee1295e15225ca15d19bbb85ce71
│           └── chunk-001.nq.gz
├── blob
│   ├── 0681cb8065cc77856da02e4c583348ce5c2f3ee8.nq.gz
│   ├── 081e935758799978d1226725e9c97abbcebe9afe.nq.gz
│   ├── 0cdbc3b7d502ffb26fe870d26a04bbd1dd8e11d5.nq.gz
│   ├── 0f1bf0a90debc367064ce84cd108250b42cc571f.nq.gz
│   ├── 0feac7803b0b0739d9f04302dbd66d488bc92ff9.nq.gz
│   ├── 14574b67f3dd0c818dc9933a66bb91bf46fa21ed.nq.gz
│   ├── 1479b33f61ab5aec0c019986e0a4123017bede8f.nq.gz
│   ├── 1e8413a19f8749cf72f52cf8ba9e05c5acb8cfc2.nq.gz
│   ├── 224c4f1303456d4c945af27ec35d85ea32b5a05f.nq.gz
│   ├── 2599f965d5e0c3bb2f92be14dac644c4d4b8d7a6.nq.gz
│   ├── 25dc52dbdef4bc5713cb347de9fc104bc3c09e12.nq.gz
│   ├── 2602b51971646d0c606018e9be8bc73f100c2c25.nq.gz
│   ├── 26ddf082f26824ce9faeddcf12623fd3793e34f9.nq.gz
│   ├── 2de08a1d4fc07d361d2db49bafcfe24eb526d625.nq.gz
│   ├── 33e7ff88d288e69fd3633537a7cd899cb36cb06c.nq.gz
│   ├── 3a2331baadfd425db05d8bae7f012e7030f1330e.nq.gz
│   ├── 460fd6adba595c87823dc0156c0e7ec31943381b.nq.gz
│   ├── 4b4ed2cb75115ed48e6f75a9a73ee7c8156dce8f.nq.gz
│   ├── 4d248e49dd6c297313d661ddfed13a9aca73ae0c.nq.gz
│   ├── 4e0306a7998c28f342652cf32f4a18e5bc0c6378.nq.gz
│   ├── 51cda9a782ee6cd58dd5e50bad27239c85f64592.nq.gz
│   ├── 5518230d68844727694c26dad132e036489776be.nq.gz
│   ├── 560eafaa67e34d8b31a13cd7b04ba970082a0fe6.nq.gz
│   ├── 5834b3fcaf5025bfa7c92fccbdb2df95aabe8991.nq.gz
│   ├── 5c75baeaa50a75dd5f271818543943248f12ddfd.nq.gz
│   ├── 5cc5c58e39c6eca3994e53b510d61253349cb633.nq.gz
│   ├── 65590f5ad7f7ddb8e4945aaf1994c69b9a17d3df.nq.gz
│   ├── 678dcd53f925ca1a29c4ecb46e879b14d42e89a4.nq.gz
│   ├── 6b67a69d48e01b987b9c1153c79be504a7d846d7.nq.gz
│   ├── 6e59965d2cf688de50a0c58ea51ed3030ea6005a.nq.gz
│   ├── 705e4b607899c1fbefa78470cd865aae4ba9c50a.nq.gz
│   ├── 7218400600cf5a1b7d90e454b449e62d7f6be223.nq.gz
│   ├── 758bf5cd78a47e691a6f78aa017d2daec2be4b62.nq.gz
│   ├── 79e83ecbb927e2f88b595d55c23f219929f982b4.nq.gz
│   ├── 7ab1c1b6e6dc55a4bf9370dee3e8b3b60c9332c4.nq.gz
│   ├── 7f05b1f766e7533777e6cc1f0e7312d19b80393a.nq.gz
│   ├── 83d8b89888c7314661a1ff8db80b5ed537f5d3ca.nq.gz
│   ├── 857bec9bea41d1ca86fc455b174fc9fd4c01c91b.nq.gz
│   ├── 8e04b45edb13eee9c520b24948b529d1817e789e.nq.gz
│   ├── 9624ec4862767c15bc63dcc26ac5509437abb5bb.nq.gz
│   ├── 98e2a6713ca62f609a3886500c3d71d76f3fe6e2.nq.gz
│   ├── 99cbfa9507b794bd22da7f5230b938c8ba8d4906.nq.gz
│   ├── 9a1d4153c17154d9f703c296ba8e58a2e7b44d43.nq.gz
│   ├── 9b6c8be2923dced0049f965741eaa73fbdb61503.nq.gz
│   ├── 9c7acfa81abb4af360fc775f5e7d3a6631964f46.nq.gz
│   ├── a1758addf4a85bc87f47c141ccc5c1c72ef827d7.nq.gz
│   ├── b6dcd7dc231e5dfc72ce99ee0e3cbace339ddcf9.nq.gz
│   ├── ba499f5241a2ba338583e31cc53276e6418007a1.nq.gz
│   ├── bd8373ce121011ae3b32a4f2e3e615b78b277a7a.nq.gz
│   ├── bfbf98d748e191a188fbb8f672bb6c5204d48b38.nq.gz
│   ├── c45abfdc4def6d49d4aa266ad9106e7474ead9b9.nq.gz
│   ├── c92363e723112ca12e1e800c5e413d7514a2f4ba.nq.gz
│   ├── ccda5f507c07256e22e8b5cbd13c4fde751dd236.nq.gz
│   ├── d2d3355a12e455555694f1a2e9844e6a6ba34561.nq.gz
│   ├── d396c2a7cb4a9c69d07b596337b1fffb249c0191.nq.gz
│   ├── d8933a5459dc668d3788d51d6142a1b2ec7fddd0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9833c0acd592f424f31b4aa5c719f87fdf3f604.nq.gz
│   ├── f13057cbb390c0df38b90c61deb311b62c95edfa.nq.gz
│   ├── f650ad68198bbce37103c64bb4ab07d00bcd9cdf.nq.gz
│   ├── f8b225970bc65598b3a77fe0c3937d88796e58df.nq.gz
│   ├── f9726f9e67d10a596ac6efaeb114a6c479fa24ca.nq.gz
│   └── ff8472ad43fa743852b2c5507a41613f4b0156b3.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 292fe8b91fc2ee1295e15225ca15d19bbb85ce71.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 69 files
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

[sdispater/populous](https://github.com/sdispater/populous)

---
*Parsed on 2026-10-28 by [repolex](https://repolex.ai)*
