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
├── aggregate
│   ├── ast
│   │   ├── 1909f568320a31549724cacf930e6d59afb32488.nq.gz
│   │   └── 93ca34091227291b5f0b8b631e0417b9457246f7.nq.gz
│   ├── dataflow
│   │   ├── 1909f568320a31549724cacf930e6d59afb32488.nq.gz
│   │   └── 93ca34091227291b5f0b8b631e0417b9457246f7.nq.gz
│   ├── lsp
│   │   ├── 1909f568320a31549724cacf930e6d59afb32488.nq.gz
│   │   └── 93ca34091227291b5f0b8b631e0417b9457246f7.nq.gz
│   └── repolex
│       ├── 1909f568320a31549724cacf930e6d59afb32488.nq.gz
│       └── 93ca34091227291b5f0b8b631e0417b9457246f7.nq.gz
├── blob
│   ├── 0adf23b03a26084848d017083cc0dac0228a9576.nq.gz
│   ├── 0e180fef7fd8ae8fe2e360d0876bcfb28ca1871c.nq.gz
│   ├── 10b359dd05935c73efb064470f9ecda90f6d28aa.nq.gz
│   ├── 1109dd81a65380c9ce2f9f7a6ba33ba54ab0908b.nq.gz
│   ├── 139ab877a87b4116a9c10694c2852591804e2f0b.nq.gz
│   ├── 1b918a1138be47796e28587e3cd4c7c451768cc6.nq.gz
│   ├── 1d50476a8470210389148d5c3b89b70aceb4bcfe.nq.gz
│   ├── 2b92969eb97d39073469eca879edf22c2fbeaefd.nq.gz
│   ├── 2d6c15e6194e3b288e11d88f500bc17e37edd824.nq.gz
│   ├── 2d9d0dd04e11f129fe7d514f8cae560723a531af.nq.gz
│   ├── 340b11bfea01564e925d57b2f17bedf8bd4a252b.nq.gz
│   ├── 362c5674e1555193ec0c195fdc045a80d923c31c.nq.gz
│   ├── 3871d78261a0a0d167a167fd33ac141fe32ed968.nq.gz
│   ├── 39f81d9f0b218594a035f3dfad2a62b91f1643a8.nq.gz
│   ├── 3b384147fae8463b4d5ee70f693b068a5a763a3b.nq.gz
│   ├── 41d249f4c9569b44814d3fe4ba4e5117235afe29.nq.gz
│   ├── 4b884af167fa424749f9ba5855f91a21fc45f6f9.nq.gz
│   ├── 51e7bdc94e090c1e124270c5b99a3418c90a221e.nq.gz
│   ├── 528ba6c3abb8b8d48bc2f322b5303927e45cacd3.nq.gz
│   ├── 5dd90b9a87279f345dcbfc77c598ec47d5e2914d.nq.gz
│   ├── 5e9e0b6b70c04ff774972b2d35296863c0e3b728.nq.gz
│   ├── 658adcc79a0b97ba92c4c055adfced92a05d374e.nq.gz
│   ├── 6ddbc81d9cc703c87c0d95be24a1afd83168b451.nq.gz
│   ├── 6e73644427b77a347a098e1762b420d917539311.nq.gz
│   ├── 70b50f72a723fd5825b898131b2db43e718d6b18.nq.gz
│   ├── 77edabaabfeb7cfc00d0a791526a549254229dab.nq.gz
│   ├── 799655099a3197f8189b261cf85f78d67093e0c2.nq.gz
│   ├── 81337ffdfdb032096b76c7b92ee3afc577c5f763.nq.gz
│   ├── 879140d1d6bbb6004c077322db2269f760574015.nq.gz
│   ├── 8920f737eaf4ae8b75ae0a9cf17bac9dd8b1a0c7.nq.gz
│   ├── 8de5ca2a73d6689d5905b348f828c36d0a193a6b.nq.gz
│   ├── 99ed9307fa55a9f92d3efdaed9baf8f058e1ed9d.nq.gz
│   ├── 9bfb32d11aee64bc5b9009c55069e8e82d3279ec.nq.gz
│   ├── 9fe50de16e59d550235aa6d7d15ee12ddf054414.nq.gz
│   ├── a0610be332ec7e62e85ebfbad8f485f58c2ea0d5.nq.gz
│   ├── a60efa72aae284e29a17b138998bc10273b0b766.nq.gz
│   ├── a6e396b99f92c07e4bb190673167f2447101f4d3.nq.gz
│   ├── a718674ce58c2cb835775828c8a323d259c0848c.nq.gz
│   ├── a84cb1f435d1e4c31acd6136783803e34b201abc.nq.gz
│   ├── a9c7bb3ed49be6ccb23dc85f264967d3bd53f0d8.nq.gz
│   ├── acbaea17648562d8b4fa9a3cf16c053c5d589f6b.nq.gz
│   ├── af9908b08f4b33c32a0080af73f53bc0fa0cdce4.nq.gz
│   ├── b10914adf1950885ca13ab88b759c5185ff8fd08.nq.gz
│   ├── b4e48e1410651aa0e0768e1fb02810527c107da7.nq.gz
│   ├── bcce4e18c62ea0613d125ec3c67440ba6218934d.nq.gz
│   ├── be6ee362f26181311b863eb5528cbdc5f1be9e51.nq.gz
│   ├── bf7979d80de339f2eb28f2b0c7a3ead98947d9bf.nq.gz
│   ├── c40b15c91a762a2b017674b5e8766c133739cbec.nq.gz
│   ├── c728828e5fc78d1ef4dad83092ff8e0a8c3380d5.nq.gz
│   ├── c7504b17b600cacd0a72d17b05bb8dae214c4791.nq.gz
│   ├── c791a19ced31f11f22d0b2b26a15ab19281e0917.nq.gz
│   ├── c874b723213bcb8a0cae99f17f9dec1a1b5e32bb.nq.gz
│   ├── ca1445439f68bef0a010e25ca3d19a05b6573bdc.nq.gz
│   ├── cbce8469a5881ca69dc69e5708c9748934f79b58.nq.gz
│   ├── cd0e15c1359d367306de047ee89e343f47ead708.nq.gz
│   ├── cdc938768df3bfc07872eda7f986e2455b7e076f.nq.gz
│   ├── cff6707c09c5a607a4353d841a4d4a61276813c7.nq.gz
│   ├── d41d4632b7e73f8ff8248d5332221e1560f5ea84.nq.gz
│   ├── da766161df2516075ad5ace718080aab51250279.nq.gz
│   ├── db78e1165db429348f35084e585657b6b11cec74.nq.gz
│   ├── e2506bbed8637f8b1a9c3538378873ef2ca7c783.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e4aaac08b63bd75482659d91b2a90bba4d88916b.nq.gz
│   ├── e63db7f72b307c27d24ba328c366b87e231af8f1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e78bd0dc1f4e1ebe4c8a03d5cb05a383ce164f07.nq.gz
│   ├── e94d007030c7f349ab7a49bf213a046e494b7efe.nq.gz
│   ├── eb2e7f6910a1dc7e9cc8b1952becff13665e7219.nq.gz
│   ├── ec95674fcc7a55b62f69e9e38f436f75cb707ca6.nq.gz
│   ├── edff4af5e1a64c6a712aa4aca418c96393e531ce.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── efc9c833c2442fee1f171511ba04d9156606bbc6.nq.gz
│   ├── f414b6040b71066a72c0fd302ba9af8fe7c9bfdb.nq.gz
│   ├── f41f91bdc855c38c9a87be761fef12b2c277dc20.nq.gz
│   ├── f74bc35b895b7f186b6a9f40014981317d93f620.nq.gz
│   ├── f930701fc4a4eb57c90e54dfd42157065dd5448f.nq.gz
│   └── ff1657eceb63fe9ab2d572fd3e52be6366113524.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   ├── 1909f568320a31549724cacf930e6d59afb32488.nq.gz
│   └── 93ca34091227291b5f0b8b631e0417b9457246f7.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 92 files
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
*Parsed on 2026-03-18 by [repolex](https://repolex.ai)*
