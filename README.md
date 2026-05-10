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
│   │   ├── 1909f568320a31549724cacf930e6d59afb32488
│   │   │   └── chunk-001.nq.gz
│   │   ├── 1988e90c39a8274f72a42214a59ea1ebc128f9fc.nq.gz
│   │   ├── 28d5aa6104b1baf8431afad7c992612eba45b2a7.nq.gz
│   │   ├── 429d8e19d046a9bd0f0909f3fc9b4e67330f5ba4.nq.gz
│   │   ├── 82679619f36a3fd6c11f13467033828fc2fce2bb.nq.gz
│   │   ├── e202a1f5530669ec1582738b40d349da7ee21529
│   │   │   └── chunk-001.nq.gz
│   │   ├── e3f1fdfcf387cb09c3ae45a0cd1aa0175586384b
│   │   │   └── chunk-001.nq.gz
│   │   └── f171ce6df67e1bf4e617799ffef4049a6db11f1d.nq.gz
│   ├── lsp
│   │   ├── 1909f568320a31549724cacf930e6d59afb32488.nq.gz
│   │   ├── 1988e90c39a8274f72a42214a59ea1ebc128f9fc.nq.gz
│   │   ├── 28d5aa6104b1baf8431afad7c992612eba45b2a7.nq.gz
│   │   ├── 429d8e19d046a9bd0f0909f3fc9b4e67330f5ba4.nq.gz
│   │   ├── 82679619f36a3fd6c11f13467033828fc2fce2bb.nq.gz
│   │   ├── e202a1f5530669ec1582738b40d349da7ee21529.nq.gz
│   │   ├── e3f1fdfcf387cb09c3ae45a0cd1aa0175586384b.nq.gz
│   │   └── f171ce6df67e1bf4e617799ffef4049a6db11f1d.nq.gz
│   └── repolex
│       ├── 1909f568320a31549724cacf930e6d59afb32488
│       │   └── chunk-001.nq.gz
│       ├── 1988e90c39a8274f72a42214a59ea1ebc128f9fc.nq.gz
│       ├── 28d5aa6104b1baf8431afad7c992612eba45b2a7.nq.gz
│       ├── 429d8e19d046a9bd0f0909f3fc9b4e67330f5ba4.nq.gz
│       ├── 82679619f36a3fd6c11f13467033828fc2fce2bb.nq.gz
│       ├── e202a1f5530669ec1582738b40d349da7ee21529
│       │   └── chunk-001.nq.gz
│       ├── e3f1fdfcf387cb09c3ae45a0cd1aa0175586384b
│       │   └── chunk-001.nq.gz
│       └── f171ce6df67e1bf4e617799ffef4049a6db11f1d.nq.gz
├── blob
│   ├── 09285b472c16269a882203847d159c2dff105cde.nq.gz
│   ├── 09fc469a6140fb1b1a9d3c315eb8b6666a5bd3cb.nq.gz
│   ├── 0adf23b03a26084848d017083cc0dac0228a9576.nq.gz
│   ├── 0babb13fd016b78a9de387887a90d87edb470af5.nq.gz
│   ├── 0d29b413d3a30a3012cc627862195caea84ea5e1.nq.gz
│   ├── 0e180fef7fd8ae8fe2e360d0876bcfb28ca1871c.nq.gz
│   ├── 10b359dd05935c73efb064470f9ecda90f6d28aa.nq.gz
│   ├── 1109dd81a65380c9ce2f9f7a6ba33ba54ab0908b.nq.gz
│   ├── 11fe0edc0aac357f877b577628ddde5d0fcb525d.nq.gz
│   ├── 135738d96efe6a61d11bab9682cd6b0ec28f1cf2.nq.gz
│   ├── 139ab877a87b4116a9c10694c2852591804e2f0b.nq.gz
│   ├── 13edb27f8341a15f7ef6805243c5be8572913129.nq.gz
│   ├── 153dda9f8f3442227ef4fda6bb508f895bf536a2.nq.gz
│   ├── 177975e493d030b630efac99ea3e5882bcf62328.nq.gz
│   ├── 19fc2dca0fe377d191dfa274618746180914cd57.nq.gz
│   ├── 1b6002e1239ea532454c256c15bba5477a0af79f.nq.gz
│   ├── 1b918a1138be47796e28587e3cd4c7c451768cc6.nq.gz
│   ├── 1c541529a150aa9abda1aaf918ae9645285c1c47.nq.gz
│   ├── 1d50476a8470210389148d5c3b89b70aceb4bcfe.nq.gz
│   ├── 1d57081eaa5040d728572ff5872557a4c0d07f48.nq.gz
│   ├── 1dd12e4b0e91d960ee6ebddf64e37d2a24e5f79d.nq.gz
│   ├── 2234d4df808796356cad5ebba89d8e6f77f600b7.nq.gz
│   ├── 2391f73aa051d3804285ce744f2e9a1c7e08993d.nq.gz
│   ├── 24ba9b38a66abaeb86523745e9d28221f8a2416c.nq.gz
│   ├── 2b92969eb97d39073469eca879edf22c2fbeaefd.nq.gz
│   ├── 2c0a9e33605740ca2a3a56bb4f0db850aea99013.nq.gz
│   ├── 2c28155f1b11d82323b110f5e96a719c7271cc95.nq.gz
│   ├── 2d6c15e6194e3b288e11d88f500bc17e37edd824.nq.gz
│   ├── 2d9d0dd04e11f129fe7d514f8cae560723a531af.nq.gz
│   ├── 2f05b805fe01c0c0304ac3848f358e54996cc9cb.nq.gz
│   ├── 31a72a7a7243593d347873c04c27e2d3c89f656a.nq.gz
│   ├── 33515e85fa8b40b71f312ebf052938e93c290375.nq.gz
│   ├── 340b11bfea01564e925d57b2f17bedf8bd4a252b.nq.gz
│   ├── 344ba72562fa4bc8189d5dc52a5415fdc2fae0db.nq.gz
│   ├── 362c5674e1555193ec0c195fdc045a80d923c31c.nq.gz
│   ├── 3871d78261a0a0d167a167fd33ac141fe32ed968.nq.gz
│   ├── 39f81d9f0b218594a035f3dfad2a62b91f1643a8.nq.gz
│   ├── 3b384147fae8463b4d5ee70f693b068a5a763a3b.nq.gz
│   ├── 3eafc6cba34d772e42f405fe1b796dd5906a4c26.nq.gz
│   ├── 41d249f4c9569b44814d3fe4ba4e5117235afe29.nq.gz
│   ├── 4b884af167fa424749f9ba5855f91a21fc45f6f9.nq.gz
│   ├── 4efa699542779925029b2b43444e82cb0c9a597d.nq.gz
│   ├── 4f49a374f85f8dc8aa0bd9e7a9d313d213c40f79.nq.gz
│   ├── 51e7bdc94e090c1e124270c5b99a3418c90a221e.nq.gz
│   ├── 528ba6c3abb8b8d48bc2f322b5303927e45cacd3.nq.gz
│   ├── 5c07e6b435acac3accf1dfbbc1ec8cf817304e75.nq.gz
│   ├── 5cb865ee99175b6e506a88fdfcb75c07d7c73ccb.nq.gz
│   ├── 5cd43e35890b67cf2a4ee69c23a8cf425844ff90.nq.gz
│   ├── 5dd90b9a87279f345dcbfc77c598ec47d5e2914d.nq.gz
│   ├── 5e9e0b6b70c04ff774972b2d35296863c0e3b728.nq.gz
│   ├── 6584dd0ca981204fd62acac797cd0bcac6f87dcb.nq.gz
│   ├── 658adcc79a0b97ba92c4c055adfced92a05d374e.nq.gz
│   ├── 677849a89f8acda35def7e0536c9b0bc27719685.nq.gz
│   ├── 68730723f18d7ebab1c4dd1140555b9da5df6726.nq.gz
│   ├── 6d42263b658cf838406fbb1758af71b4a49adf7d.nq.gz
│   ├── 6ddbc81d9cc703c87c0d95be24a1afd83168b451.nq.gz
│   ├── 6e73644427b77a347a098e1762b420d917539311.nq.gz
│   ├── 6ec372e39a05fc681e4be87ce55035ec310caad9.nq.gz
│   ├── 70b50f72a723fd5825b898131b2db43e718d6b18.nq.gz
│   ├── 77edabaabfeb7cfc00d0a791526a549254229dab.nq.gz
│   ├── 789fdbfc0a79b3d54e48faca7e78d5cec5b1fdfb.nq.gz
│   ├── 7900e7f85b26652f66ff3e91350351ba3b9c0022.nq.gz
│   ├── 799655099a3197f8189b261cf85f78d67093e0c2.nq.gz
│   ├── 7bc4f4bccf0f7db73d97709b53c1866c49f5b84b.nq.gz
│   ├── 81337ffdfdb032096b76c7b92ee3afc577c5f763.nq.gz
│   ├── 867d1f08ebae7761448bc94f79da2170e25cca94.nq.gz
│   ├── 8778d105f0c0e1e39f43381c69882955250bff3c.nq.gz
│   ├── 879140d1d6bbb6004c077322db2269f760574015.nq.gz
│   ├── 8920f737eaf4ae8b75ae0a9cf17bac9dd8b1a0c7.nq.gz
│   ├── 8b85e1998da7b980fd6e73025499443c58d9f113.nq.gz
│   ├── 8de5ca2a73d6689d5905b348f828c36d0a193a6b.nq.gz
│   ├── 8e03f963aa373e7c8621206b0f596598ea9fea00.nq.gz
│   ├── 8fd74c90c67522e4b66b4a99936cbccb50c58f78.nq.gz
│   ├── 96f219f22bddec011bcbd2a089cb9153d59d8770.nq.gz
│   ├── 9905cd2dc26f0d822b336e00c4d47a50b390c17e.nq.gz
│   ├── 99c9435b5ddfe1f8037eaba438b958b12f3b2353.nq.gz
│   ├── 99ed9307fa55a9f92d3efdaed9baf8f058e1ed9d.nq.gz
│   ├── 9bb5714b34adf1841d64a8208e8da756617bb7f4.nq.gz
│   ├── 9bfb32d11aee64bc5b9009c55069e8e82d3279ec.nq.gz
│   ├── 9d0cd2ef6878a1e1f392701d14fb622654187c94.nq.gz
│   ├── 9fe50de16e59d550235aa6d7d15ee12ddf054414.nq.gz
│   ├── a0610be332ec7e62e85ebfbad8f485f58c2ea0d5.nq.gz
│   ├── a1ac84772af0dc5f31826485d417e243e5b1536d.nq.gz
│   ├── a20b126a2778a9ad5ec5f08c260868a01aabd1b2.nq.gz
│   ├── a3c140beae32701390337627cae504377e7816e4.nq.gz
│   ├── a60efa72aae284e29a17b138998bc10273b0b766.nq.gz
│   ├── a6e396b99f92c07e4bb190673167f2447101f4d3.nq.gz
│   ├── a718674ce58c2cb835775828c8a323d259c0848c.nq.gz
│   ├── a77fbd6d90108deb1901f8b57f53ffa304c6a5f9.nq.gz
│   ├── a84cb1f435d1e4c31acd6136783803e34b201abc.nq.gz
│   ├── a855dc8294301132904cec8949819591a302cf19.nq.gz
│   ├── a9c7bb3ed49be6ccb23dc85f264967d3bd53f0d8.nq.gz
│   ├── a9f25b21e66ea2cf3604b45016f4e50f81fae943.nq.gz
│   ├── aa299b583b4a01ef8261a95c4fb8629a1a807439.nq.gz
│   ├── aa658cb7b3b8734a827233643bd280826de15ca0.nq.gz
│   ├── ab58ac4eec6a29572620fdad9af20ccb5e1c8527.nq.gz
│   ├── abab77236f0f9a03c9e4267a92c45225581727cd.nq.gz
│   ├── ac0bfe28560e0d0707478ccdb0fd828452e3ffa6.nq.gz
│   ├── ac0cdf2e80f60675158180690a4c37464fde7bd5.nq.gz
│   ├── ac9664f4be8e6579ef21a3adedd0d1dd4b7c2b38.nq.gz
│   ├── acbaea17648562d8b4fa9a3cf16c053c5d589f6b.nq.gz
│   ├── af9908b08f4b33c32a0080af73f53bc0fa0cdce4.nq.gz
│   ├── af99d7b2bdc0c86ee2288a7743c4f39c977d436d.nq.gz
│   ├── b10914adf1950885ca13ab88b759c5185ff8fd08.nq.gz
│   ├── b16503d98f8a2ca401327817157e6c01b4284a42.nq.gz
│   ├── b1b6e75915a75a1c2d61966f021692e2698b7dfe.nq.gz
│   ├── b3f36470a08999e14fc6b9e154797c16ba85a06f.nq.gz
│   ├── b4e48e1410651aa0e0768e1fb02810527c107da7.nq.gz
│   ├── b60e8b08985742d6b03716b41a210bc2a621cabe.nq.gz
│   ├── bcce4e18c62ea0613d125ec3c67440ba6218934d.nq.gz
│   ├── be6ee362f26181311b863eb5528cbdc5f1be9e51.nq.gz
│   ├── bf7979d80de339f2eb28f2b0c7a3ead98947d9bf.nq.gz
│   ├── c0044cba4b78103dd8dc83279bae6ab09ca82d52.nq.gz
│   ├── c215d64f53b632c8d0177a986f843c037cb77b4e.nq.gz
│   ├── c40b15c91a762a2b017674b5e8766c133739cbec.nq.gz
│   ├── c728828e5fc78d1ef4dad83092ff8e0a8c3380d5.nq.gz
│   ├── c7504b17b600cacd0a72d17b05bb8dae214c4791.nq.gz
│   ├── c791a19ced31f11f22d0b2b26a15ab19281e0917.nq.gz
│   ├── c874b723213bcb8a0cae99f17f9dec1a1b5e32bb.nq.gz
│   ├── c926dcabc4b233df869e10befa02a2b537a09619.nq.gz
│   ├── ca1445439f68bef0a010e25ca3d19a05b6573bdc.nq.gz
│   ├── cb1671bf850eb5d70d439150a49befc8d752910b.nq.gz
│   ├── cbce8469a5881ca69dc69e5708c9748934f79b58.nq.gz
│   ├── cc668578cd60b53ab8e99469753af51c04fbde74.nq.gz
│   ├── cd0e15c1359d367306de047ee89e343f47ead708.nq.gz
│   ├── cdc938768df3bfc07872eda7f986e2455b7e076f.nq.gz
│   ├── ced02c7e43f1b15787020e650182a391280f0d0c.nq.gz
│   ├── cf1b7faf1a76687d3fee84afb0aaa98c6d38f7bc.nq.gz
│   ├── cff6707c09c5a607a4353d841a4d4a61276813c7.nq.gz
│   ├── cffe347756387f81183496c46543ae28a7d2005d.nq.gz
│   ├── d2d774d685a805fac62723c16262a6ba9ded7549.nq.gz
│   ├── d319baf38461eca0cc0b63d8f5e008c2e16a8379.nq.gz
│   ├── d3f0fd6e93ed46783dcb66ca514a5ff9ff8d5a27.nq.gz
│   ├── d41d4632b7e73f8ff8248d5332221e1560f5ea84.nq.gz
│   ├── d54ebde6e151eb34bdf3682a05b10e7d112a0942.nq.gz
│   ├── d7fd035a5a6686ba3427654c488aa6812d184893.nq.gz
│   ├── d8357123eab660e8243bb27f9bc1055cafc7abce.nq.gz
│   ├── da2aed4a05e3573df49c89670127137689fbaf61.nq.gz
│   ├── da67b5e76848ee5330a12dbeef9409aa9368e89c.nq.gz
│   ├── da766161df2516075ad5ace718080aab51250279.nq.gz
│   ├── db78e1165db429348f35084e585657b6b11cec74.nq.gz
│   ├── e2506bbed8637f8b1a9c3538378873ef2ca7c783.nq.gz
│   ├── e3e57a8ce4ccbf74759a6df8fa4a3980ff1c9209.nq.gz
│   ├── e4a1091d4abc4a28ecf41089d135c72131dec490.nq.gz
│   ├── e4aaac08b63bd75482659d91b2a90bba4d88916b.nq.gz
│   ├── e63db7f72b307c27d24ba328c366b87e231af8f1.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e75482c6fb26970f3a7b3d0d0180e0ed70a8e0ea.nq.gz
│   ├── e78bd0dc1f4e1ebe4c8a03d5cb05a383ce164f07.nq.gz
│   ├── e94d007030c7f349ab7a49bf213a046e494b7efe.nq.gz
│   ├── eb2e7f6910a1dc7e9cc8b1952becff13665e7219.nq.gz
│   ├── ec50a64ded33981836d5e4a10ec60f3501f1ce74.nq.gz
│   ├── ec95674fcc7a55b62f69e9e38f436f75cb707ca6.nq.gz
│   ├── ede06db3d19b2c3c69656efeb3d07092493dea2c.nq.gz
│   ├── edff4af5e1a64c6a712aa4aca418c96393e531ce.nq.gz
│   ├── efb98088164f5786b17e83ed384971fc3c74f93c.nq.gz
│   ├── efc9c833c2442fee1f171511ba04d9156606bbc6.nq.gz
│   ├── f414b6040b71066a72c0fd302ba9af8fe7c9bfdb.nq.gz
│   ├── f41f91bdc855c38c9a87be761fef12b2c277dc20.nq.gz
│   ├── f55d1289261fb1103c85d6df772ef3d0d05a98a0.nq.gz
│   ├── f5e302d087aa0657de8160c078d5654df6afc0b1.nq.gz
│   ├── f74bc35b895b7f186b6a9f40014981317d93f620.nq.gz
│   ├── f88554fac6faf41573e9ba1181604120a98f52d5.nq.gz
│   ├── f930701fc4a4eb57c90e54dfd42157065dd5448f.nq.gz
│   ├── fc553385e86a47a84d99c5b56e1da2b62613d42e.nq.gz
│   └── ff1657eceb63fe9ab2d572fd3e52be6366113524.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
└── dep
    ├── 1909f568320a31549724cacf930e6d59afb32488.nq.gz
    ├── 1988e90c39a8274f72a42214a59ea1ebc128f9fc.nq.gz
    ├── 28d5aa6104b1baf8431afad7c992612eba45b2a7.nq.gz
    ├── 429d8e19d046a9bd0f0909f3fc9b4e67330f5ba4.nq.gz
    ├── 82679619f36a3fd6c11f13467033828fc2fce2bb.nq.gz
    ├── e202a1f5530669ec1582738b40d349da7ee21529.nq.gz
    ├── e3f1fdfcf387cb09c3ae45a0cd1aa0175586384b.nq.gz
    └── f171ce6df67e1bf4e617799ffef4049a6db11f1d.nq.gz

15 directories, 200 files
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
*Parsed on 2026-05-10 by [repolex](https://repolex.ai)*
