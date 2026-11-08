# Repolex Knowledge Graph of qdrant/api-reference

RDF knowledge graph data for [qdrant/api-reference](https://github.com/qdrant/api-reference), parsed by [repolex](https://repolex.ai).

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
rlex download qdrant/api-reference
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fae554bd89b6f4350144b7472243ef25b6edb7ab
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fae554bd89b6f4350144b7472243ef25b6edb7ab
│           └── chunk-001.nq.gz
└── blob
    ├── 0012cfe0be2951a35a39f38a5bc31fce1b300201.nq.gz
    ├── 01b5f0b68cf2b9d69870cda15a33ba13295844e8.nq.gz
    ├── 0260738886d177fa6b71556b94e50f5b3f36b284.nq.gz
    ├── 02b3aeb26cd366edcdfc2997e21ebdd5df13f145.nq.gz
    ├── 0339b2d97d84df48d35a832796c9cd35574e4371.nq.gz
    ├── 04044e6ccf7f0ef4bdcd491ba4486240aa7fabc0.nq.gz
    ├── 0651184bed3a343c4ba1511ab9a2f6d6c2ebf552.nq.gz
    ├── 06d4a3f216f080dca218061bcfbfbed4846560a3.nq.gz
    ├── 0814096fb8ad193b875566b2226b725c939cac8a.nq.gz
    ├── 08218611d5ca7bd011fcf759c126c4628f5db85d.nq.gz
    ├── 09fc33c68e10a9333a66ae2d5d8fa6ae74b63409.nq.gz
    ├── 0ea60756d62dda7caad95809f300e153747534d3.nq.gz
    ├── 0f1a1fe5ba2e1237be3a96dc36f5250ea0757bae.nq.gz
    ├── 0fa8537895aa5af676297789e806931117928a3e.nq.gz
    ├── 10565dc10db7d2556fd26acfc03729ac7bdae966.nq.gz
    ├── 11670eba9074268b9bd5f68ef366a712ed225806.nq.gz
    ├── 11fb2164fa67a5cf00bf12150f066fece7bc1eb0.nq.gz
    ├── 1209d60f9a9c2373f20ad3f8d5c9fcbd91eae6f4.nq.gz
    ├── 12fd19584f43a153b76bc6d4aeaee323d8fb7f13.nq.gz
    ├── 13eb4f7c3066c5dd01e27fa29a90544da3e02f15.nq.gz
    ├── 145f60dd539f2fe95042c74c0e965fb3a414cbaa.nq.gz
    ├── 147959ee6bb5abdbafa457bedac631bab7e1677c.nq.gz
    ├── 187d2208ce9cf1ab02533fe5550634386530c5e6.nq.gz
    ├── 1919be78edaa87b5d69b776ba5c9efa5235dbc3a.nq.gz
    ├── 1ae5050b6e7534bf7c521615ba6da6e30fb0016a.nq.gz
    ├── 1c0eecb1325184431a24a63840d35063ed28c8ad.nq.gz
    ├── 1c66bd121aef6f5eb738397a43cef16b0a246d20.nq.gz
    ├── 1cc6a515129cab1eae52d7c62a51904b09ab57b6.nq.gz
    ├── 1d1485ae69b6b166241821b32452ef2a0abd3886.nq.gz
    ├── 1d415443af77872aeebd34fd8082f171608b9ccd.nq.gz
    ├── 1df1f92244d32bedcd1e91dc38396bd21da1c4ad.nq.gz
    ├── 1e7e8b6b8d3a241f20839d5c5c6e5eca037dd82d.nq.gz
    ├── 1e82e0f099145c89994fec717802e47a059666d4.nq.gz
    ├── 1eff30ba80a75d6b272a4ff32912f97cfc1d4810.nq.gz
    ├── 1f60d60343b1c89c914cc3810fcdd5ff6c0fa695.nq.gz
    ├── 1f7c62d4b0ab8500398dac730e788e0487cd505d.nq.gz
    ├── 202f090b043930303abc05579c46d67594300b9d.nq.gz
    ├── 204a23e29de86dd24338eb3de58a907ec23f22bc.nq.gz
    ├── 207d308cfed6f0e1ad205492ba7aee2f73bd1151.nq.gz
    ├── 208d5b0bbec0f1721d53b6574d7857e17ebe8a23.nq.gz
    ├── 2116fd943c9f1c38c5424f19069c4cd75d07c143.nq.gz
    ├── 2131bf3fb11722c9e7ceff7371e65bbe9bfd1cf5.nq.gz
    ├── 22031a7f6ce9a8994c5c00d6c385276a8d90e69b.nq.gz
    ├── 220e9299211a1db0464590e3ec4063e3304a3638.nq.gz
    ├── 2357c2a349a0b649507ade18d9d2ac80d34e618a.nq.gz
    ├── 23f47db85519f2c7ce652fe361278cb796d7ea69.nq.gz
    ├── 248ae8fb9799222c7d11d8a2670e6bef0574e951.nq.gz
    ├── 2573b79f75c324b8d844e5323c824bd7edd31cf0.nq.gz
    ├── 26ef43008546de45875aa2d437c68aa8420faf28.nq.gz
    ├── 272019e8573bb2324cfe487d00e1401869a5ca04.nq.gz
    ├── 27d0f44b285add8cc9cf107330e8aead552dc625.nq.gz
    ├── 27e29d8a56cd0c95db61abaaeafc465c7eebb03d.nq.gz
    ├── 291f21c37ad618a16e3a8397811c46265dc8d5dd.nq.gz
    ├── 2947373f3d694b67457dfc806e284c5afe794306.nq.gz
    ├── 297782554b2708a29caf0cd4c6ac7d83f61e6c20.nq.gz
    ├── 2992a5f734d82f82d0ac853bd319f95604b403f1.nq.gz
    ├── 29ff951b81e84c4610de47bd7e728e0d3a44bb5c.nq.gz
    ├── 2b4b217ff5dfd488e603290156c5d384e34c4f95.nq.gz
    ├── 2b4ce631447ce56f1a096202598e79ce54969be3.nq.gz
    ├── 2b723cdfabacb882b844fdbe1e81f8b58005462a.nq.gz
    ├── 2b7c507f5a8aaa779b1fcb1a661d073620861d30.nq.gz
    ├── 2bed7053c3ce60ad5ed63e9928698c7f371c4e9c.nq.gz
    ├── 2cb1f10d1fc7adcab48248e3e1e450d89ab0c307.nq.gz
    ├── 2cc7e2d868899c18f4492e9434ec566037c9a3b3.nq.gz
    ├── 2d1fd84aa11f5b13326a72ed16c645556f0663ef.nq.gz
    ├── 2d8df77a376f4d0f6397c33bad1a9931840b365b.nq.gz
    ├── 2dbae08388df5348104de057f0cf243fa0a1c9bd.nq.gz
    ├── 2e326d9a83c5b922ac617c3a5f43c4e2647e4a58.nq.gz
    ├── 2fbb7a34b66bfa06025b23392d0a43482f431df8.nq.gz
    ├── 3052b838e57e1f1842c9235934c76714f060e0d9.nq.gz
    ├── 305540a1be2129b47f482a5bd611b1847f6f65f4.nq.gz
    ├── 30f35607a53f491c1bcb54c713ddbc137a31ae53.nq.gz
    ├── 31017f01631777ad1cf16994b76f5ea3e5aa21e9.nq.gz
    ├── 3145512c265eb129c5cb43626b91e5459e20fcf5.nq.gz
    ├── 32ad541134e85fc840a5d433d8fb286e809f3657.nq.gz
    ├── 32cd39421c27ce2e4f4ae57171199a5a035d1eb6.nq.gz
    ├── 340cfac7dfee37432ee55ae0091961946bf87699.nq.gz
    ├── 3553de7d6d9c0708c60d8636717d52e484f1b5ec.nq.gz
    ├── 3584c380fa473018d32bbdfcda2c50c2ae982251.nq.gz
    ├── 365eeeebcfd73dc06c37a093fc40b4820f825430.nq.gz
    ├── 369f45ce74b68fd0c971e8ec4f247a2f8b06b7b2.nq.gz
    ├── 36ad8da4dbc9aa62142e3ac1f92f90e10a708ba5.nq.gz
    ├── 3759adfbf5b180a2dda1af2f2bb45a776411b4ea.nq.gz
    ├── 37e21d8e74873167249bc9c11f57f4cfc1fb558f.nq.gz
    ├── 39750eafca2aece5e4f1a4e4090d2cf90f2c2289.nq.gz
    ├── 39fe0e5981bf60e13c19ac32fdee7ac276e5afa1.nq.gz
    ├── 3a5c455875f8d4ce0c922553b0da82d1ab760a67.nq.gz
    ├── 3be36ef392f5e839700733e88c67e48cd582a861.nq.gz
    ├── 3c919f5dd6f56bff892498f39e672d83deca07c2.nq.gz
    ├── 3d096f5c00abe479e65feeedf465f4a5193a148a.nq.gz
    ├── 3d1e4a74e0c86d0bce659aaa7770bb1da0a52843.nq.gz
    ├── 3e65de7874cc1c2eecede5ff2e80da2afff1ac3e.nq.gz
    ├── 3e8c5ec7abba7e6f5e1a3963640bf7b66fcc5a76.nq.gz
    ├── 4088ed265c6d04f6f9625d478d4f49cf7741fa8c.nq.gz
    ├── 41996717cfad66a4040b2dd3af553f9b3b987153.nq.gz
    ├── 41e86f27af8d56fede3c3b1bcc33d83f8b38c87f.nq.gz
    ├── 42696c3251fb5a1d4b5f502fed11b7aff029cc44.nq.gz
    ├── 42fa2fceb2223ce0f725c5d9edeec0f35861ab65.nq.gz
    ├── 434ca10f93811668a35762e885a4d9e967b3d999.nq.gz
    ├── 460f89b8f991db8c6afb79b2e344c6324847a357.nq.gz
    ├── 465b435b27c164ee8f5d1d99e47df407175e2fe1.nq.gz
    ├── 48301175b15913a8ec2a02026323da92bc2b36c9.nq.gz
    ├── 492d9156a2902cccd8eaf4cb7bfe7043a85c6cb0.nq.gz
    ├── 49d40730fcbbe95b1f34fbfeb9f853b5e4ce8a3a.nq.gz
    ├── 4a3b34acb5060109f060ca5413b5c03f55a3c570.nq.gz
    ├── 4b3a27c8a3c022799708fc0f38990a9e7f3902ff.nq.gz
    ├── 4c9b2691ef3c27e1da2464ac5bffb0bafa199b48.nq.gz
    ├── 4d803b0411476fcc62d3718caff2dc27995dece5.nq.gz
    ├── 4ddafcf376b5b42778bf90ac7cc392ee60beb22f.nq.gz
    ├── 4f6c257b11a8258d06b63b2044be3d9a35da979a.nq.gz
    ├── 503a85f3c7e1ec2f1e31ff69e7561e59c67aaee8.nq.gz
    ├── 5074535e45add8b44b311193cc21f3c11ec43dbe.nq.gz
    ├── 51508a91455d3afd4ca7e27b60fda3b0cb371cf3.nq.gz
    ├── 51e056b677a13b840fb6162a091e2e24b213b304.nq.gz
    ├── 522baa52fb75a49455812f14e91631d491486b82.nq.gz
    ├── 524e4dd9856dc78d3d2faae1b529fec308a9681f.nq.gz
    ├── 52ad162a9cfd6584f7d273bab8d2c475a407a7eb.nq.gz
    ├── 53ada02316d5dd42037b27db0e861e3a54cd2f86.nq.gz
    ├── 544a02f5590e61041bcb728470c78b4a94dd7f6b.nq.gz
    ├── 54caa6356ecba4021f1b9370386db486cda27f23.nq.gz
    ├── 554648cc081df955788071d7711b215bd2048256.nq.gz
    ├── 55afcf7fb6d40eb3c122601760532837d32c7a75.nq.gz
    ├── 55d6e09f231ea158f5be7d0659549bb758b7407d.nq.gz
    ├── 56775e3ecee0d0aff741ae500431fc1c92e3319e.nq.gz
    ├── 56c6233acaad0e1d0e838f14bee20ecf58fbf6eb.nq.gz
    ├── 572696586a3c7a4c9c4e7fa19957e63841b9f105.nq.gz
    ├── 580358ac7e936fe798d8dda25064ee1ae8bd1a80.nq.gz
    ├── 589cf5010d084cef41a68fc8de4d2f9280c29cd2.nq.gz
    ├── 58c5838e107282fb68db18154a30b2f661900411.nq.gz
    ├── 59ae4abb9d496e3573cd5d994791c052f9339bc9.nq.gz
    ├── 5d24565beaa575585267e6118cc6251550a39432.nq.gz
    ├── 5d6abfd34ef647be8f13806f77363f1b97f424e8.nq.gz
    ├── 5d91f840ccff251b6cf71fcd5afb855556baf3b7.nq.gz
    ├── 5e30f73d86fcbbd5c6559462943347f393e5847f.nq.gz
    ├── 5fae2fb70d0dc3e02ac16c667b27cc5207461569.nq.gz
    ├── 5fe6dc0954afdc87e6916b8d99eccb164c17bb4b.nq.gz
    ├── 616541febf47f222473cf166464f61e56170e9eb.nq.gz
    ├── 6190ea2fd9ad8147bde649eeaa5a8f6975de6cd5.nq.gz
    ├── 6257b6280f81194e755633cd99f4250ae98fa427.nq.gz
    ├── 62de228ae96b31623166dd9a669642e7e3a8651c.nq.gz
    ├── 63181f77ec29b06cdbcfb80093f9c919a0dad3df.nq.gz
    ├── 64107a31984fb2ae66088214d6e3e364aeeb6127.nq.gz
    ├── 6460b6f5c377c6ef18b3c9c572216a0f6ac4bdae.nq.gz
    ├── 6475e0b56a57955ed880ac4e53be0d163bd705ca.nq.gz
    ├── 64970ace9410c0e6297e35527d31a043e269a5c1.nq.gz
    ├── 65420228d49a321cb14e49d651bc47c582b62e35.nq.gz
    ├── 65f3380885a2be64aef89142bea36f9f06690c49.nq.gz
    ├── 665877657753471662a7a23769fe3f04274fe8b0.nq.gz
    ├── 666c3bbea8eda77c0af9e7a17e665414183392a7.nq.gz
    ├── 666daee3ca3618e48a820908bb0c5158ae17e8a1.nq.gz
    ├── 667266ecfaed08e7687548c8cff1398765ea06c9.nq.gz
    ├── 66c7616b90ea7fa967989e5a6b98a3eac2099979.nq.gz
    ├── 67283fa3ed4e64e2e4fa24c0b59009ffbfb81a5c.nq.gz
    ├── 6740b8b483765567131cbc5194607cf2188ee061.nq.gz
    ├── 6772a27387623a0095bedbac8fd8a5d3b3bfcf23.nq.gz
    ├── 68239428e788eda92756e6db90cfecb87bd2abb5.nq.gz
    ├── 6825032c75ae2ed98b6a9b771cb9b905183c8e61.nq.gz
    ├── 68b1620dbeffa5f7eeba0dad3d278b6ce26b0763.nq.gz
    ├── 68dcc4e5ffcef58934d2e68dcfff1b39fc8630d7.nq.gz
    ├── 6a72bcc27223865d77e4747d38b1ce1b9787eace.nq.gz
    ├── 6b88b7b2c31e2d4a8951306a1196e1e18a7a22da.nq.gz
    ├── 6ca5afe1a7c52dc35a271cb93374c5f57271eeb3.nq.gz
    ├── 6e49faafc3a409e72f3433dd3e38b6253b68c204.nq.gz
    ├── 6ec65a907e2d0e1f9d3263108cd6df406671c39b.nq.gz
    ├── 6f3d4b9deb65c3bcf7a62defdaed7c3333819da6.nq.gz
    ├── 70bf19f92831b524de6adfd361aa7195c393a482.nq.gz
    ├── 714ef074b5123678ece5bcf90da86019e6dbbf43.nq.gz
    ├── 729487fa231bf793d804f32541c4118870f218f6.nq.gz
    ├── 72b17075ba0209cad750d50924164ed86618f5a6.nq.gz
    ├── 72f6ca04ab764344e8c8329afdf962aa6ef7c7cc.nq.gz
    ├── 73a396df0fffa68fdb5ce8630534a7b116e93994.nq.gz
    ├── 74549d9c7736339a77496301c92e133f567627fd.nq.gz
    ├── 748403ceaf1a97f417f237c4e2ec6869e14a9ac7.nq.gz
    ├── 74d7faa27d6b461bcc80a4466958e5582462d145.nq.gz
    ├── 74fdea7b4403aa0d5fe56525c03266f26b267480.nq.gz
    ├── 75772d3e2dedbf68b4b14e2dac09b2296e9d3b90.nq.gz
    ├── 7690c374a0da8c6dbc8b36ca921b44f71bed8cba.nq.gz
    ├── 76b01c5402472dd8f697947f555c750eea870d7b.nq.gz
    ├── 774a328551f7279c922460c1f013120c782bf4af.nq.gz
    ├── 7b9c9a2eaf8062ad2431a077e2ea4a3fe10b5f17.nq.gz
    ├── 7bf1a9c0fa101a2fac4df25d2df6aa4e07be506f.nq.gz
    ├── 7c95d5e65759e2b740e4878c76596a1323d87328.nq.gz
    ├── 7cb12005f08f68a779794c5f8afda94e8ed78557.nq.gz
    ├── 7cf444709783de580e33204bb9605ac831b8a04d.nq.gz
    ├── 7da271e09e13edd9bad8f7f6cdf2651ca99c71e3.nq.gz
    ├── 7e094b72e8a4ac6793ba769c1fe4f8bc36c61c4f.nq.gz
    ├── 7f067a729a3f20044d3d1a3e742cf88f0a11220d.nq.gz
    ├── 8008d5511ff8b56f824410e1a8c4ab0092907413.nq.gz
    ├── 80f8308e6db8cbb51ae80669b9917a13bd88dcf8.nq.gz
    ├── 8101155fbd2de84bf275a65d2f210372fedad852.nq.gz
    ├── 8145d174917139c862287351cdcd3b20128c8a46.nq.gz
    ├── 8289df1eaff488382697f2bbff79bb77e427c8c2.nq.gz
    ├── 82c01bf11a8c83af7f250939abe4a37a80bb6cfa.nq.gz
    ├── 832e01a17941674c9dfd67e5e8172d61904eb090.nq.gz
    ├── 834d0c7800c3b7034cd5d7b244ac923b3067daa1.nq.gz
    ├── 83553e290a2b2f081188cc3c6ed6074074f18d80.nq.gz
    ├── 84cd91e1b4d69a36e0b8a9120d46e23d9b080bb0.nq.gz
    └── 865860c9ae92be5418006f07eba6aa003911115a.nq.gz

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

[qdrant/api-reference](https://github.com/qdrant/api-reference)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
