# Repolex Knowledge Graph of fsspec/kerchunk

RDF knowledge graph data for [fsspec/kerchunk](https://github.com/fsspec/kerchunk), parsed by [repolex](https://repolex.ai).

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
rlex download fsspec/kerchunk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 37e8f9016509d0d2b93fb3fff5549312641311e5
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 37e8f9016509d0d2b93fb3fff5549312641311e5
│           └── chunk-001.nq.gz
└── blob
    ├── 002067ce80de3b81a896a86f93fcd6ad22f63311.nq.gz
    ├── 00b76c94e07d0186e2917ea0ba354a2b933151aa.nq.gz
    ├── 00d8b86221f7306bbc94b1533a92bc52eadc33a1.nq.gz
    ├── 02885b668769b4c49223a456522ebdca236ed261.nq.gz
    ├── 02cce5cb27b38903740ac582516110309368292c.nq.gz
    ├── 0612f0fce2b16ec011de9467969a27468e58aba1.nq.gz
    ├── 06582e2f07b528b8a7e9c57eb2ada2e6728b2f51.nq.gz
    ├── 069cea67279419468e1b76e20a8a54c56cd68f94.nq.gz
    ├── 099f66d71325ed304b6a7d86b4339d3bb6d1d100.nq.gz
    ├── 0a52383ba6e32a297bc455c4178d5cf809cd3f76.nq.gz
    ├── 0b7044e2d58777dacfb862e6cbd8b4a3081569e7.nq.gz
    ├── 0c117cc2d86a395b2a8a566be49f9f83ba1eb4a0.nq.gz
    ├── 117995018369a22e9e8283019a0f900938748b1e.nq.gz
    ├── 11a70b812aeda561de306f31f2cf5d487a532726.nq.gz
    ├── 12ff9a309b2cbaf5af2e33496e13a3ff736007bb.nq.gz
    ├── 1734224943e25ced5d5c14ef4338b4d667821e9e.nq.gz
    ├── 19fa6e947bb2111baed625f9a210d20ae6b8560e.nq.gz
    ├── 1a82dfec38865ed5d767785c4b7a642ce95805a3.nq.gz
    ├── 1dca6c57c87e69c89f7cf08bb1bc44bd29ff7d1f.nq.gz
    ├── 1e7950bf8bed74e7983eb4f042a986277f2c3f40.nq.gz
    ├── 1e98b7895bb6b37f8163fc19bd4033b129cd5eee.nq.gz
    ├── 20e3721cb0238a0d19eeb87cbfec0636fee8ceae.nq.gz
    ├── 210f0fb7bb9db1d90c2fc44ad3248b74269c8d5a.nq.gz
    ├── 2119f51099bf37e4fdb6071dce9f451ea44c62dd.nq.gz
    ├── 25828986108337b5cba0356d35969a689fa2ecb0.nq.gz
    ├── 25b24bfc5633964c7e5fab52134309a7923d80aa.nq.gz
    ├── 26bd8de7d8e309d128d085522d31d9f8e5885446.nq.gz
    ├── 28c93192ee820c291329e68f90f49282ede001bf.nq.gz
    ├── 2b8091b9fade43dbc4865f3bb0ca0dc7c43c66ee.nq.gz
    ├── 2b9c66285f5b8640641510dd6b1bb9dd1c3051bc.nq.gz
    ├── 2c3237cca89f205cd7f855c0afac77f38d8ecc71.nq.gz
    ├── 2c5387fded815e8a005b651f0eda6b9d525d1328.nq.gz
    ├── 30cfc834c85aa5c3e3ce11a65d1a900b4bed1896.nq.gz
    ├── 320a2c0e070f920c2c695b6dc06f018e43dbb78a.nq.gz
    ├── 337e9da353de02177b8ce87b7964b09daef7f6d1.nq.gz
    ├── 3411ee6e8481b492e63eaceff734239f8fd2f190.nq.gz
    ├── 37b6e2fe601a1b698a940fb7beb7828e38da48b7.nq.gz
    ├── 3812b91a5f71e932bf12ab70f3e853a6c7dfc42b.nq.gz
    ├── 3a7e725796bdd7cb5562a1bc826eae3572bab6e4.nq.gz
    ├── 3ab82af6efa87b9b32a5dd7ad2b866fc7285f698.nq.gz
    ├── 3d548119db7f820dd80e3f5259cde3b87d090abe.nq.gz
    ├── 3f4955e60e14225cde9a4683e16f6e20ca99b7c5.nq.gz
    ├── 3fd37f1b62d5bfc7faf24c57303561e2dc20ced0.nq.gz
    ├── 40eaa277fe120284ff1317695c7bf3979fddbdc2.nq.gz
    ├── 42330bae59070003acb6f851065d7c3b868faed6.nq.gz
    ├── 42a059d9371c3e4e8edf124f4a02c47730b3caf9.nq.gz
    ├── 43c976192428885ba020dc5746e11ebb02da8e8d.nq.gz
    ├── 44b45accc1a5a62f28e4f191f5252e965eb866ad.nq.gz
    ├── 45bcb9bc07f00b6a0199dedc872aa9a107595e04.nq.gz
    ├── 46f1b4a65f8444f39d9942347b616a003b7234a6.nq.gz
    ├── 4852ab28ffabb0fb0bda365836d4257670c92f70.nq.gz
    ├── 49736418c8f61c35cba327e6ae1246b5d6867a51.nq.gz
    ├── 4a9e3c4ac0ec769370ed3c52fd74b89d724a5de1.nq.gz
    ├── 4b115dfa3188475e49e21593cd4b6f97d301f9b9.nq.gz
    ├── 4cce102a70dd7a6fdcaa912cb38db91c3410095c.nq.gz
    ├── 4d3f26f64511aba16da4bd1bdec0625fe4f07bd1.nq.gz
    ├── 502c098b80656ab003ff1c0d0791fda5f8f8bad6.nq.gz
    ├── 5242cca9b60518673d8eb62b6bf9db15ec56584e.nq.gz
    ├── 5449a8d6d9c013251b13d06191e24f2c7d749cd1.nq.gz
    ├── 54ec6671e6270b5abedd0e003cb85022f0163943.nq.gz
    ├── 565502ba8665bec57b75a83a545838677cd49c34.nq.gz
    ├── 568a3b2049f4365337bf13705d63abfafe4cda0a.nq.gz
    ├── 58acbd54d094297e1a13438f4ca90c1a1e88a12c.nq.gz
    ├── 5995b4efd818e4bc5188c8164de8f996236a74c1.nq.gz
    ├── 59d16b1600a6dd41d289df78fb3fe08814b3d790.nq.gz
    ├── 5a7c957fc236e081221531d144c53023862cda51.nq.gz
    ├── 5b686a67aab6936dd59b2371a0dc54530829b6c5.nq.gz
    ├── 5c0146f2648843439159024a15c952222da57b70.nq.gz
    ├── 5cb785677e7164d17483fac201874831bfd22028.nq.gz
    ├── 5e88349923e5ed7e1ac520bf5333085e41bed1de.nq.gz
    ├── 60a7c24350a6de629685dccd0b347e967ed1e4ea.nq.gz
    ├── 61347ac232668bbc0d1bbf8b721235ea0bc08d41.nq.gz
    ├── 62d8bee6385b671af21b882558e862c6297d8db5.nq.gz
    ├── 64cd38aee531cf4057ae93b4c9aaae150c1d455e.nq.gz
    ├── 66ab7ce6f78a9102d87468bdda3958d96d06c785.nq.gz
    ├── 66e059915db85710ddcc085ffe14c22a81589b24.nq.gz
    ├── 66f0db4531178c5624d966132c20323fca5616d9.nq.gz
    ├── 6741c0b2b59062ac880d45b152603438df6dee6d.nq.gz
    ├── 67846e53bf5acee2fd6db719257b57fa7542bb76.nq.gz
    ├── 69a3cd769a88dcfc97ed8571555b6b41d205734b.nq.gz
    ├── 6b9767bd4fd5c23f51893d65ee4d7c1e0bc71550.nq.gz
    ├── 6bfd7ef20bdd93fd99a84369e40f06da0e100761.nq.gz
    ├── 725b1319d869de24b4d18754d6659c1587f2a964.nq.gz
    ├── 729b7e9ecaf108507eee81614f0d1162ca5601b9.nq.gz
    ├── 7582139550e406e61b0c290a11cebfd19632896c.nq.gz
    ├── 787c35224e2af4d5d1a3a8611df7ad396654609d.nq.gz
    ├── 78f924919a8e37ac7123d55ba5fcdd6cbb188c98.nq.gz
    ├── 7d8e6ab93bd41c3102455de8129bc2e3957b5bec.nq.gz
    ├── 7d9dae6a6428b9b208c8ca45eb555ba6ab84f9d7.nq.gz
    ├── 7e81ebbaa0c8c42adf2a4939ece68ae091d1bc0a.nq.gz
    ├── 82575b6ed68c483baa9c2c25246277e2ede73283.nq.gz
    ├── 8346809dc6a11a52b8eb96292f1baa65bdeffb78.nq.gz
    ├── 83cfcee09847a1df9942cf748b283aba0598f357.nq.gz
    ├── 84933f061d5323c1fb42722586813b46ff5ce8ee.nq.gz
    ├── 85863c321ff9e811066bed883c98c2b549cf3051.nq.gz
    ├── 8590c544666b7b3ce39d66dec44599fe24a0fe7f.nq.gz
    ├── 85ebecb56c71b783814663fb239bf3f6a3b4963f.nq.gz
    ├── 862532b72219fe3b68f6dedd544f3001454ea8a1.nq.gz
    ├── 8629573f8a43d4a5632ab0c616ad169791ee5584.nq.gz
    ├── 87e301a527ef5551fd083abc5ec466b7f3e43d26.nq.gz
    ├── 8ac4a89a6f94aaeeab00456beee71ffbdedb70c4.nq.gz
    ├── 8c68d173d69cfcc0be85dd85141408d565a915af.nq.gz
    ├── 8cee27d190f3c6309a84a30ba7b1e0cbcfc00f47.nq.gz
    ├── 8dc2809832e2e8b78fff9ae0fc4ae30dc020b324.nq.gz
    ├── 8e055873e3fd69e283a80c5501ebd9f5a2f507de.nq.gz
    ├── 906b5669fa29eae5dcc4758c5e395fa4ea83298c.nq.gz
    ├── 914920a86789e443deacf430372ae56dcb624c8c.nq.gz
    ├── 91559939f44bda698a0a95f17f466b744b49454d.nq.gz
    ├── 9180defa21fdab52e30c7f1cdc71c02faa99c60b.nq.gz
    ├── 94623f457b94372e6cbc48bdf22a46da81903edd.nq.gz
    ├── 9645052036da1c4a2b17a8c1489604fc1f65fcca.nq.gz
    ├── 96deaeb7eba0a01a8bfde63bcd47393d4889a543.nq.gz
    ├── 970831a08f13362167c017bf0120d8386daa4d47.nq.gz
    ├── 98e4cfb98f0e67c382a6629930e351f65a7b5e11.nq.gz
    ├── 99fffa3a88fda3c498117da22c2b2732d0940395.nq.gz
    ├── 9a1bc1c09d87c8ba01818f0c63b8450f71291f7f.nq.gz
    ├── 9eaf1e29148b6dd9eda45b58f1b2b96beb8de4ea.nq.gz
    ├── 9f5985b547bb7f54cb59092245b92f963c81c646.nq.gz
    ├── a1b4d6d08a5899a52ddb76af2a231fb619ac5da2.nq.gz
    ├── a2944a0247895c56c28a94f8d606ffacc564557f.nq.gz
    ├── a3d9cddd8a2a75e4dc7715ad295f835b26712b06.nq.gz
    ├── a43e187b69fb333cefe6da7e2305e3cb90471cd1.nq.gz
    ├── a560008e5de0a06b597969ae3114898dc4963ae1.nq.gz
    ├── a57579342302767256c6269861400f671d578b79.nq.gz
    ├── a5daf3f89b41869c638c92b04d19c382e60fba4f.nq.gz
    ├── a6ad28df8c41cd47596282f35be9e36fcbf684f9.nq.gz
    ├── a79403695faabb2dca2b447e1734dd390c264d67.nq.gz
    ├── a81aa640339c2ba14a1c419512cf1b1728fd04e5.nq.gz
    ├── aa6374bfbcf959b4e2426a3ed88eb002777a49a3.nq.gz
    ├── aae0047e38506072e2601ececf9372141a257f0f.nq.gz
    ├── abd3f06bdb38912d959358d1deeca66cb17ae538.nq.gz
    ├── ac4292d3c1a10477505ef0faa142e49a3affe294.nq.gz
    ├── acd0c97ff18219d9c8e34f6556211f9280ada877.nq.gz
    ├── ae78b21cb06a2b8b730d086191e8e24f5b0712f9.nq.gz
    ├── afaf6be113d169e642d5bf8b7d36c56e36bcfe35.nq.gz
    ├── afcc1dbdaa62ee5315e74ecea80f77cb58991a09.nq.gz
    ├── b09f101da1a1a789d43fbc183c7da106e132edb1.nq.gz
    ├── b22c633919ffa9f4bd8c804ca580c58cc4b17aa4.nq.gz
    ├── b383f04eae117b01d3bafe3f65a87301a3d2db60.nq.gz
    ├── b40611060fe0bcb4f06106eff45178d51f42abfe.nq.gz
    ├── b5d651a1b6b14bd73fea7940f0908f5409d5ca77.nq.gz
    ├── b7143398004883b6a8feb03fd02e60c053a2e29f.nq.gz
    ├── b8bd88874c4e0b376908594e72d08b3470f197b1.nq.gz
    ├── b97f912dac7a289dfa614e2e9c8e582aee106b2c.nq.gz
    ├── ba9c45e811a10d91af66558d8c8e3f2acade2ae6.nq.gz
    ├── bf222fe600746be535d977c87f9a908a12e38aba.nq.gz
    ├── bfd0d3384b84b1df380a3512ed49dd8f9e83bc88.nq.gz
    ├── c01d4c530ecb732f73d7acd344034af64f05488c.nq.gz
    ├── c053917b730d2a2b6278a5c0e6b988ec35984cbe.nq.gz
    ├── c1c6b8161978ed9e84c1153670c824c0c8316889.nq.gz
    ├── c212711ff1bc4a9a0d2a6120d33245e669382fde.nq.gz
    ├── c2d4dfeb4f2d264c6dc9ca5f817708203a0d4925.nq.gz
    ├── c38d7fa59af123fa7ec0332fbe279244ed10f620.nq.gz
    ├── c553a30850e0d19be0dfaaae8ae1258c2386c24b.nq.gz
    ├── c740f964a2641c70f1bf33c666e850e2440c1c9f.nq.gz
    ├── c77fe14b0f6b1c0001ad0317cec33877374f4418.nq.gz
    ├── c8d4136e1ecfe1a3265d9cff71c1c66b689adf03.nq.gz
    ├── c9c23dc3e7921d280c61125ae7e41cde6649a087.nq.gz
    ├── ca08559d55951a433e5768c2d677d27a799ba037.nq.gz
    ├── ca5d614061f3f81c7d924f262f198b55e242a3b9.nq.gz
    ├── ca97c84fad4a6020ae7b7655cfba0e032e5030c4.nq.gz
    ├── cbd29e96e897e519dd4df87418bdff3b8cdec825.nq.gz
    ├── cbf974c8a6c4c72791cbca7e7b3ebdd3fa2a18bc.nq.gz
    ├── cd35dd70af9b4179a27d3a752300f185a30f90d1.nq.gz
    ├── ce3fff44ba7b5b6650e275f7eacaa3c5d56e2ddb.nq.gz
    ├── ce5484d7d3e4be8d4bafe9bdb22913e4156026e0.nq.gz
    ├── cffbf69a2de60fbaeca046bafa48f9b0880a5103.nq.gz
    ├── d0457c865addc37afad3fd2087c94422e5420950.nq.gz
    ├── d17173ea9254fcf2cf64a1dc9465a4720e9c3aec.nq.gz
    ├── d3d87f6aad60ada64bae0c168849656b66f8098f.nq.gz
    ├── d42aed220d3e91c2663debfc10e222e036b803b6.nq.gz
    ├── d5e9965dab2366d3dd85072800157c2e5f09708b.nq.gz
    ├── d831200c89a95a0bc3e371d42363e142428fae78.nq.gz
    ├── d86c00dee0a7c0329311730eeec0a7fd5e9bc8a4.nq.gz
    ├── d892ae290e8f6413a3f4be081bc878a9d62457b4.nq.gz
    ├── d92df94bc515f159f1dae62a29ce3abd293a4993.nq.gz
    ├── d9664362dc1e5f0a938c44fb3a618ec9ad377e9c.nq.gz
    ├── dc4a45c915f1b11c5061775d9b2d314d6fba2732.nq.gz
    ├── dcf8230719390ce1e5bd8e91ab93d56c59991005.nq.gz
    ├── de6b34c2419e439a3ca86a9be2c588ca0cc7e281.nq.gz
    ├── df24762bedf286ce806c754ab1a02bb14a442b77.nq.gz
    ├── e32d0052b523da6642aa4b027c289f7e443583a6.nq.gz
    ├── e5a7aff3491944ba800a64a28bad7022d1298646.nq.gz
    ├── e6f2a4e59265b1bb44845b9b738f798fd50f8f79.nq.gz
    ├── e7d1532df3b74eb65811189079cc81843172f93d.nq.gz
    ├── e828a719e1e92533aa9cc1e9566b9f6c272e0e0b.nq.gz
    ├── e83bb1774ae9a3f6bc1184c012b09b0c71fa8a43.nq.gz
    ├── edf68eb2a04fd9d8ef65b08f82cc7dcfd027db71.nq.gz
    ├── ee8e28faf95bd0786115eb9a6a8ab35e86f73cde.nq.gz
    ├── efc7b8f59de649e1394d27648a4123dbd9b8d18c.nq.gz
    ├── f154ce3ce54087b866fde458c7f10d759d5505bf.nq.gz
    ├── f321b27b4a8487ab4699ef1718bbc5f20af7b02d.nq.gz
    ├── f3db3b5d686c389525cdb6c8b421312a88bc8e89.nq.gz
    ├── f73d07b19f8d20833fd7ea580c9f5ffdb99ca80f.nq.gz
    ├── f793abe8eabef5aeb3b5a1db98fb491eeb876f4c.nq.gz
    ├── f7ab499dd25323d1918c39955071a4aa604b0eab.nq.gz
    ├── f88d144c1e50d53087e4b8edf1eacecbff76e9dd.nq.gz
    └── f94ec7edab7b0eee9b91ab82d8bf8f554e9e155f.nq.gz

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

[fsspec/kerchunk](https://github.com/fsspec/kerchunk)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
