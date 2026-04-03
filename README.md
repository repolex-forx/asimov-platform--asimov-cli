# Repolex Knowledge Graph of asimov-platform/asimov-cli

RDF knowledge graph data for [asimov-platform/asimov-cli](https://github.com/asimov-platform/asimov-cli), parsed by [repolex](https://repolex.ai).

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
lexq download asimov-platform/asimov-cli
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── blob
│   ├── 0d29b413d3a30a3012cc627862195caea84ea5e1.nq.gz
│   ├── 0e180fef7fd8ae8fe2e360d0876bcfb28ca1871c.nq.gz
│   ├── 10b359dd05935c73efb064470f9ecda90f6d28aa.nq.gz
│   ├── 1109dd81a65380c9ce2f9f7a6ba33ba54ab0908b.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 177975e493d030b630efac99ea3e5882bcf62328.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 2b92969eb97d39073469eca879edf22c2fbeaefd.nq.gz
│   ├── 2c0a9e33605740ca2a3a56bb4f0db850aea99013.nq.gz
│   ├── 2c28155f1b11d82323b110f5e96a719c7271cc95.nq.gz
│   ├── 41d249f4c9569b44814d3fe4ba4e5117235afe29.nq.gz
│   ├── 51e7bdc94e090c1e124270c5b99a3418c90a221e.nq.gz
│   ├── 658adcc79a0b97ba92c4c055adfced92a05d374e.nq.gz
│   ├── 6e73644427b77a347a098e1762b420d917539311.nq.gz
│   ├── 70b50f72a723fd5825b898131b2db43e718d6b18.nq.gz
│   ├── 799655099a3197f8189b261cf85f78d67093e0c2.nq.gz
│   ├── 867d1f08ebae7761448bc94f79da2170e25cca94.nq.gz
│   ├── 8920f737eaf4ae8b75ae0a9cf17bac9dd8b1a0c7.nq.gz
│   ├── 8b85e1998da7b980fd6e73025499443c58d9f113.nq.gz
│   ├── 9bb5714b34adf1841d64a8208e8da756617bb7f4.nq.gz
│   ├── 9fe50de16e59d550235aa6d7d15ee12ddf054414.nq.gz
│   ├── a0610be332ec7e62e85ebfbad8f485f58c2ea0d5.nq.gz
│   ├── a1ac84772af0dc5f31826485d417e243e5b1536d.nq.gz
│   ├── a3c140beae32701390337627cae504377e7816e4.nq.gz
│   ├── a718674ce58c2cb835775828c8a323d259c0848c.nq.gz
│   ├── a9f25b21e66ea2cf3604b45016f4e50f81fae943.nq.gz
│   ├── ab58ac4eec6a29572620fdad9af20ccb5e1c8527.nq.gz
│   ├── ac0bfe28560e0d0707478ccdb0fd828452e3ffa6.nq.gz
│   ├── ac0cdf2e80f60675158180690a4c37464fde7bd5.nq.gz
│   ├── af9908b08f4b33c32a0080af73f53bc0fa0cdce4.nq.gz
│   ├── af99d7b2bdc0c86ee2288a7743c4f39c977d436d.nq.gz
│   ├── b3f36470a08999e14fc6b9e154797c16ba85a06f.nq.gz
│   ├── b60e8b08985742d6b03716b41a210bc2a621cabe.nq.gz
│   ├── bcce4e18c62ea0613d125ec3c67440ba6218934d.nq.gz
│   ├── bf7979d80de339f2eb28f2b0c7a3ead98947d9bf.nq.gz
│   ├── c7504b17b600cacd0a72d17b05bb8dae214c4791.nq.gz
│   ├── c791a19ced31f11f22d0b2b26a15ab19281e0917.nq.gz
│   ├── ca1445439f68bef0a010e25ca3d19a05b6573bdc.nq.gz
│   ├── cd0e15c1359d367306de047ee89e343f47ead708.nq.gz
│   ├── cdc938768df3bfc07872eda7f986e2455b7e076f.nq.gz
│   ├── cff6707c09c5a607a4353d841a4d4a61276813c7.nq.gz
│   ├── d2d774d685a805fac62723c16262a6ba9ded7549.nq.gz
│   ├── d319baf38461eca0cc0b63d8f5e008c2e16a8379.nq.gz
│   ├── e2506bbed8637f8b1a9c3538378873ef2ca7c783.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── eb2e7f6910a1dc7e9cc8b1952becff13665e7219.nq.gz
│   ├── ec50a64ded33981836d5e4a10ec60f3501f1ce74.nq.gz
│   ├── ec95674fcc7a55b62f69e9e38f436f75cb707ca6.nq.gz
│   ├── edff4af5e1a64c6a712aa4aca418c96393e531ce.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── f414b6040b71066a72c0fd302ba9af8fe7c9bfdb.nq.gz
│   ├── f41f91bdc855c38c9a87be761fef12b2c277dc20.nq.gz
│   ├── f55d1289261fb1103c85d6df772ef3d0d05a98a0.nq.gz
│   └── f930701fc4a4eb57c90e54dfd42157065dd5448f.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 82679619f36a3fd6c11f13467033828fc2fce2bb.nq.gz
│   └── f171ce6df67e1bf4e617799ffef4049a6db11f1d.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

8 directories, 62 files
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

[asimov-platform/asimov-cli](https://github.com/asimov-platform/asimov-cli)

---
*Parsed on 2026-04-03 by [repolex](https://repolex.ai)*
