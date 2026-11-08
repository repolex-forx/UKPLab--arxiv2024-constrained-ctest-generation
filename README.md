# Repolex Knowledge Graph of UKPLab/arxiv2024-constrained-ctest-generation

RDF knowledge graph data for [UKPLab/arxiv2024-constrained-ctest-generation](https://github.com/UKPLab/arxiv2024-constrained-ctest-generation), parsed by [repolex](https://repolex.ai).

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
rlex download UKPLab/arxiv2024-constrained-ctest-generation
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e512c1ca29b98554880227cefdcf7b43125df57a
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e512c1ca29b98554880227cefdcf7b43125df57a
│           └── chunk-001.nq.gz
├── blob
│   ├── 0007418ce3fe9fefad13ada294f7ddb752c910ef.nq.gz
│   ├── 01807612a8b4b2cda5f8beb26e8484a958b46e45.nq.gz
│   ├── 03369e64580fe10d23029b0cf2d7eb9808074029.nq.gz
│   ├── 046f45bed53fc60769c7e4336f64750b69123f49.nq.gz
│   ├── 071c6111416804450a9a7df1dbf296e7384f3cf2.nq.gz
│   ├── 07236e5d30ef5fe7899c066e95ea41052727cc9b.nq.gz
│   ├── 078e1329b343e4d753359ae3253844e452fcb7b0.nq.gz
│   ├── 094b68ddaffdb68e1d69bf4284bdeb328c6d4277.nq.gz
│   ├── 0a911ef9925581b3d2ac585d4cce984c24076676.nq.gz
│   ├── 0aa123d01aa629af787981900e7a34bc459069b2.nq.gz
│   ├── 0c61136c90c3101c46f6ecea290c7874fc11913a.nq.gz
│   ├── 0e6cdaba07c554b9d408c7c731eabda3a3df0a0d.nq.gz
│   ├── 0e76b539f8001fd80ca16d05b06693c7e0893236.nq.gz
│   ├── 0eb3a752b77bb024dab9d790d49df4c1cbe89123.nq.gz
│   ├── 10328528d827f39c52be059244714883685477cf.nq.gz
│   ├── 1035c4e0fdc8b868d6d57be713fce0fb93f21196.nq.gz
│   ├── 138b37d5306693b942475af1f73a40d4a4094428.nq.gz
│   ├── 13d8d9f85e5334826afc112d3f7022d1c6f8dd52.nq.gz
│   ├── 14f983b60ef54e829c3b0ba9c645f893b7ad3878.nq.gz
│   ├── 15fadf295285d20f928f773d48dd8d6bcbe27b65.nq.gz
│   ├── 1820b4852715098783a4782c7668578ee62a9283.nq.gz
│   ├── 1bc85164d07f3c0d8153b950f9a569af94335d3e.nq.gz
│   ├── 1de5ea473148c5aecff88c7885cdb5486c8301ac.nq.gz
│   ├── 1e0a56330afd5b577c70b4826b2ebbed728cfb17.nq.gz
│   ├── 20bdae426f8bf99c4f14788e840c11c82fb181f0.nq.gz
│   ├── 21439cd90d86d6cc0cf8042197db931116169715.nq.gz
│   ├── 21f21097ec429d05e2a1534fc78d4949f0230ffa.nq.gz
│   ├── 2279b109d01bca158e74e9791ca71c84050348fe.nq.gz
│   ├── 229db85a3a208e74651828fa18472c8f538643b5.nq.gz
│   ├── 23c9f426295ee9bd85d19f7aa52821b82624749a.nq.gz
│   ├── 2800b64e64ec6c9e03829f8e465bc98fae3941c4.nq.gz
│   ├── 28070a4dd3e32e42b0a48fa074bedfa5aec56de9.nq.gz
│   ├── 281a5d5cf721fae1c19edfacff22069c08fe5fa5.nq.gz
│   ├── 29533f34d6b996c3aaf639253aacb4aa7fc2f92d.nq.gz
│   ├── 29fe2e4051dd55038f8c2698f1445816c188362f.nq.gz
│   ├── 2a23b99e16baca10027edbcd76949b8769818fab.nq.gz
│   ├── 2a85a3b459080acdfa8719cd4a0a9db40bb8709d.nq.gz
│   ├── 2e1dd9be88f3561fae552945724c43a0a48c1e6e.nq.gz
│   ├── 2ec601f4ed4174a1c44ca8a05c8111be7b88a4ae.nq.gz
│   ├── 2f0292f8bffb023ea57f4d69b8990c6f6f1af322.nq.gz
│   ├── 2f82948d8a19f1035492a07b40d08e0deccc49dc.nq.gz
│   ├── 3045c38283b40ba7f3452ff9f498bb0416a7804f.nq.gz
│   ├── 30b9c253f86eca1659676654ee5582656c492a3c.nq.gz
│   ├── 30f36241876e38a0ba721a7932ab1364f9b0ebab.nq.gz
│   ├── 32440545a0ec33be56e05db179afc6321c345c89.nq.gz
│   ├── 325b67a2d62ee209ca022087db7ab6c153ce436f.nq.gz
│   ├── 32ff1b773869e1f60f0039c98d128e4b9c156959.nq.gz
│   ├── 375554545d999b3558977f73f5e9081e3d36ebcb.nq.gz
│   ├── 3b31b3d2b199f6f8ace712044819a85182381603.nq.gz
│   ├── 3baa4515da84b464e18d0e465137f026a6e0e720.nq.gz
│   ├── 3ddd0d077b6f7eaa9c1231197683c55eb200db27.nq.gz
│   ├── 3eb65c9c0081da3b30953a77f0b6f2d343e4d1bb.nq.gz
│   ├── 3fd11bdf7ed96df3356cd3ba75b5472798f005a6.nq.gz
│   ├── 40b175478affe3734eda2cb28929b54bf69452ac.nq.gz
│   ├── 42445633a00f5278fb853133027861dd5dce3173.nq.gz
│   ├── 44fa874dd43f7811fd92fd3efc5c788826f77e4f.nq.gz
│   ├── 4628b4418ca62812cae2132f9f3c6d32532f34d9.nq.gz
│   ├── 46e3b10ad5137224942d7e2c3db30587e28fc125.nq.gz
│   ├── 47563227201660905d5f14a6fb01708f6965e3a9.nq.gz
│   ├── 4cde51c2ef490811eae26caf70f1130a66c709a5.nq.gz
│   ├── 4cee999d12a31ef2d5c40728eff3236a85351498.nq.gz
│   ├── 4d6590305b452f8f68c82153aeb005020f202f76.nq.gz
│   ├── 4f28c33517348b3d2aa63510e010928de33137d6.nq.gz
│   ├── 4f9d4b44f7978be98fceaaf13079eddef3dc752b.nq.gz
│   ├── 4fe4e21a81a41304913d07f7e62d9d6f20ab126d.nq.gz
│   ├── 51464aefce3b774c47edefff11bf151f96bda831.nq.gz
│   ├── 5785c9d7488341955694d543053a5d4ebb2b7578.nq.gz
│   ├── 57d883af285f3e8d1e37762cee2f80a13cfae855.nq.gz
│   ├── 59ca139ead8ac2dedbd83c2a4846305e18de900b.nq.gz
│   ├── 5ac435c0667052470b11a06f8848767d2e77466f.nq.gz
│   ├── 5e49534b500f875a5b8db01eb682e6614b80db4e.nq.gz
│   ├── 5f246e5cec21ec24c5f96185c1e091f4c54d7c02.nq.gz
│   ├── 5f2f83661ae5de80e27a48b2fe6791d3d7f32b7e.nq.gz
│   ├── 5fd10d3a455ddd1a9b1a0c9f54bc78ffbdc357c1.nq.gz
│   ├── 60d6a4f3563657984a4b40348059d3d8e5734ca1.nq.gz
│   ├── 63884fb9a76350a69f7861345392e1819fa4ce52.nq.gz
│   ├── 6583ccb0fa53a0e56bc033e22e02b25af31bab1d.nq.gz
│   ├── 660c192766dac1677d5b969dd11f68efd5f22076.nq.gz
│   ├── 66d1fefd4bec7ca08c68d0aed8ea858c89f1fb68.nq.gz
│   ├── 66f57b79549704dc83ba3e197b2bff4385f2ee5a.nq.gz
│   ├── 676caa8fe483c0b8e4f328ed013cf73349422985.nq.gz
│   ├── 6928fcbf13bca39aee15791a5c89394eda77d907.nq.gz
│   ├── 6935c0036a67974615ea475002e4b304ec26e0b8.nq.gz
│   ├── 69d6fcc3b46d856e46c3bc3a1715a18f3481a117.nq.gz
│   ├── 6a38a4f64ee9e5cf8b665ab6c82f2fb0995283e9.nq.gz
│   ├── 6b37cc7114a58d9e8cb012798e8755a6f3e4816a.nq.gz
│   ├── 6d4a9c62c0e222021a71613e7c85f80637531f5e.nq.gz
│   ├── 6fd6bc1017097f2450765288f01eddcfec36a477.nq.gz
│   ├── 6fea6c53f8afffabfe2b050b390314cf999853c5.nq.gz
│   ├── 705334b32de5add45d7da01f2b2aae0f8da2adf6.nq.gz
│   ├── 71243313ed85e1e0f63e491b2ee729b60f10a134.nq.gz
│   ├── 72c73655b812082d7fd5adfb3dfd2a90b792aa1c.nq.gz
│   ├── 7c27a6573b29b957003b3416e21b7fefa797c470.nq.gz
│   ├── 7dab1552aae4293b9866185ac13a910332194d52.nq.gz
│   ├── 7fefdc17be1370f8f88a75f5d284fbab5f6beee0.nq.gz
│   ├── 8099ae32d7b946940eeb9b84f9423f786e25c4db.nq.gz
│   ├── 80f790827e6d49b96232b50e9d9e96ddaf4498f3.nq.gz
│   ├── 83845fc9472fc0c99ff92a8e565f5e94e1f6de4d.nq.gz
│   ├── 87241ed14e82756474eb8ab6d707b391ea3af32b.nq.gz
│   ├── 877d055abac30ee1157e860350d88c515d4831e9.nq.gz
│   ├── 892389edac6a95163cb1294402e02c62bf98f231.nq.gz
│   ├── 895ec7d405914035271fb1cd89e4b0faa5ae107c.nq.gz
│   ├── 8aa0f2d1f984a07c27487c4c26b22a462aad8b60.nq.gz
│   ├── 8ace55867d4d5b36bbd990ced62473fb928dfdca.nq.gz
│   ├── 8cfb7c508798febd6aa255da662ce4f7c6c99f76.nq.gz
│   ├── 8db319998da29639a3abe203d28f0b0c77e4b124.nq.gz
│   ├── 8e39200918ca38a686ea4bcf87f46e072b557b20.nq.gz
│   ├── 8e398a70efa798665c6ce660dcef639c4b5d3f81.nq.gz
│   ├── 8fd2db7e482d008f05cb4c61cb3584b236de285a.nq.gz
│   ├── 94e3d5c09c43b769efb9b9f0cf15c1cad70cac2a.nq.gz
│   ├── 959fc31c5c2bca5a58b2b856ba63862c44006586.nq.gz
│   ├── 95b9ce21053b3829498e8ee3824649ee14412ee7.nq.gz
│   ├── 96272a80270c15f8400c09d227fc533684693007.nq.gz
│   ├── 96ef987f098d8f58eadee2075f16bc1fb70fa100.nq.gz
│   ├── 98f30ec47bf58fb3b09bc156b819795e5cdbd4bf.nq.gz
│   ├── 998ad1836e87570d5b95d19deb9f16ae4040e0c3.nq.gz
│   ├── 9b510079a92bb3ca0bd92f480056cf223bd708d3.nq.gz
│   ├── 9bf5fc8f6b77d7d11cb5b301529f54009bdb13f6.nq.gz
│   ├── 9c064fb8e6ad02b9cb27eb54f3e5835ec97d19b9.nq.gz
│   ├── 9c3176478257ad77b1bfc6b82632f3d153cad893.nq.gz
│   ├── 9f170bf52048e20f1f1b938df49e3d212c211826.nq.gz
│   ├── a0d144b48d809ee04498f45839448186b690893c.nq.gz
│   ├── a15016ee4000abefa557a545f1db06d7e7256226.nq.gz
│   ├── a36b7b4df7ce0455fb111e6ae5ef9e134ad3b501.nq.gz
│   ├── a48ef02040e51d82ba4f6b78baea6eabf0981f50.nq.gz
│   ├── a4a4d2a9cacaf852bddd1f77e9580cb52ef446eb.nq.gz
│   ├── a8431592f928d046c8e273ecfe840fc5eedfec46.nq.gz
│   ├── ab943eb821e11a8f80a5123d265f95d729ed0ef9.nq.gz
│   ├── ad9a5818da92569e2bfa2990b7e62bca6e07a428.nq.gz
│   ├── adf8e3056600315ab4be9e70656a59377c7c8785.nq.gz
│   ├── b369af1c82edb02fe3a349ee8c291b2bbba650e5.nq.gz
│   ├── b4738e716adeca0af10834908cd6a0868bfae86e.nq.gz
│   ├── b9f35b71a1b7646114e6327a0a29ac5c845a3b78.nq.gz
│   ├── ba4e0837106dcc846c5ae03d82f8ca38707bce50.nq.gz
│   ├── bb46b6dd7e69c30a581ebb0d0ef4794636d15826.nq.gz
│   ├── bbb632ec0a3bcd4e132ad4afcbb44fbc2972304d.nq.gz
│   ├── bd60429a94e87fb8f60763f19a48c64de41a138e.nq.gz
│   ├── be6780f6757fba18f56ab2b17fb1d6d1f76b1c27.nq.gz
│   ├── c053b23b3cb258e6722daaa2b8d43fce24bdb16b.nq.gz
│   ├── c1e5a986555fa59074bdf713f55f91690adb2a0c.nq.gz
│   ├── c4c1b0c70b7347fd04c3f013d0a1c5df8cc01d6a.nq.gz
│   ├── c53ddd00016c6ff83c63eb148dd32a2aa0367037.nq.gz
│   ├── c5ba53b7052f840e3d0f1e802143b7aeed6d726d.nq.gz
│   ├── c6149d55b876a9b141d73fcd237be29bf1580a0e.nq.gz
│   ├── c63204eef373fb2c53650992c0598be21b02c198.nq.gz
│   ├── c6f900a4f80d456781ff6931e18eb83e290fbca9.nq.gz
│   ├── c9b4e4239baf5fc62229ec37965ae80d1994dd65.nq.gz
│   ├── cb47b4868d159fc9e191c37af8b9256b71f48833.nq.gz
│   ├── cb9086a31d28362d9d7a0551610a47e4ec7ec0df.nq.gz
│   ├── cc117811f878cce7caf8fa31d8b49461599db3c5.nq.gz
│   ├── ccd8affdd1b57ad257e79f8bb9200d7b5979d509.nq.gz
│   ├── cdbc81c1a41fa5c03f4c35864cec7af8cb5ad29a.nq.gz
│   ├── d0563a4f2dc15d293360f722f158bf857ad40a4b.nq.gz
│   ├── d07df8088984b6061267e14a2664fe42d796c06f.nq.gz
│   ├── d0b574a56584f3d1935d3b082fbd811451a359b9.nq.gz
│   ├── d0de75347fcf7e19c4c65b4d41747d4fc7ee735b.nq.gz
│   ├── d2a83b33e78678867a9eba92b9b65cb88a00d275.nq.gz
│   ├── d2db9892be8a277930819744ed3e9ef19bfd0e95.nq.gz
│   ├── d2dc68c9a683d9800b59c9e37bb849a75c150e1a.nq.gz
│   ├── d32bc9d0da106e748d6e29ddaf8153e4a6c46d3a.nq.gz
│   ├── d52364336f563e03ec5ee62015f5d90ac9fc78ba.nq.gz
│   ├── d5420ab7aa100d53b249fe8d5246906be2273c6a.nq.gz
│   ├── d63bb671d58c6095ea50677cc405779891517e76.nq.gz
│   ├── d6b7876e96a252bf9ecf8031d5fe5b2d071f9975.nq.gz
│   ├── d7e7d620bef8070180c77b1aeff8e897ffba5d49.nq.gz
│   ├── d8932f82bf7ac29d2dcfe926231255b7d8476825.nq.gz
│   ├── dcd5931b895594da9a0bd3a7980e35d5cf0aac4f.nq.gz
│   ├── ddb17c66a6dd09c250f3001ad07c23a7c77789a7.nq.gz
│   ├── de196601d0bd5a40b0f97f1997b8eb50c86b9508.nq.gz
│   ├── dea19c8cd2e0c42bc883698eff0bb8b4d2913609.nq.gz
│   ├── df9225c699e2dc109453ceec3fdcfe3c2702b906.nq.gz
│   ├── e2f45f3d520773e212ed4f0d5c69d682373c18e8.nq.gz
│   ├── e3ee3b7256d12a43f9063bc0a0121f17ebb7b068.nq.gz
│   ├── e4cf6626bb72016f444014aee07849fe20210d27.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e9a0e3249e240d9bef639f1e07f674c113a67b7e.nq.gz
│   ├── f050d88a1278ffd6e70df3a6328c3f1dae9350d2.nq.gz
│   ├── f072bdee42bf19a1346d50cb3e0bf1fbe66ce11d.nq.gz
│   ├── f0a81af994befbbd54b92bf257d88feded72a8da.nq.gz
│   ├── f1c2492b7e27460a22ce0d9a9ca4030e91b24b59.nq.gz
│   ├── f30c1a209cecb7eddeb70de3cfa9c2c8a9f46e31.nq.gz
│   ├── f30c4fd0f71cee7789b816ce9e1a2ca726517149.nq.gz
│   ├── f59013e7b0be6f0b3862c9e005d6729f6c7dfeca.nq.gz
│   ├── f6000aae2c14c34ab86a594a86100fd989edcd55.nq.gz
│   ├── f81ab56ba9bcaa7c89266822a1d1865af953e775.nq.gz
│   ├── fbcc17e0e1c2a9c3f7f880907846ee7f920bdcc8.nq.gz
│   ├── fc7fb63e1915c747c8425e7bd375caef0f7784eb.nq.gz
│   ├── fcc3d8f9f8acd3e6d420a5ccfbd87e7dce5c0258.nq.gz
│   └── fcce4492f05360cb3b40d23af480e4dd37032b64.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e512c1ca29b98554880227cefdcf7b43125df57a.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 195 files
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

[UKPLab/arxiv2024-constrained-ctest-generation](https://github.com/UKPLab/arxiv2024-constrained-ctest-generation)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
