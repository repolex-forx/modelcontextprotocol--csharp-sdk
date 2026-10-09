# Repolex Knowledge Graph of modelcontextprotocol/csharp-sdk

RDF knowledge graph data for [modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download modelcontextprotocol/csharp-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 3338e88e15c42cfc27465143c140d7d10f1a2707
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 3338e88e15c42cfc27465143c140d7d10f1a2707
│           └── chunk-001.nq.gz
└── blob
    ├── 00317fcbd4480276e32df80c57eadb41e7fcec27.nq.gz
    ├── 0113e1abfddb2a849889bccc62b58e0f1fa20904.nq.gz
    ├── 01a4b26cf9443af377099a5ca7648e1523515d1c.nq.gz
    ├── 020896a1f8db0be2402318a2ecd4b691a35e3393.nq.gz
    ├── 02f9b5297a81364576d495e17cbb5bfe1ab924f0.nq.gz
    ├── 03af131b4be0d4d050c29b2eb39bf4b547ba2bbe.nq.gz
    ├── 0497d618a920e31f1c0f845884d77422211b12a5.nq.gz
    ├── 04ea63ea2faf373b5ddd44aa5c51d5b1b50f1af9.nq.gz
    ├── 053c2ec543d65ef613322cf500753bc5bb8438c3.nq.gz
    ├── 05f9bdff3ab8d2f3db6dc9d407d7dc7aa51380e5.nq.gz
    ├── 06573ec9f47578bacb658d224fb44ff98bd7ddd0.nq.gz
    ├── 0704fb9cb96b456530bc30c581b225b9dac691ce.nq.gz
    ├── 0840c9c7c9fb77de2487e14f6e2e02339b0b8a34.nq.gz
    ├── 0877a0f836d8d7dfa0e9ef07ef9d2e44dc78b962.nq.gz
    ├── 097848773275891c1efd0e2121eefe35d0757724.nq.gz
    ├── 09b1f5b3de3f336363c9a3298dfcd33717ca635c.nq.gz
    ├── 09edb09fc1e9a1fb831a3d3d1a006cd9a2e5dbd5.nq.gz
    ├── 0a7488688af8172164e21292c97b861e56734a24.nq.gz
    ├── 0ab19a37364fc211cc29c82e1ff152ca1e3eb2a9.nq.gz
    ├── 0ab7b526e9c02d9ee4cbf8b4fdc45a46f2e64b54.nq.gz
    ├── 0ac808ac5ba0d204b977287653d6c9013194275a.nq.gz
    ├── 0b56caa29bfed387fc3cd5324573a7304ad0b857.nq.gz
    ├── 0bf4aff19ffea1275e2f61b525f5c5af6952f904.nq.gz
    ├── 0c208ae9181e5e5717e47ec1bd59368aebc6066e.nq.gz
    ├── 0c431f3f0f629b9e24cc69c0123f6a95c3ac1161.nq.gz
    ├── 0cec55c9bd2869c2b18cc477fba92bc4ea68fb45.nq.gz
    ├── 0d0fafa0aa83aecfa95e9af254de7735d712a023.nq.gz
    ├── 0fb51dfe28eee5d2a9cf3e37867736b488a0acd9.nq.gz
    ├── 0fcb057113df466a00d6f0cff709d976838eeed9.nq.gz
    ├── 107c28d6ab3ed013e911f182686d21858a9cbbb8.nq.gz
    ├── 1127aa284f2631113c2c7bd282cbef1bf9b98964.nq.gz
    ├── 11ba0565e9126133ddcaabcc7ee029682b56a3a3.nq.gz
    ├── 12ab7ac1673a2c1d4428c5c20e34009f86ea0f7e.nq.gz
    ├── 13c92ee14dc45ce1f37f2fbc9a8e587ba6be471b.nq.gz
    ├── 142536b9d814ca7471615bceb4a760242cd67a1e.nq.gz
    ├── 150f6d307e60fa4fa5aa5a553bd5ccc11125cc9b.nq.gz
    ├── 15c0d7dea114b2bfd43c5cf35297c460fc2bb875.nq.gz
    ├── 166622d74c7edcd2d95056a6b65a8e10c3d923cf.nq.gz
    ├── 1747a6303bcf2c3164a3718158b9b08f4e5ed2b8.nq.gz
    ├── 1757fa6f6d37a633b4d7f5da7f4b07a2c2d392c5.nq.gz
    ├── 18386d326e71b82b992915f6d1f2bf4594c6a93f.nq.gz
    ├── 1866dfe136de9dd880fe519d450174da513b6017.nq.gz
    ├── 186ecc9c68de0090e76b6e7e6087357077cd663c.nq.gz
    ├── 19400d39470d3de7215f23cce76e0bf1b4e06987.nq.gz
    ├── 198fb43114b2e635c66f02ca6926cfefe0882598.nq.gz
    ├── 199ee899957c82bf73b150045427ff9507064e79.nq.gz
    ├── 1c99aa6609fb9e8c3b62ebc51645de48baff20dc.nq.gz
    ├── 1d9fe554ad26e1e11601d15ef4981c0774afb310.nq.gz
    ├── 1df78608ab4c2bc3fb9118d56b5cac08428c2635.nq.gz
    ├── 1df9c1c21a73e4fa58d5c03d37b09c79bdad4ffe.nq.gz
    ├── 1f9097ac5cefb7f4a6396169bbde4ec4a84ab58b.nq.gz
    ├── 1fec187333f84e5ebd0b75356e836ca6d9bd2a32.nq.gz
    ├── 205d70be0f5071f37a534affc7fe9022b1596c2c.nq.gz
    ├── 20789feb1e98eb7246b92983ce8aca658cf4f283.nq.gz
    ├── 209e571d164326ee56a2590c46237346f4d0e77f.nq.gz
    ├── 20dda4a18e27d5ae14a57b4be0bcd07bcd10dc1d.nq.gz
    ├── 217ff97eae1d3f30c30745199d02979c33374d49.nq.gz
    ├── 21fb98c2eb95f4687898e05c9ee42a16603c798e.nq.gz
    ├── 222130bb9b4607851a821ea2bf5cc9825ba44ce6.nq.gz
    ├── 2256dfb01affab20db1caaa2dfd43b16bbdc6150.nq.gz
    ├── 227bf132e9f490fea661b65e09546a2e78fef352.nq.gz
    ├── 229c57d6028cc4fc78d9acb3880d12e3a5ca7a34.nq.gz
    ├── 22f945ad0dce6fc0b8c84f7732b815c6b3ba3215.nq.gz
    ├── 2352eb966a03425c997b0ded5264a00992f358bd.nq.gz
    ├── 23b66a11b3044244174e0ee8af61cb13d16a6c00.nq.gz
    ├── 24081c06ecddd543e1b46aaa1f9a426dc683bc29.nq.gz
    ├── 274d53be38213ec3aea92a7a808d620b0361bb62.nq.gz
    ├── 27514aeb1c013ca127350f9633890816c1529b45.nq.gz
    ├── 276415e1333b3e8e65d11a7cae4a83ea95dab9b0.nq.gz
    ├── 2828602fcaf5afc6f879e8b55a49e39b07d19236.nq.gz
    ├── 283c47d6b3d4ba6fa568c2c13d201fbc7351a1c0.nq.gz
    ├── 292ed2f96700fbeda1485d13ca6014692b95e23e.nq.gz
    ├── 2982d8f87ef82a0c3f012bd537af738c3de45884.nq.gz
    ├── 29f524acb7aa3ab11c8a8beb770e71ff5fede7ef.nq.gz
    ├── 2a5f589de7eec1973bcb07b34d1e5ff3219e2f12.nq.gz
    ├── 2b2b66a37c98e65fe24bac9c1cca98cfb59bafc7.nq.gz
    ├── 2bed8175b64584a840d25f3648623aa9c6188a67.nq.gz
    ├── 2ce63a1bc2320a733f3c28ff74aaf6ff7af39b65.nq.gz
    ├── 2f3ce58846f19244737dfb111ff660846e357396.nq.gz
    ├── 2fe717786576e5ca0a82cce1a7d7b48fe0235912.nq.gz
    ├── 313523b1fa3d790402add8fe84e8faf40612514f.nq.gz
    ├── 31f5dbe87ca064790fb58da949d205626fb424df.nq.gz
    ├── 333dbdf15459cdf28650766c7edec6aa13af7e52.nq.gz
    ├── 336f583824ffa2639e73df98909d8a360511f0a6.nq.gz
    ├── 33d5403115ff083800c128f59f52aca576789203.nq.gz
    ├── 3439acc6005f4093bd95e6a857ee133fe5470c11.nq.gz
    ├── 34e77e2b49180ad6c4d482801a239d4ab71d829b.nq.gz
    ├── 35b6948a7872ebc1957cb73c04400c1534800753.nq.gz
    ├── 365cf281d7811184ff7fd9d516c8fa0124475c7d.nq.gz
    ├── 37234f7f4bdc8c0d0af96730b97ae632bcdb499f.nq.gz
    ├── 376609349c22ca8f4d21647a597f971506f93c00.nq.gz
    ├── 3833c490833cdc0cb4bec8be877f6cccc645babc.nq.gz
    ├── 396b5876bdb05fd829313bd8fdf103f5de4a00a3.nq.gz
    ├── 3998fe1f5f8e580f8fa7d13908028a083a10a494.nq.gz
    ├── 3a5001118e372e834268dc4eac6151435d99d81f.nq.gz
    ├── 3a68d619b4a134d1b542c60dc8950a6014a2d4c6.nq.gz
    ├── 3aa36e8bd7b956846eae7588ab7ee66c381df843.nq.gz
    ├── 3c070130c5a99fafc6b4287b222df462f2715b85.nq.gz
    ├── 3d149780a37ae6c0807ea629a42b02799d033d16.nq.gz
    ├── 3d37568ed2ed42ce0f24258f70e556b3c035edb3.nq.gz
    ├── 3d927b1632342103ce649f5136aa8bba3275013b.nq.gz
    ├── 3dc42b5cf6a09665180d6fcd7144b030fdfcb009.nq.gz
    ├── 3e5cea2806b08d3bf8525a70e86be4f11de9b22f.nq.gz
    ├── 3e6d24ad0f5840a66d9f8ae4a01368ac2905daf3.nq.gz
    ├── 3f4716342951846eb2bc0c9e71f51065d7784bae.nq.gz
    ├── 3f62021f08abe815dce3a01ac9564ceb79ff54f1.nq.gz
    ├── 3f6a4a3499c99fb13b729b08a964d4156319764e.nq.gz
    ├── 3fbef037702be2872f24973be399e5a1bcfc626e.nq.gz
    ├── 42472556d1bd5c3967b22d15b0ba0a0872b4b681.nq.gz
    ├── 4283ef3d56143eea8b4b2e065826393f0f08f9a8.nq.gz
    ├── 42b3fa3b5eb6b85c5992c7506be02a151e32b37d.nq.gz
    ├── 42bf22c5790bef8bbc28e219a3f8f47db170205d.nq.gz
    ├── 43a3c12b5c85e3fddeed0e080480d016e957dedc.nq.gz
    ├── 43c2838597581be9923c3894014501f167982af3.nq.gz
    ├── 44172666afa23f8ccb2fd09fc34538e2ce393bec.nq.gz
    ├── 4441c1d392fb9275412e666a753d246a242978ec.nq.gz
    ├── 44736a3089aade442eac0f6656087cf855d6a136.nq.gz
    ├── 44fa369c105f3a448cb19bac4e16a2da7c16a376.nq.gz
    ├── 452b8032169a6386a21e10d430f8090578fa3c04.nq.gz
    ├── 45cf0379ce3fc390b4444066bf475785b4ac46ab.nq.gz
    ├── 472ba08c4086bdb5c00bb23b691daafdf7738f4a.nq.gz
    ├── 47a5935b53f9502bed13b025b9d9147b231c9745.nq.gz
    ├── 47c51f07a57af72149723351401e6ac7e6c1f2b4.nq.gz
    ├── 4a337df363cf99c8f7618b564d3b643571d12b08.nq.gz
    ├── 4a830c48e68c88d86d159b0918957bff953e29c3.nq.gz
    ├── 4c0f014f0f59711274214e2b8ab59ef3e0e8e74a.nq.gz
    ├── 4c96a86b61373df77a8c4aa5c76cf4853ef99780.nq.gz
    ├── 4ce99c87c9c25758628ad644f80a0091593c0cb6.nq.gz
    ├── 4d083d8a1ce6ff736f1f52708a30f622b3657b24.nq.gz
    ├── 4d953a9f9e0aa8504f2763f42184bd393cf61f95.nq.gz
    ├── 4da082f7be6dd60e1aa7bd4dc62f788e7c67961a.nq.gz
    ├── 4e500b5ab429d1286293244a35432c59ec9f2922.nq.gz
    ├── 4ff77007d7b1e07b8922b04f2326c2e095d632a3.nq.gz
    ├── 500142b6b89f220f37fa9a8cb97c5af37d7fae0e.nq.gz
    ├── 50127882b1a9fee36328228a607118e1eb013ac9.nq.gz
    ├── 50f61fbfbc8f2f3b4953498642a763f012d3b41d.nq.gz
    ├── 524f35063edcb7620b8027b5e4b75d284499be6b.nq.gz
    ├── 53278a0d624e93487f544b548d8487335ae3f139.nq.gz
    ├── 545ecf07e626e8ce8f3a98e1c69dc252ee67f5bb.nq.gz
    ├── 548579d50564adae264dc5d77935080373f53671.nq.gz
    ├── 553afbea1ee94aab839947bed668092ae562bed0.nq.gz
    ├── 553e239d31b25d60b610d38fee74970c40f35511.nq.gz
    ├── 554a699a413f964b647fe7aa3ed54e96470655f0.nq.gz
    ├── 55d2570b11152596ed4bb8062e32e73daa78b7d4.nq.gz
    ├── 562efa5261f7407049a7a0407886c6a37982c399.nq.gz
    ├── 565d01689b15f949d24dc6b593300e02a79913ae.nq.gz
    ├── 56e8fd1e6a04cbab3eb83455a00525c2b4eeee76.nq.gz
    ├── 577d3e1f89f5fca4be57b6e30d4d17264bf4f3de.nq.gz
    ├── 57b3ade951e65d63d603e4370687aac66541a4f7.nq.gz
    ├── 57fc17a376f824f65ae2e3e00de99df76562348b.nq.gz
    ├── 580ac1cfef219bd3f18ec711fde4eb3579719815.nq.gz
    ├── 594ccf40b9ca4ded07e3847d75d565a8e98b65e6.nq.gz
    ├── 5979fa8682ad3eadb8389c7c73423f0a595f3546.nq.gz
    ├── 59bacb0a3631133ccee3694de10c99491217f3af.nq.gz
    ├── 5a88253c87a224af07a657638592afcd62c5fa4d.nq.gz
    ├── 5b105c3fe9c18950ca9d37631b37e6f04a098e6a.nq.gz
    ├── 5b294496deab106f1f02b0cb09ac72e099493a3e.nq.gz
    ├── 5b5951d3d349792894f8e603b3dcfff649664919.nq.gz
    ├── 5ce896e044608c4903fad38938498d510d92f833.nq.gz
    ├── 5dcc2366234bbf4bded3dea643541c0c8ba01985.nq.gz
    ├── 5e58a6cd564d343ad99d5c8f6d8d3f7d3be4a59c.nq.gz
    ├── 5e66a16370000bb0c2fa497a13fe52960b17c5c6.nq.gz
    ├── 6024e296a524e22376f12b734e6769331d2b9eb5.nq.gz
    ├── 611edf8a52e8d40ce4f23553d5a30488cecf889c.nq.gz
    ├── 621acfddb7fdd5be4cbad36fd0ed35e7d4bf2ea2.nq.gz
    ├── 627bc5c89dbd728361d236b3e35f38708bffd8d6.nq.gz
    ├── 6290dd5c65dc680b05393c30b776389619ba94f4.nq.gz
    ├── 62d57b913a6176947659ba9525ef716f5d6c96b7.nq.gz
    ├── 635c6307a504e5bbef545cf4bd0071241596a31f.nq.gz
    ├── 6380199902d13b3e78e0e2127072f8b97929f207.nq.gz
    ├── 63d8d0ea9e3e56caf0a9dc9e1fa1df6859e7bbdc.nq.gz
    ├── 644871d51484af2082a182126aeee8abea2d07dc.nq.gz
    ├── 65369adbb027935f4f87d13fca0ac4ad016429e0.nq.gz
    ├── 65c326c3d8d94b5ff6d0e88f81d25c84630a39b8.nq.gz
    ├── 65c662a1ac1e787de056d97d43ef7508a68c1441.nq.gz
    ├── 65c790f087b3c8742ce0856e296c5fc931e30b39.nq.gz
    ├── 669499c12cfa36af7bb68f567288c1b8c764b2ff.nq.gz
    ├── 66a80c681655863e1616f0bb1baf458f9327cd7c.nq.gz
    ├── 677d7735706f5c1b3a0af38f3230a30691bd07a8.nq.gz
    ├── 6812fe5d52c3ff4e330f26bfb863d726d3914e70.nq.gz
    ├── 6851f21ac41464fba93fc5a02cfdcd109a9db314.nq.gz
    ├── 68c37e1341f8b1480c4b33c2b33b0c02f271f844.nq.gz
    ├── 692d9b7b94234bb89c2a8f38d891e0e5ad3ad9c1.nq.gz
    ├── 693c779432eea6ba3d1ea69f11afbcb53dfc3fe3.nq.gz
    ├── 6972fa4b42c0573226fa831bf093e3731d3b8ba5.nq.gz
    ├── 6a3cc4f0366ef62cefbf9b164fc3527d2bb74d1f.nq.gz
    ├── 6a415dd5e053f67165d0e533e3e5340034bfb478.nq.gz
    ├── 6abd6d363562e0d3cbaf59873c715bcf4507ab3b.nq.gz
    ├── 6ad643ef5108cc0ae9f78580c44c3ea7ae677b13.nq.gz
    ├── 6ad8bf2c1fefc86399c6e443dc0e79e22510a6dd.nq.gz
    ├── 6af33d8d287dc047c8ae8628c35741006e39ca70.nq.gz
    ├── 6bf9d633da9e2c001c3733541dfe6139de93d1f9.nq.gz
    ├── 6cda43e948b04f0b1104517d5c6f388919c2dc25.nq.gz
    ├── 6cda8e795c514005c49f6cc9f3e022488fea594b.nq.gz
    ├── 6fbe1c4498de187664797ec08d5b34dd753909be.nq.gz
    ├── 7141d031e18429fb81d17cb00140dcfdecd7a2bb.nq.gz
    ├── 715b87a4610e5ae7397d46c977219153f0fb9ce4.nq.gz
    └── 726a3fb1a639fdc38487bed4eb76e053d206652b.nq.gz

7 directories, 200 files
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

[modelcontextprotocol/csharp-sdk](https://github.com/modelcontextprotocol/csharp-sdk)

---
*Parsed on 2026-10-09 by [repolex](https://repolex.ai)*
