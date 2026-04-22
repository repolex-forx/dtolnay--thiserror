# Repolex Knowledge Graph of dtolnay/thiserror

RDF knowledge graph data for [dtolnay/thiserror](https://github.com/dtolnay/thiserror), parsed by [repolex](https://repolex.ai).

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
lexq download dtolnay/thiserror
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── dc0f6a23a3fb6ae34ef117133ec43650450c4b32
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── dc0f6a23a3fb6ae34ef117133ec43650450c4b32.nq.gz
│   └── repolex
│       └── dc0f6a23a3fb6ae34ef117133ec43650450c4b32
│           └── chunk-001.nq.gz
├── blob
│   ├── 00463be9e722b60e6b947033b99c2fc99b4e73eb.nq.gz
│   ├── 035b15e5d136a12c5db31664752820ef3b02fc74.nq.gz
│   ├── 07cd67ac6422d84244bc488ff45aac2ca8285f51.nq.gz
│   ├── 08c41f92b14991acadf9bd1a3348f5b3c8f75949.nq.gz
│   ├── 0a0bcbee8ed514b4e7c28e901f273ba0b064bede.nq.gz
│   ├── 0a101fc01cd46036cbd94a59564ee2e97e9b3e4c.nq.gz
│   ├── 0be0eaf3bc69d4e13b8512e5f67f49ba58045ae2.nq.gz
│   ├── 0ebdf4519f49f9714eb8a05495cb4317546fd1dd.nq.gz
│   ├── 149a2434da11e4a44921101bbf9e2f90b5855805.nq.gz
│   ├── 155b5b63bf02b21b226069fd7bb98d998404fd2f.nq.gz
│   ├── 15e579f8fa75af13da14d5642c88e7d163c73e90.nq.gz
│   ├── 160b6b247ff5a62ef46dd1dda2d465ee60c187ad.nq.gz
│   ├── 1872fb5a88a1cd62cc55f0f5be35736781ba3812.nq.gz
│   ├── 18f2466450cafb141fd33fda9bce83025cf44d3d.nq.gz
│   ├── 1b5ec8b78e237b5c3b3d812a7c0a6589d0f7161d.nq.gz
│   ├── 1f5350bcf84150abca02e30c0e4e7837aaf5c0c5.nq.gz
│   ├── 20fe888c30ab44fa877a58de0304f4b5e2a5a5cf.nq.gz
│   ├── 21bd885e68f1a10fb27ea354c2623ae3fd0a7c90.nq.gz
│   ├── 21cd5e105adc0a955d05984fdf194e4f9df85f47.nq.gz
│   ├── 23a6a065ec960a031726c8c26222b0405d4f5851.nq.gz
│   ├── 23dcf287702525a456e92329f3566223ba81ccd5.nq.gz
│   ├── 25890f221db5227a86c8f883c71e41364f093140.nq.gz
│   ├── 26fe0a9a7f989236caa5f44c1638d1271a43be64.nq.gz
│   ├── 2988ca37c92715dcb418fe3bc1b91bcc38d515de.nq.gz
│   ├── 29968bee6ab52ee691ad16f735534a4d6dadb304.nq.gz
│   ├── 2a59f183baedb8ab51ffe80ac7496a2fd41cbbeb.nq.gz
│   ├── 3012ca31190754a030f6e2b661ea6613c72f8d79.nq.gz
│   ├── 31aa79387f27e730e33d871925e152e35e428031.nq.gz
│   ├── 31e23fe683d73a31fe57eea6ba94876017a931c3.nq.gz
│   ├── 32f7a23d2ada8288a85e20e65a0b88ceb0e08876.nq.gz
│   ├── 335614bd013a874e626a8060c7801cecaa92192a.nq.gz
│   ├── 36882b99010a22b5cbb8ca800e467c88d0211100.nq.gz
│   ├── 3849f66e787304d2a10822269f4986b4f27f352d.nq.gz
│   ├── 3b781ac4e1f42c4166bc404c9a8a038353f96427.nq.gz
│   ├── 3ec4d71c0d5a7ce1f341df101d61ff27f9e3469a.nq.gz
│   ├── 49c0e466792936a1234e2fa06fc53184ea3b8194.nq.gz
│   ├── 4a4b2d39891f7ca84a79b6a17e9afde018e0452d.nq.gz
│   ├── 4b2f06a98fb3fe0ce6673edde58d6a8ef473b73b.nq.gz
│   ├── 51af40b1579a3735f9a358b8ba7ed382ef09bb5f.nq.gz
│   ├── 545aa8ee198132f177ec873b6cf1fc17e8a234de.nq.gz
│   ├── 54d958b2780d03c964d06fd6dfc7d2df5ccedb1d.nq.gz
│   ├── 568e891a18f6ce3d29abb37683ae767110694b68.nq.gz
│   ├── 569df8dd406a084dd387eb3973771316f5d5d16c.nq.gz
│   ├── 5c0b9a3bfa243cc13a04abbc44edddcddd32fefc.nq.gz
│   ├── 5fb57441566abad6ed03b0e397cd01782976163a.nq.gz
│   ├── 649d77df81a8c89ad191324ece6c07aba8c000c5.nq.gz
│   ├── 6bd3730731c84c0f08886a9f3392e80db70e54c6.nq.gz
│   ├── 6deb65826e954a26afdf86ee864eb9486dfb75c5.nq.gz
│   ├── 6f15841dc09ba91abcf265b33877a419748f8553.nq.gz
│   ├── 72691295e70a2c720ae579071711c6d1720f42bf.nq.gz
│   ├── 73718aee6b08e7e756ef73c6ac717b6e023de3e0.nq.gz
│   ├── 73b9970a65a01540208d4ce094f1cb0b14e5c398.nq.gz
│   ├── 73bf79fa28241d37d24c157753d9392483f0da81.nq.gz
│   ├── 750707701cdae985156601cc906195021ba6a6e5.nq.gz
│   ├── 76219eb72e8524f15c21ec93b9b2592da49b5460.nq.gz
│   ├── 77f95837d42c27de9c1cd5532e962a323a4f7dcc.nq.gz
│   ├── 7ad83e02704a9000320932a11f70355ded605e46.nq.gz
│   ├── 7c439d941f1d4fa5fa749504d3e484f7a69da65b.nq.gz
│   ├── 80ccfc973a8e9a99fb7f671283a71b63a7a026c5.nq.gz
│   ├── 811ff539589f06347d57d0e51fb31d021908dfe5.nq.gz
│   ├── 8321d4ab0045ec280e65197d8891db5e9f042acc.nq.gz
│   ├── 87c32e0b6cfbeb9e134da72f63b57fbc9d1e10a1.nq.gz
│   ├── 8b03d2f07858d57284d551439663079442cf5590.nq.gz
│   ├── 8b53cc0cd9028cf4549fce3be58d0afeb7710540.nq.gz
│   ├── 8b58136e52b1dc468ca80f584f3314cf6f0057e0.nq.gz
│   ├── 8d22c3a59bfc10b44a9e64abec1b46fc683fcf0a.nq.gz
│   ├── 965b606f331b51d566b46025f9ff311a7aad0c12.nq.gz
│   ├── 97136017dfab7289ea1330c07734857a8b71ff4f.nq.gz
│   ├── 97505826ef5b873ab8cbe0d4ecac92186cec4a3b.nq.gz
│   ├── 9914aa5f54438f4dd75c69e710023a46611536d9.nq.gz
│   ├── a3ce94daf534fc346a966f06b9ec1592486bac00.nq.gz
│   ├── a6551632b356f265f491c72e67eb38bd7e649c74.nq.gz
│   ├── a6c993220c3783f034f12255a988c56970ecd1d2.nq.gz
│   ├── a82909d627e1ef5083f1723b8db24eafa56cc251.nq.gz
│   ├── a8308790e0c20c88751230f8ea3e5733d7898a52.nq.gz
│   ├── a877c2cd0fb959306ab9805d4c3df7bc0d0b742f.nq.gz
│   ├── a9adfa5a90ba3714a2212c4401a758371a270a66.nq.gz
│   ├── aadf138cd37c6e5454340bbbabace8024b5a396e.nq.gz
│   ├── ab133717848a24d257899842a418fd381da0829f.nq.gz
│   ├── ac91cc867b4863a2a8b9c26228cf2597dd7717e7.nq.gz
│   ├── ad7286706fd5583312e530e32ae147baa5651c96.nq.gz
│   ├── b4f7fbbfd5e2ec9baa42a5a1e0f5e04e9a15fed3.nq.gz
│   ├── b98c31e9c6b01371036868c1bc9bfbce456af64a.nq.gz
│   ├── bb836d4e8d58f4738419a41667d8517b1d932358.nq.gz
│   ├── bcbfee0cf1e1eb8ec86a3b542fc70d71a4843ffa.nq.gz
│   ├── bf3c24df298a962971330393e6bc74bae630f821.nq.gz
│   ├── c0be37357e8116d0ab1fac5e2e777621c9676317.nq.gz
│   ├── c0e3806e7f469d653ffa8ee532605d750fbc0c98.nq.gz
│   ├── c26aa0ce984cbfdc25d191c1bc3621bdc1da1fe5.nq.gz
│   ├── c3d6c0023d9d037030436a2fb2b48494ef366e0c.nq.gz
│   ├── c8de5747df7979653f570dbf66b8a0ba6ea76d9b.nq.gz
│   ├── cace226157e2251755504a5b5a2f2371045915ba.nq.gz
│   ├── cc2567699141c7a8f41c4db97ab9e6add5e42f9a.nq.gz
│   ├── ccb906776285c24f30957178d3beedb22103bd85.nq.gz
│   ├── cd6a9346d5395ee7cda904b3d21b1f1acd20019b.nq.gz
│   ├── d1558fb76affd6c68a18abfe0f01d40943c244b7.nq.gz
│   ├── d4512c288bcd439ad5b3f45ed8632182eae1cb53.nq.gz
│   ├── d52fbdf0d908644ca4106cf9d89a72d7a9fae8a0.nq.gz
│   ├── d5429b2b2637732dc720154f4e250a97049f59dc.nq.gz
│   ├── d59df1eef8fc126e300442afc2c1a6433b0adf26.nq.gz
│   ├── d804e00542a8636708d788b0f679887326df2984.nq.gz
│   ├── da7899cece2fb2e2f61de9f94efe56cdf7c0d255.nq.gz
│   ├── dae2285b830c89ce6a7d636b5736f5f7aaf740c1.nq.gz
│   ├── dc97a4b8740f68e5c35110d1308f1a163de810a9.nq.gz
│   ├── e2a73a4700b02c963810431f9360a3e72fcff717.nq.gz
│   ├── e544657b24955784efe4dc42cd6349e73f1c41a7.nq.gz
│   ├── e7e66d055d7cdcd33e8e6af934012504f6ed0070.nq.gz
│   ├── e9e21997b1aca0707f8749ea13c09aec66c899d2.nq.gz
│   ├── eb52cefbd9e934fd46be2d7c529378a3cd3842bc.nq.gz
│   ├── ecfcd857a8a81c66e234d22838887394861abe05.nq.gz
│   ├── ee126d452cd21ed800e82d6e883b27d5fe96e2d3.nq.gz
│   ├── ee30f5b2ababf4b901ce302da03d9c53b2489942.nq.gz
│   ├── ee50d03a7b20871972133f6a7c4f1e7d4df27bf3.nq.gz
│   ├── f05e2ec97be10ebed41913a96bd1c2c1f6ff7956.nq.gz
│   ├── f337c592eebec1c846d6f85393f95676c2d24ec1.nq.gz
│   ├── f39649424ce38afc561d079bef79c082463c10b5.nq.gz
│   ├── fa85c1d2d5d9ca18ffeaa47f591f6c70e5baeda4.nq.gz
│   └── fe7472ef2fcd028054af448b2f1e91e2ff5db459.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── dep
│   └── dc0f6a23a3fb6ae34ef117133ec43650450c4b32.nq.gz
├── filetree
│   └── dc0f6a23a3fb6ae34ef117133ec43650450c4b32.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

15 directories, 128 files
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

[dtolnay/thiserror](https://github.com/dtolnay/thiserror)

---
*Parsed on 2026-04-22 by [repolex](https://repolex.ai)*
