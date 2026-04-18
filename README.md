# Repolex Knowledge Graph of webpack-contrib/file-loader

RDF knowledge graph data for [webpack-contrib/file-loader](https://github.com/webpack-contrib/file-loader), parsed by [repolex](https://repolex.ai).

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
lexq download webpack-contrib/file-loader
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── 25e2668f75ae3e8f78adeb99297caa258b2479f3
│   │   │   └── chunk-001.nq.gz
│   │   ├── 6fadfbe9fe43ca86095c836a3c521dfbbac408aa
│   │   │   └── chunk-001.nq.gz
│   │   ├── c2aded7c33dae128cbbfca8a23b120a2be4843b2
│   │   │   └── chunk-001.nq.gz
│   │   ├── e44eb73eaf519aaf44f9eace2fecc95f700159c6
│   │   │   └── chunk-001.nq.gz
│   │   └── f1b071c55a6653a6efc7c42fd24cd787217730c6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   ├── 25e2668f75ae3e8f78adeb99297caa258b2479f3.nq.gz
│   │   ├── 6fadfbe9fe43ca86095c836a3c521dfbbac408aa.nq.gz
│   │   ├── c2aded7c33dae128cbbfca8a23b120a2be4843b2.nq.gz
│   │   ├── e44eb73eaf519aaf44f9eace2fecc95f700159c6.nq.gz
│   │   └── f1b071c55a6653a6efc7c42fd24cd787217730c6.nq.gz
│   └── repolex
│       └── f1b071c55a6653a6efc7c42fd24cd787217730c6
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d7a6b2c756295d0dcff045a5cafa17a34cef4e.nq.gz
│   ├── 066873ab8918612592267a5f24d642ae26fd0ae4.nq.gz
│   ├── 07891d0c5f761b7de1b1e16b9966c397aa7c89b4.nq.gz
│   ├── 07a01e12d50ca8e77af7388829531a6aa8b7ec20.nq.gz
│   ├── 095ce2a513be70fbc270f0a0872e7ecbae9cc5a7.nq.gz
│   ├── 0ad23b2de9230bf3ae9a0a765231cc7d5af2f2f4.nq.gz
│   ├── 0d44d4814649a5c90481218c48bca7cb850e5a51.nq.gz
│   ├── 0e2d1365f4857cea70e0900ae35e3d75e3ca7b7e.nq.gz
│   ├── 0f696f6c77960681b505efc6cca3c9c6e1bd4bad.nq.gz
│   ├── 12d0886a910e483e13a680e0ed736730fd61492a.nq.gz
│   ├── 190c33801b3a563bc750edd3d5f97b35815b4199.nq.gz
│   ├── 1934550a651ff23ddd95d4cf4a1ac8168e405708.nq.gz
│   ├── 1968f0437a01988e633158630be6e3f3613a10c0.nq.gz
│   ├── 1a36027d693c76f427fe4eda8aec862e6239c21d.nq.gz
│   ├── 1c71e970e2f3473207857d228446a936df890e02.nq.gz
│   ├── 1d20cf060477c3301492ce0f903f76c236a14f07.nq.gz
│   ├── 1e4b787080072ea5f5ede3fea85b1717f2a5f655.nq.gz
│   ├── 1f468502e988a52a5ffdc8c48960030d0d050b85.nq.gz
│   ├── 22ca42c5984fd3511418d50b1f8592d177fd3685.nq.gz
│   ├── 2350e2fadf724bfef3125218eb0bf9c36d50dec2.nq.gz
│   ├── 28f02168e17556403149aadcc9db8a16e237e0d7.nq.gz
│   ├── 2d24fcaefcdf3e457e5d2fa10131ca8c57404f1e.nq.gz
│   ├── 30cc7ef26ecc973af7989775f2dfb294a236cfcd.nq.gz
│   ├── 34e1faa214a30f43fbedc395969ab55a10d95d1b.nq.gz
│   ├── 358cfa9f76bee2ca7f4c19d387a4f3735a0cef20.nq.gz
│   ├── 3a54ebe0b715fa794ed5b49fc36b78baa5690aa8.nq.gz
│   ├── 3f0187ce57ce43b85e44f7f0e1beac9f85f9680b.nq.gz
│   ├── 3fcbc7ce60b37a8dc2e27ac9ee3188e9fd6ee52b.nq.gz
│   ├── 46d0fbdbfd6b310efa40381575f3b7d327a006f6.nq.gz
│   ├── 4aacdc1c6eb76aad05d5e2bdc072c8a538273355.nq.gz
│   ├── 4b82ada3d1b22252ec9928fd95db4a544f0f9dd9.nq.gz
│   ├── 4c2ec3ae82e3d88b259792fff9c89f012b02a994.nq.gz
│   ├── 4f14003fb7c09fe832e3a165dc8a20a6679b625a.nq.gz
│   ├── 51ba83e2c98d053ed56688eeeef243249f8f518e.nq.gz
│   ├── 539538c7431e6c5b4b23ed58903a49faff9504f5.nq.gz
│   ├── 54b7f84ff80d2a92f77db5884411ef30a1a48d52.nq.gz
│   ├── 550abc2cf8aaad512cd7aef9b7a2fe757e2a846b.nq.gz
│   ├── 558934ac01b69c44accb607b32f216f535820f79.nq.gz
│   ├── 590910bda23b8efde78fe761fe163983ce22741a.nq.gz
│   ├── 5a9c63caa123cbc16e97cefe87c6a48b5ecdd1f7.nq.gz
│   ├── 5df92b747c8ed453d725630e4f7ec5d5b0b424ce.nq.gz
│   ├── 5e7c7b6d7a63b3ae8efaf4dd3aaf741c71db767b.nq.gz
│   ├── 6151f27a86bb33f15756468f32eafc982e5ed1f3.nq.gz
│   ├── 618a5ec4ebd5ca7735f3c47fbee8fee5a803fed0.nq.gz
│   ├── 67a24aee948c7eb64f8363cfba9c2cb446628d35.nq.gz
│   ├── 6e6c7744302e63cc8ff978d99db093be52b2fdd0.nq.gz
│   ├── 79c2296e3b97f8283d9c13cccc5a204c994db302.nq.gz
│   ├── 7d34392673332647bdd5b466422ec2907fc09efc.nq.gz
│   ├── 84dcb122af08159d4135ebbf530f11b3129b988b.nq.gz
│   ├── 862e870325bc21632337d4aa5755fe2ac4bda418.nq.gz
│   ├── 866001ae9fa131baf14c8f4b46c8e05b6782bd9c.nq.gz
│   ├── 88d05ddde04a8320d053afeaf27535971f35fe9b.nq.gz
│   ├── 8916f61847c784899cbcace609ce37c08c807085.nq.gz
│   ├── 8a112da8840e364298b0407b099dfb23071b210a.nq.gz
│   ├── 8ab481bdf676ba8c26dc83262f7940a527028c4a.nq.gz
│   ├── 8c11fc7289b75463fe07534fcc8224e333feb7ff.nq.gz
│   ├── 8c1a771ac45d15e20cdbccf397f758c5521d990c.nq.gz
│   ├── 917937d7fdc2fbeaa915436774888bf7b8c0b678.nq.gz
│   ├── 947366de31156adbb2516883fd0fbf4ab2cf8521.nq.gz
│   ├── 97f5b6f6defa97e58b67e52a4dc6f2117d0b7e3f.nq.gz
│   ├── 9a144f5b238fa9de39860cbdc0c4357256df388a.nq.gz
│   ├── a195992f19d09118d0b0f5f1b8ce5f999be67499.nq.gz
│   ├── a90d9cf32e799d5e832c3d649f7d5daf62b1bffc.nq.gz
│   ├── aa9dd29d095dfc40f1809ac72be6d986728f5c58.nq.gz
│   ├── aaf787ae02d79052e646c1a1aec14e76fb8bd027.nq.gz
│   ├── ab524583df52338d82838e962fa810f805e4b81e.nq.gz
│   ├── af79d8f269f18e64651b7896cfdabbbadf5614da.nq.gz
│   ├── afe19dfad5c83bfe4c03bf3b60ddab5b475c59fc.nq.gz
│   ├── b1e6350b2df20d262b34bdd96e5812c0401ed1e6.nq.gz
│   ├── b2a232d88a3eb1c4912361c00764505c8fa1400b.nq.gz
│   ├── b42eef56a30f1c00e9606c3d5a1558637d898e6f.nq.gz
│   ├── b6875188a44d1c78c814c0f79d7d9b91c0f1b668.nq.gz
│   ├── b8675523d84aaa506f9eb54aebc0e510821da031.nq.gz
│   ├── b8771ef58d479614f59ab270837c5a0c78ed315d.nq.gz
│   ├── b9687ecb821cabad7ffa554204c6a39eac83a597.nq.gz
│   ├── bd8ba61c9faaba42c17dd03ad854dfd2a30ceb07.nq.gz
│   ├── c1c8d9a53cfb9fdb5c33d6b7044c042d96932493.nq.gz
│   ├── c36da37c97595bd85df107756e1437dae36ff5ef.nq.gz
│   ├── c417cb1ba379fba5b7b10491a4ae67fc2dd24f5d.nq.gz
│   ├── c5aa4522e1ce6dd1c2003d516efe85e986f821be.nq.gz
│   ├── c605e8cee72fb10ebc7dba78e346cc8c3ab6c7ad.nq.gz
│   ├── c6d0f160d545c719c72e35d44b59c6c314977998.nq.gz
│   ├── c76fd02b74b21e6743a803f0f167864059144af3.nq.gz
│   ├── c923e34e934cb64f7d0d71a2c286eb5a531c1742.nq.gz
│   ├── c98cf4f059a5ea622718655fa96f7ad4ddf4efe6.nq.gz
│   ├── c9fe1d219e3665b279112a83f84774cb9d5450f2.nq.gz
│   ├── d540ed769e616f05c076d85d59f63b14368ba22f.nq.gz
│   ├── e153a5d7aba9013882b793bf225b1f5f47240cb2.nq.gz
│   ├── e537c8adfe2e5228f144b4cea1ed5f178d807f87.nq.gz
│   ├── e579ef594b3ec1f533c30cf54c8d9f2bb95f713b.nq.gz
│   ├── e634a19f132031c4594342b1cf6579b758676615.nq.gz
│   ├── e66389a75f3a4c8eb730bfc4fc2de06223ec725e.nq.gz
│   ├── eba57dc3da35d97d5204887f53b1139a38aae52e.nq.gz
│   ├── ed7ab6a072eefe28cdfea47a68dc00d0eff48aed.nq.gz
│   ├── f1a083069b6d91c45544a65e3b1180ced37250df.nq.gz
│   ├── f32064859e1449d8cd7ac43c6a99f00959495b3a.nq.gz
│   ├── f4d9a77a6f376cb6148e591895dd5c728fd87480.nq.gz
│   ├── f68cbd3e629a4a5aa76c55af24e730f80d08fb5e.nq.gz
│   └── f9679dbe94756c00164c8a1bc8752fb524499e07.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   ├── 25e2668f75ae3e8f78adeb99297caa258b2479f3.nq.gz
│   ├── 6fadfbe9fe43ca86095c836a3c521dfbbac408aa.nq.gz
│   ├── c2aded7c33dae128cbbfca8a23b120a2be4843b2.nq.gz
│   ├── e44eb73eaf519aaf44f9eace2fecc95f700159c6.nq.gz
│   └── f1b071c55a6653a6efc7c42fd24cd787217730c6.nq.gz
├── filetree
│   ├── 25e2668f75ae3e8f78adeb99297caa258b2479f3.nq.gz
│   ├── 6fadfbe9fe43ca86095c836a3c521dfbbac408aa.nq.gz
│   ├── c2aded7c33dae128cbbfca8a23b120a2be4843b2.nq.gz
│   ├── e44eb73eaf519aaf44f9eace2fecc95f700159c6.nq.gz
│   └── f1b071c55a6653a6efc7c42fd24cd787217730c6.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

19 directories, 125 files
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

[webpack-contrib/file-loader](https://github.com/webpack-contrib/file-loader)

---
*Parsed on 2026-04-18 by [repolex](https://repolex.ai)*
