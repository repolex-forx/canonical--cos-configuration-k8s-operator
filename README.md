# Repolex Knowledge Graph of canonical/cos-configuration-k8s-operator

RDF knowledge graph data for [canonical/cos-configuration-k8s-operator](https://github.com/canonical/cos-configuration-k8s-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/cos-configuration-k8s-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9364ce7e6715c918bd1d51dc4e8eeb8bd7636cb8
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9364ce7e6715c918bd1d51dc4e8eeb8bd7636cb8
│           └── chunk-001.nq.gz
├── blob
│   ├── 03e5b8fcf27c9ca42d4cf1a76398c943b3430034.nq.gz
│   ├── 07b437627c5c85c402f5bd738f95208be1774c28.nq.gz
│   ├── 0a680f5a5db10e08181a048a447c08a584d51967.nq.gz
│   ├── 0c2887782de90b0f4c51cea140cd37dea8b7f122.nq.gz
│   ├── 14cd592e0466bfdd79dcf2003f3bf9310308a98a.nq.gz
│   ├── 1527248b125dabe30867ea3750b2a727c6797536.nq.gz
│   ├── 1755f3630ff852b2e034cc60fbfb2d73e492a634.nq.gz
│   ├── 17b233bd240e75867aec281bd28ad383b82fdd8c.nq.gz
│   ├── 1bb45e9085b56696c3b53307f0da6268b4b3d16a.nq.gz
│   ├── 219793a0aa948e6766e7ef5ea130682b05755c83.nq.gz
│   ├── 21d1008ea05d344395e4a5d961ec7dd183c1c88b.nq.gz
│   ├── 2fddd8d9608d24f4cb8ea347cc3f532417c7591b.nq.gz
│   ├── 3500a8da6c72b0d4028467bdee07087df993fb78.nq.gz
│   ├── 3755082de04061fcb54c9465e0d4ff82664aafd6.nq.gz
│   ├── 387ac6a47738bcce3f686ea6d43178ab2197e414.nq.gz
│   ├── 49800c280e211dec8b637f0c0617fa66f7288367.nq.gz
│   ├── 4cf38b57613d27a3ac3740a4b86e04ff1cb167aa.nq.gz
│   ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
│   ├── 5e8f4f6551168871cec2ab58e955a8ecd624b7d5.nq.gz
│   ├── 5f429d03760f20f56cd060c8e15e525ebb0bfe34.nq.gz
│   ├── 6105d2193a599aa0f61a600100960dc0d071b4eb.nq.gz
│   ├── 623fae4978af551884e8859a914526597f5baefd.nq.gz
│   ├── 6526b451f81329a02504420b2dcbbd1bd07a38ce.nq.gz
│   ├── 6529018230d905782e567630986cf15c86cf441b.nq.gz
│   ├── 652c7d218edf2dc1dcf39f46f745b352c2172801.nq.gz
│   ├── 6540f7eefc9ebbd871e89c7974e644dc6b54ecc9.nq.gz
│   ├── 6ccd559eabeae93e4d23215fa450130fa9b37ace.nq.gz
│   ├── 6e8a973f15b9cc6532dbe45c6878c3dc0e01a280.nq.gz
│   ├── 6f94cded4fec60283aa42d48789f2f779e32bb9a.nq.gz
│   ├── 704dcfa370e0ed74ffe1ce14166c8c89da9394bf.nq.gz
│   ├── 7d61be1199e065f432b9dfa55fa4de081e94ccd7.nq.gz
│   ├── 7dc71b68fcfb255f04c72b5ffc84ef966dc2b24e.nq.gz
│   ├── 84534a0b5b8f3d643c067df95432f2f61f99531f.nq.gz
│   ├── 888c85583f72dc67ed997c9868566452e70cf898.nq.gz
│   ├── 8d898f486776983adf57a6e83a4baa6d7656d7c2.nq.gz
│   ├── 9007c8c6849f86c05e1ebb4cdb4605fb0f9b4d2d.nq.gz
│   ├── 901f14351bdce339c3fcc6c3b3112c94e4fecb2f.nq.gz
│   ├── 92a7408f3c1e71b93bc9b8cb4aec9b5a710e0693.nq.gz
│   ├── 982c0e0fe7327a921301ef2f47c965aea9137feb.nq.gz
│   ├── 9d5c8feeaaf887cf4ac755614cf7beb7e4f19cd6.nq.gz
│   ├── a522fee2d9f683fc944962c89b94c83b47418973.nq.gz
│   ├── a69ab44af7b74e2f2272ab4f7ce76ad5a2aeba57.nq.gz
│   ├── aae9a69ec1b91c9b69fdfded988adc60659883f2.nq.gz
│   ├── ad60b546623c02340f4e7eb19bf83031a47b2ea1.nq.gz
│   ├── aff29f890a081dacb874528f6aa2e9edde9c581c.nq.gz
│   ├── b2348b9fbfdc4eb154566c80f844510446be1d02.nq.gz
│   ├── b415af0a8109afa614fe12d8c9d83e095c752d50.nq.gz
│   ├── b746b3f99c42cda9a29895956a49232a2f5fb0c0.nq.gz
│   ├── bc6a02c945fa01fa126e8e600077df0ca77f16f0.nq.gz
│   ├── c415d619034ba92706972804c4316f2d0f5a937d.nq.gz
│   ├── c6a55109313d5f0b49bfbeb6358346bbd5fa265d.nq.gz
│   ├── cd5f322120ab5ed637bac606eac95065857b469a.nq.gz
│   ├── cd64df9260b3b1fbfaac7df2be50a01d3b190e58.nq.gz
│   ├── d645695673349e3947e8e5ae42332d0ac3164cd7.nq.gz
│   ├── dddf1a8d41157d098cf3c842f1db4595172408af.nq.gz
│   ├── de535d0f97c5fd103dfccb173b400b7e71461bd6.nq.gz
│   ├── e8be3d11e825521618022012357008d1905407d6.nq.gz
│   ├── ec723be465f40c298ce761498c60a3a05c5d30c3.nq.gz
│   ├── f29d4af1b3448b0fb0fa9aeb7295a42b460b3bfc.nq.gz
│   ├── f2c7dcf552c7a788fdcfabc6fa911afcb985d826.nq.gz
│   ├── f35143eb2ace2ec8c395b78e06459ca40e03caad.nq.gz
│   ├── f42427246ffca71d3a311b74522017ef416d177f.nq.gz
│   ├── f4aa9e929f7e6bdca6242a2545014480968600ec.nq.gz
│   ├── f9ce09e42632d292a93276f0ffe8ac44be6455da.nq.gz
│   └── fed845447169507b9ec5af45cb1f11dc61f4118b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 9364ce7e6715c918bd1d51dc4e8eeb8bd7636cb8.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 73 files
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

[canonical/cos-configuration-k8s-operator](https://github.com/canonical/cos-configuration-k8s-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
