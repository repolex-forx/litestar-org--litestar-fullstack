# Repolex Knowledge Graph of litestar-org/litestar-fullstack

RDF knowledge graph data for [litestar-org/litestar-fullstack](https://github.com/litestar-org/litestar-fullstack), parsed by [repolex](https://repolex.ai).

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
rlex download litestar-org/litestar-fullstack
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 90e074e12383209716c68b98a74982599e477900
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 90e074e12383209716c68b98a74982599e477900
│           └── chunk-001.nq.gz
└── blob
    ├── 004fde62d4140ca74bc5c23bd36a4fc113ab4749.nq.gz
    ├── 00d5f62510645464a6a762e877c20b4889f9b143.nq.gz
    ├── 02c47f8f97d58e33e21952ca36956a91dfac1a1a.nq.gz
    ├── 0416ed03fdb82199dd1a00f3002cf5b85418e381.nq.gz
    ├── 043ae1aa115fbb8848e95c74465d2cc5af0fbe02.nq.gz
    ├── 04890cbf51a0de7c00b271d4ce23c7b0285fd51a.nq.gz
    ├── 055b75bc9c879f3e2cabed19d942a6bb0cd62c59.nq.gz
    ├── 056edf811f66cf87ba790da4dc64980e75b327f7.nq.gz
    ├── 05b32c8e40a92a817f7affab6b3e01ce228f1e37.nq.gz
    ├── 067a6243268a672d4cc21304788f5fab5bd29f39.nq.gz
    ├── 0713164c5a4146a956259d6eeb42d9bf9b75eb82.nq.gz
    ├── 073a83cd1b46a42b3f5d598cba161b8728d6deb5.nq.gz
    ├── 07b687d5f04d85eb87eca7f18b6effeb0d39d170.nq.gz
    ├── 07e99e101347daf84dd07a63c8fe12b893cdb377.nq.gz
    ├── 0897ba15bcad3e04a1dbb8e5f1c114ea3a7ad93a.nq.gz
    ├── 0a8bda9a5aa1bfc038ff4cb09d7c95a7bd81320f.nq.gz
    ├── 0d57df20c54600c00fdef3d4b7e676926ec6bec1.nq.gz
    ├── 0ddf1cc3af719c6dd8049f49a2b2a37c1e29efd5.nq.gz
    ├── 0de89e8f4b3ab6a0b691f3d2dc74f71fc4109f80.nq.gz
    ├── 0e79dce236878dee353fe17a618f8de605c1b810.nq.gz
    ├── 0ee0f30a12810719df4ec45d307b0a91a9d95d9b.nq.gz
    ├── 0eeffe7e08851274e563b163211683d49c177b9f.nq.gz
    ├── 0fa1a176ad86e2a9aabd36e914a2d919e7015668.nq.gz
    ├── 0fc5c75a52e2a8f6fd7a24033c7ae3b9f5633b31.nq.gz
    ├── 108294bc7818add6fdc273dec1b9e403125dfa74.nq.gz
    ├── 1088e6c2c45566d640261a4030774b66ed1ebdc6.nq.gz
    ├── 11fcbe96505e4148bf8bafd3020aec4181ef3691.nq.gz
    ├── 123014908bebbfb7ecfa1d15daaceb272fabe05b.nq.gz
    ├── 133e57da4eb23392406f534eb222126e0d20773c.nq.gz
    ├── 1341a5e8fdf86ea90b2a56aa9d5762bb509e3507.nq.gz
    ├── 141124395f7f9d31f5bd9f6f82f97bbcb52d60d2.nq.gz
    ├── 14500e38462f013ef547034a9a6f6493e0438d50.nq.gz
    ├── 148d0a6a7f714b2207409b289502e83e8cbd0229.nq.gz
    ├── 15db819a2f933100ccaa8f4762ccce460549dc86.nq.gz
    ├── 165757b1b92dd9b97601501f860453bbfe88fef4.nq.gz
    ├── 16d02b09430be2a6ff09a0df34dbb32eed3446fb.nq.gz
    ├── 17424ada041dd2c0b765f3fd7837c83eb763d66e.nq.gz
    ├── 17ca121e51117749aaa97d4230a144677b5bd12d.nq.gz
    ├── 1800c5311a1309163b21cae196c7d21a4c2b87e4.nq.gz
    ├── 1828d849e12ee7182a45b577c8a621e790b508ef.nq.gz
    ├── 18af76373e4b5acd06b27475fa5c39a2449a8163.nq.gz
    ├── 1b05385e43ca89e7049a5dce42f9fac961e49e67.nq.gz
    ├── 1b7f76a0018db798e014f7127be3143bc0facb48.nq.gz
    ├── 1c7822f5636056e16a28f01acec1e9ed8792c8e5.nq.gz
    ├── 1c82edf50b73738c4c8cb8779853886db87fb6b2.nq.gz
    ├── 1cac98a533c23a5099ca706c1ff592ba6df0d832.nq.gz
    ├── 1ce39690c6edf16e73eeecf048d41d1fe5e85b1c.nq.gz
    ├── 1e27914332b3396cb9495d612d2558b8251f695c.nq.gz
    ├── 1e7573e916d7daef239f57c5c68b6b37203a6da0.nq.gz
    ├── 1ea54faef10e227acd344bad72b1c168d8d9c567.nq.gz
    ├── 1f4daf595a0caa6ba44e7b5ba31bfbb8f10e7dc4.nq.gz
    ├── 20a4fae47ac8a4b7da4676c13c2f3126c5d484d5.nq.gz
    ├── 210f42b40587c4555898dfccfdae891bf6cdc89d.nq.gz
    ├── 2201a3b52fbae210062de8c3238fdd9a08688c95.nq.gz
    ├── 2260c4b8c502587f125bd20ccb46a5e3cc6d0dfa.nq.gz
    ├── 22c5317ec6561c57642e19c5634cc6f42fe718a7.nq.gz
    ├── 23d86b2dc90d78faf002dd80bf703e19b82e7807.nq.gz
    ├── 23f297fa784a734b970fa7491e46de8ad60bb65c.nq.gz
    ├── 249dc4ff6c90bff803a86caa89e2b1c802a9e296.nq.gz
    ├── 24e66ff4b467ec11e286c8348583184188acadab.nq.gz
    ├── 254af5f033f01d1ab1b69a5569fe44a79b3231a9.nq.gz
    ├── 25e49a22567e121c5ebea28871f35e797b77c355.nq.gz
    ├── 26b33a3ed39eeae5c156653578da1065a14b37d1.nq.gz
    ├── 2760aac7f75dc66b71daf9b49166a1d2ccffe178.nq.gz
    ├── 2794bbba99906c1403d623a44bc8c900ce9232e9.nq.gz
    ├── 285bf3ef4d9f87b1015be381e563c2835c6f3e72.nq.gz
    ├── 28df2449c84d55d5b6a444f5355dc4f28e17230c.nq.gz
    ├── 297b7de384d6be32c337950f1e5a3225eca5895c.nq.gz
    ├── 2a12e69c0827e795d306ff5273fecfa9cdef8360.nq.gz
    ├── 2a72082b8c380bc49ba7f9be7f63a90d7167ab7c.nq.gz
    ├── 2b0fe1dfef3b17850bbac040665f514a8ffd0f15.nq.gz
    ├── 2b4e02a9c591dd8164a6ac195576cbd664524135.nq.gz
    ├── 2b645f467e73958bda42c8d71617bbd8f76d0382.nq.gz
    ├── 2bc68c444e9a62cace3eda363ddc0d3d540065cd.nq.gz
    ├── 2c1879afe45dce4575a89763844a29a0d1e654dd.nq.gz
    ├── 2daede995bdac0723791bddf117699641080d007.nq.gz
    ├── 2e81f3f6b61138c81e4fd32f12294de60c4bce88.nq.gz
    ├── 2ed9d6d4e6fc07c1d3399a8d16ee15c50ab8766c.nq.gz
    ├── 2f06816485f956338a161db9646a55d729c69a25.nq.gz
    ├── 3029855c7013bfd737d17e2fe9d0f6a9ddb85bb6.nq.gz
    ├── 3076d98a99865329c7e125c9f2dbb51c4991a79f.nq.gz
    ├── 31abaded3a87bbbdda8247e9c77dfd90f64ffe85.nq.gz
    ├── 31dfb195e6c616547311e465195986ac770a2f9d.nq.gz
    ├── 32a5c921a6033b157d270c83d3d1fbcf4e84ab43.nq.gz
    ├── 331a38b8832375a7cb297398d0bea3415b2f987a.nq.gz
    ├── 342247cdca56d55e3009a704f4ecd17db1ff7366.nq.gz
    ├── 35b3767422e0b667a8bd8319d0deca361e4aca22.nq.gz
    ├── 35bf2940c620284d1ccdf41edf7ed67b01aad324.nq.gz
    ├── 36314c929f2174deb9d6804a53bf924057a19df7.nq.gz
    ├── 37361fca5d489f73ee2e2fd528d61e8a55609d45.nq.gz
    ├── 37a4f2eebc56d61c4d47b72c93855338269d192c.nq.gz
    ├── 38ae440d805b30aae6cb114a9202d16da77764df.nq.gz
    ├── 38fa94d1ffc0c719498fd42002d47825b58154cd.nq.gz
    ├── 3911500f4309c1b4abfb8e9b5e8744019202a513.nq.gz
    ├── 39842c407b0f0c88ee6ccf70f5eda97e02b257c3.nq.gz
    ├── 39d0ca9a46c26d1280a7c7e299ef64117d25a167.nq.gz
    ├── 3b7c13c20d8ffb35e065a85e4920459b565da170.nq.gz
    ├── 3c4c85a59c49ef9096df47773ea722484dcc3471.nq.gz
    ├── 3c71bfc0af57859671a47ce47047a6761bef677b.nq.gz
    ├── 3c724a8389b339b4708b613a8f8903bbc77e2bfd.nq.gz
    ├── 3d651320ddaac0ea07c02f0567c7ea711631d8cd.nq.gz
    ├── 3d6e47acaccd15a414e4086ba89599cdc81215c1.nq.gz
    ├── 3d7411517cd4bb2c39f8fae79e80cd49e90a6a1e.nq.gz
    ├── 3dcb764863b129081e5db10c3d86c8d83d244f12.nq.gz
    ├── 3e561fbcce767c543198e7b98a927dcbb5c40ab3.nq.gz
    ├── 3e83d60b4e60424479080f0ad523b4d1f37d1ff7.nq.gz
    ├── 3ec1e795f7c415d2cefacc2b40e1e49234d05196.nq.gz
    ├── 400cf8189270fb221e035b98a0c93a87a88b1cf0.nq.gz
    ├── 404bb5e379acf62779e000738213e06a030857a3.nq.gz
    ├── 4151cba64b9cd717e3c8fc2cf3f048858c0c15d7.nq.gz
    ├── 41c23069b716b593863b8dd480126277a1e28044.nq.gz
    ├── 435cbe4e9c50c2ef60cf769932c6cde567b447d0.nq.gz
    ├── 43ff22641a0303bf155c8b2a69be1328e371446f.nq.gz
    ├── 44512f0d0c20d4bea744fac6803ab273d63a8ed5.nq.gz
    ├── 446cc5a02a75913019ecf35a676b6afdb62989c7.nq.gz
    ├── 450ddb9362b0d2eb494f105a1b3aee45cc197ba1.nq.gz
    ├── 45289ac16d948bded87712e05ee5c6f8c6b90c61.nq.gz
    ├── 45d347eec99b285acd82fe38c5f72acdc6687322.nq.gz
    ├── 4602312a668eeda7cfe7fc5616e1f47cb02f551d.nq.gz
    ├── 464bd3aff57a4e37915248142eb4175858faed96.nq.gz
    ├── 473f74c3a1ceac64e2d45c62c54425f1f5b59922.nq.gz
    ├── 4940d8346c0a98e9c1392f4ce696e9af1bc04d61.nq.gz
    ├── 49640f74fb5e352c76482e69b5a64084c3bb528b.nq.gz
    ├── 4a95eaa1e2854e0e73029e216e867a563e6a4e80.nq.gz
    ├── 4b887defb2f8905a2461ba5d25094ae8c2433df8.nq.gz
    ├── 4bb730da7d0afb2c8a014b8803229faecb5b9034.nq.gz
    ├── 4bc6fa482943203470c1420c70a249c7f0f4df8f.nq.gz
    ├── 4bd7d6f1bceaaaada9cf096d8bf254d78c44be31.nq.gz
    ├── 4c32be6fcb413baa07857a7aff504bd7afcceddb.nq.gz
    ├── 4cc33a6e95dfbf5fd37d8d92921558cf152d193b.nq.gz
    ├── 4d7c6e738af1d40e88d3fc0a1f98783125cc835c.nq.gz
    ├── 4dacd5c36d2c43e03ccac1c95723ac98a78a5c03.nq.gz
    ├── 4e1c569954a7ea9998c6fb547d6e4e8b6fd4d30c.nq.gz
    ├── 4e2c59dae43151a37d10eeaf7ca2f9acf1b871e4.nq.gz
    ├── 4e8c99eb2274d67d6f437d13786e7fb192eb7cd3.nq.gz
    ├── 4eb227c45f40972dce755c6de2d49463accc71d5.nq.gz
    ├── 4f3cee06f77cec6c947d2359a4428b67c412ce40.nq.gz
    ├── 4f71c17201bc7234129d10ede647e7823864eea7.nq.gz
    ├── 514def1d1aa7727f2c17b8f2d4a98316cec05c54.nq.gz
    ├── 51604c69b85334725c719cc02bcdfc7a6b8ca038.nq.gz
    ├── 51deaeeb3eeb4a13da499c60a5f7d593af50b6e5.nq.gz
    ├── 52457e0c7700b74691ba43bc5bbe8e70b6d8a0e8.nq.gz
    ├── 5248fea635bff70ac2f7efe69cb86fc650efebb2.nq.gz
    ├── 52d429cfd75b5b1beb3fccd442262b3071c680d2.nq.gz
    ├── 52f3ff3f893ddfc476a45880ade54e0d81a82fc3.nq.gz
    ├── 55c405ba1495cbf277be3ffce423163c44d94455.nq.gz
    ├── 55ef0a75412001fd46962acbc1f70c050c19eeba.nq.gz
    ├── 56744e130246c202f49b9a9a8762f8f4d56089f5.nq.gz
    ├── 57b94d3dfa2e6d66a6a9e14e502cf7068488f614.nq.gz
    ├── 57bad2836676ff22ab98b54ffb3afa5a3b0ba5b4.nq.gz
    ├── 5811938566f78f6ef6a7b42e231d3828baeb5f4e.nq.gz
    ├── 58f23ece2f434072851a8245b597f83089123b19.nq.gz
    ├── 58f8692297aee85c6a68858b73a976c058b38362.nq.gz
    ├── 594ca9ba02a45589eea28588c13c2cb28ce77074.nq.gz
    ├── 5a125ae1886f98ad93132625a19edcd943defb27.nq.gz
    ├── 5a8f556d5d440a1b7157aaf3f319787cebc696bd.nq.gz
    ├── 5b68f5076fbad304dc547c5ed99d70e918589ee8.nq.gz
    ├── 5bb4103f1f08de5fb07b323fc159c2e9f8c6c963.nq.gz
    ├── 5bb535e398a655b0904ea980af6c38093328c355.nq.gz
    ├── 5d4372148fb9b24a1489e27d1833063bc7fa717b.nq.gz
    ├── 5d6f02af18732ad84999e7da2e64ae48afd13873.nq.gz
    ├── 5e405a5ce5eb63def48bfa6e4735352f661c9065.nq.gz
    ├── 5ef1b0508648cab0539c2e2fa54c88a6852f8955.nq.gz
    ├── 6025697bfa085e7c4fb0022c65fc972a1163fe0d.nq.gz
    ├── 60f825c1f7ee80a3a1329b5d3cf7e0624f5a9cb1.nq.gz
    ├── 6152bc6e2a5481265d109d8be24b8883bb96071b.nq.gz
    ├── 61562e8586db780193571943bac2fa83107e6af1.nq.gz
    ├── 616673d4f6672b146623b86cd238cd0051b35708.nq.gz
    ├── 620c664461a41043d24c2f5daff4a2d310978b4e.nq.gz
    ├── 63bcf22f364e560041eeed63ea593e6528123bf1.nq.gz
    ├── 63d8232959e6a60f3554d71877f472393344d49e.nq.gz
    ├── 6465abce7e495c6c90aa4c3f1df46545c3a03e92.nq.gz
    ├── 64d7ac2795a27d55a4e1da3afef4fdb42fbe05f7.nq.gz
    ├── 64dffb8e9d951efc82ee188a6317d0533d61f1a6.nq.gz
    ├── 651af0f176a5985530108c8f330264e153472837.nq.gz
    ├── 65b12b44f67fc028f86c9386f90bbbb882961a74.nq.gz
    ├── 65d3a8067182f1d2e8479fda0ed4d49085d24c30.nq.gz
    ├── 667b85f89392ea4a2b2309df61441f7d6d86021c.nq.gz
    ├── 671ce7de5635b55fde077cd71d10465b9497ce31.nq.gz
    ├── 6742ae6265de282134aee9c0c1c57a369a621c9c.nq.gz
    ├── 699e09d3186c536c1bf3400c9a049c1524431612.nq.gz
    ├── 69ca2446d28c4a2966f1a5ab5c476a75742edd9f.nq.gz
    ├── 6a61f4729e8a872953dd73fcf16fb718dad61f81.nq.gz
    ├── 6a6338ba314ffbfbf4aa0c09678a618a3fc0465a.nq.gz
    ├── 6a6d4c706f8d0aba38e332112df737d273503a56.nq.gz
    ├── 6a6eca7a66f5bae2c740643b7b8dae44188190d9.nq.gz
    ├── 6a8486099377a8b991b63cab0364273752d871dc.nq.gz
    ├── 6adbd5e3fda191edd85b510a0ad7f969edb3444c.nq.gz
    ├── 6b23d10b87299366009d00e546fb4429fee9330c.nq.gz
    ├── 6b774344e5b7f57e7919e3898b7c7fafc65a669a.nq.gz
    ├── 6bfef498a5680dfbb178b32f4fb8699ce07c35c5.nq.gz
    ├── 6cf6671d944f49356fe08c856eb2f0e6f2c07338.nq.gz
    ├── 6d53533dfba78c1e7f8528ea0e6c5d9313a1d5cf.nq.gz
    ├── 6e0dc73b28a1325c11c99816ada984f52bced733.nq.gz
    ├── 6fa7a3369d8432144727c5ba36907fd2cbed394e.nq.gz
    ├── 6fdda549b15713a0b86f2ca1b1b502be58502d4c.nq.gz
    ├── 700dd0e750dafbf2dae4f9ded541f7c55d5f5f4c.nq.gz
    └── 71654238d4b8d79663f262545905cf56ee6026c5.nq.gz

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

[litestar-org/litestar-fullstack](https://github.com/litestar-org/litestar-fullstack)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
