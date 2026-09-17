# Repolex Knowledge Graph of tanstack/intent

RDF knowledge graph data for [tanstack/intent](https://github.com/tanstack/intent), parsed by [repolex](https://repolex.ai).

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
lexq download tanstack/intent
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 18a8fc1ad567b42b0fc01554f0cb11440c2b82d4
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 18a8fc1ad567b42b0fc01554f0cb11440c2b82d4.nq.gz
│   └── repolex
│       └── 18a8fc1ad567b42b0fc01554f0cb11440c2b82d4
│           └── chunk-001.nq.gz
├── blob
│   ├── 0026a8814214c919d52b0a66f376595aaad2188c.nq.gz
│   ├── 02f11e48760122ca6873502172a217312fc50f84.nq.gz
│   ├── 0398d36c71a3d531d5a6fc68d71ad6ffe10dcc11.nq.gz
│   ├── 03d265a50106a780b1224a07ef0a4bbf4464ff01.nq.gz
│   ├── 080b84e9f2450fb32a0dcfb28d5381ddf5b24bae.nq.gz
│   ├── 0c742309b79fa4df2c56cd8e779c9fda13715df4.nq.gz
│   ├── 0e36f6a2c07b9c52a2c604b4ef65f113e4cc6f1e.nq.gz
│   ├── 195c1f91dd356207296b6d567001f20a3c798a90.nq.gz
│   ├── 1bf884d16c6f96e7559fc91765734dac27e02a95.nq.gz
│   ├── 1d58c4f5e76e508aa4bd2d829ff69ec953731492.nq.gz
│   ├── 1f48e15777effb8306166e9568314b260d15de9f.nq.gz
│   ├── 2217c8788c05b415e8107ec7cb151bd4165e85c2.nq.gz
│   ├── 22a083777bb6074241786588f5f986fa432958dd.nq.gz
│   ├── 254f72f2de50edbefa1ed899b3e44cc1269f10b6.nq.gz
│   ├── 268c392d3cb71fb4ae2f175cb7478a627f4a3a10.nq.gz
│   ├── 26b83a2e37f03a6b5f0aaed3e454f7b41be6789a.nq.gz
│   ├── 2e8dc24f414dd09be1521815a28e57231118b031.nq.gz
│   ├── 2effee9ec91a970539eb09afb5b1aa75d958812f.nq.gz
│   ├── 316e7a2b4434704b4d22469c583c13a2cf1ce934.nq.gz
│   ├── 31b74cad0b919614bed74eaf5f4cb6d553d5f9bb.nq.gz
│   ├── 34808401f7c40b280c2fb8e659e7eb150a74941f.nq.gz
│   ├── 36bfbbcac0857d048c989412c695e39ce9e07ac3.nq.gz
│   ├── 3aa66066e18903df83a5a773071852f5f077a2c4.nq.gz
│   ├── 3c14fcd67cb2f86f9420278848efb432dfd20a1d.nq.gz
│   ├── 422f7d2e28d6a1fa605599be8373f0588bc9e7ff.nq.gz
│   ├── 44e3e817f7a24b3023c5d0c217e626eddc4e2cdf.nq.gz
│   ├── 4b27e13e3106d6f07b42ea28898788818eb06d22.nq.gz
│   ├── 4e68b5b969ebf0f42655fe618764134ba7b11fa1.nq.gz
│   ├── 50ceeb2d0488de75050b64d7c291a10a552599bb.nq.gz
│   ├── 52742a4d6da3e2f602eb6427c83c8a2144ca8bd6.nq.gz
│   ├── 53e9b8461ae3248c3bb15e2f1b7a80c59424b30d.nq.gz
│   ├── 57d9021eb3ea62b045cd3ef2d93089e1ffe98968.nq.gz
│   ├── 5835ba0b5f4b2d31b68418a58d3d03f33f150222.nq.gz
│   ├── 584f8c8019055d8ab5c0debd10ec5912b731940d.nq.gz
│   ├── 5add109e67e5bd2a7671b23f962d90f598cf80ef.nq.gz
│   ├── 5b3091d46b40e34a844622d38bd17e0451a1656b.nq.gz
│   ├── 5de4148bdb2243cb0f438ebf10e1b0c34346c9c1.nq.gz
│   ├── 5e46ca11797641e59cb9766a5d29ddef78de4b3f.nq.gz
│   ├── 65798085d2ede95a9acfea594f3fb1e561404db0.nq.gz
│   ├── 679c2ec519b57ea349e2a9db043721475983c0cc.nq.gz
│   ├── 680382327980ceb8994d1746ad5e8e75f7987f3c.nq.gz
│   ├── 70deda66b10d81af820966a2f65c0dcf1e05f70a.nq.gz
│   ├── 7351a178ef4edcf31e80bfda34bdcf8fe2af8a7d.nq.gz
│   ├── 756f590b4d66bdab408a38a059c1e35e98698ce5.nq.gz
│   ├── 76802436fb89fb2b81e481ee3a5b1a846b4c95ab.nq.gz
│   ├── 7b9c66d4614f61c595a656123c867c21e6d9370a.nq.gz
│   ├── 8a1c40ddc515f3ef7d4a4a570084f8eabaf744a7.nq.gz
│   ├── 8f39716aa982b1a86222e64fe9b9545c31290af2.nq.gz
│   ├── 8ff32f05391c33e8d6941bea422a9324407d18e0.nq.gz
│   ├── 901204d1b300c4d42ae07d7fd927aafd25f04faa.nq.gz
│   ├── 904117cad1e27e07eba5edf42503f3279016d328.nq.gz
│   ├── 9065d4850341cb943463205605567f63129b42b9.nq.gz
│   ├── 9134737ca0aceb13198f38069cda510d4863dc4d.nq.gz
│   ├── 91670a6c844c52bfcef95b11ff1d1d4c3addc4b3.nq.gz
│   ├── 9d08a1a828a3bd2d60de3952744df29f9add27fa.nq.gz
│   ├── a0dc1420bbc2657b889dacf8757d0eb259e2ac27.nq.gz
│   ├── ac5fc112d937e0f7072ba0d928e6b90e0f887016.nq.gz
│   ├── b24cf46e46dc2b1114228b8ded47820340ba5d47.nq.gz
│   ├── b3a9b9f5d65ddff6d84690612d958bf7d53a47fb.nq.gz
│   ├── b40402760432e1e60ce87646a294814866bfe195.nq.gz
│   ├── b532c4dea6c7fc0450dfd6468bcff35b793c29d1.nq.gz
│   ├── bd43909333b7461945acf88fa53adde5d7a045be.nq.gz
│   ├── c2a526bb8ad59229fc0e2505990f81f7571fc859.nq.gz
│   ├── c4686742e4d474ef7ea432a16b08fa75bfee5058.nq.gz
│   ├── c74940bdce3e21ccfd31b7ea9dbe73d5dc4e2320.nq.gz
│   ├── cbeb23105a67cdd35af2185e047d0c76fcfb3f91.nq.gz
│   ├── d0d7146eb606150e94c58abe7ffb081ed1356f6e.nq.gz
│   ├── d1561e32883b21d6b3f75afbe3f27e4d2ee9f9f8.nq.gz
│   ├── d38b74e7d95bf15bf19322dc1b4aade31ce3f0da.nq.gz
│   ├── d58b8af1f18fb7c51eb671f6bb49adaeb1aa19b6.nq.gz
│   ├── dbb08b111030f71191ee00be67d551fbdde7308d.nq.gz
│   ├── e19f643a970ad522d4733505d99a8e432b41e460.nq.gz
│   ├── e2ea8ad3b9df4f7d3759a122bd420f4f8e1bbb56.nq.gz
│   ├── e700f23f3ee25a316733be4fce731399023dbc2c.nq.gz
│   ├── e72d76300b604545678a11d150689680eb1054f1.nq.gz
│   ├── e7eaf26b14aefee99ce8776490f32775bd2f646e.nq.gz
│   ├── e95ad1b2c813f366557e4e24fe744250e9f54d86.nq.gz
│   ├── f61e1296abdf8807d74eec61e554d1e893cd0dd8.nq.gz
│   ├── f67138a3dc8562b576c8eedc8ac5db7cdadfb028.nq.gz
│   ├── f7a232bed28b23efab5ef9bb539afa85cd188f30.nq.gz
│   ├── f7ef756659cee1c93adfc78da01d5871155b8807.nq.gz
│   ├── fa111aa2dbdc1860b5f28a39a1a4fe5b5f3e4281.nq.gz
│   ├── faa17f4874bb7b118e75c169857a402ffc9a2441.nq.gz
│   ├── fb2083cf49c84afa1d06613b344b9abd776a9299.nq.gz
│   └── fdfee28a2cfeefccc75460245527e2f9bf043943.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── 18a8fc1ad567b42b0fc01554f0cb11440c2b82d4.nq.gz
├── filetree
│   └── 18a8fc1ad567b42b0fc01554f0cb11440c2b82d4.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 95 files
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

[tanstack/intent](https://github.com/tanstack/intent)

---
*Parsed on 2026-09-17 by [repolex](https://repolex.ai)*
