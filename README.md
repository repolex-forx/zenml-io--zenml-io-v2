# Repolex Knowledge Graph of zenml-io/zenml-io-v2

RDF knowledge graph data for [zenml-io/zenml-io-v2](https://github.com/zenml-io/zenml-io-v2), parsed by [repolex](https://repolex.ai).

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
rlex download zenml-io/zenml-io-v2
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── c8371c37e9184407db937734533d075f729e4581
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── c8371c37e9184407db937734533d075f729e4581
│           └── chunk-001.nq.gz
└── blob
    ├── 00ca2b1436a0afd0fa7ed298b5130c84f35e633f.nq.gz
    ├── 00e2d979f679b45026ed22290e57b7488c2b1e04.nq.gz
    ├── 014f0275fa3d2bae5914df4cfbe1a74e7b66dd67.nq.gz
    ├── 024b89dd92f20ffc6bc5ff9bf7e43f1d27c3c75e.nq.gz
    ├── 0293e3d50abfba9d0f0dc2276d92b24d37e2905f.nq.gz
    ├── 038291bfa2a6a30fbc63ccb596184af755ae4cb2.nq.gz
    ├── 0382e44dc4f2990dece0c32dd34f82979faada4d.nq.gz
    ├── 03bdcd83e6342222cec5c3083702ab0550f757af.nq.gz
    ├── 03c96022d097aa6a14ec49dcfa1c53273bb3a8b7.nq.gz
    ├── 0543651e5ec1bc70067c9147fe610bebd6f30f23.nq.gz
    ├── 05a1b88cd20511f413896dd3114c8dec0e3e3238.nq.gz
    ├── 05d131f8d295abf8ce6793a0dfbeb6bfa2ddd4cc.nq.gz
    ├── 06351483e01acb553cf8100362862637404284e3.nq.gz
    ├── 06f093ceaabd71a8efd66d3a47462baafb52c5af.nq.gz
    ├── 06f4a79736c4949d755282ef1628c24a52273d9a.nq.gz
    ├── 073ce20f8fe51b8bfab8dc99b02831d3bf9584f5.nq.gz
    ├── 07ca4dc11bde7e2ffd84f7189e0f561889851dea.nq.gz
    ├── 0837df48308cd038089eded41e1e32b2a02f162b.nq.gz
    ├── 08675b5f64d2f50b503c3750f34d2c954bd7755f.nq.gz
    ├── 0a587f5ad07638a22a971ae8652c55ee6b8c1b25.nq.gz
    ├── 0a95042f65bf32f0168f8db13026a8bd84dd38a6.nq.gz
    ├── 0b2401381dd064dd2573f5f3b266c3bb2ca70af1.nq.gz
    ├── 0b3d2801cf904270425f664e3880e5fd8ee3cf5f.nq.gz
    ├── 0b83c04d3a88c69eef043c61ce1008a72ed16c56.nq.gz
    ├── 0c688e418eed0e03abc47746629adf755d59ddd0.nq.gz
    ├── 0ca74aa50101807dd0dd373adfe6a9efcdd4183a.nq.gz
    ├── 0ce8c9012c73134a07a12f9a1eabf8e0cb2ed498.nq.gz
    ├── 0d3af1bf6780f9df4a0350fd6fd405cdcf50a35b.nq.gz
    ├── 0d740f91ec9e8147f7fcc70e3133512a1c77a886.nq.gz
    ├── 0e164b2685bb93630be3f92fd5a143bb990a7bff.nq.gz
    ├── 0e7058c3c89c0a671fc7de338adce14d5b14d88f.nq.gz
    ├── 0ee69dda17461fd92dbfa78e09be263ffafa008d.nq.gz
    ├── 1046c3c86403f17c48095d3ac97d1e646aec0064.nq.gz
    ├── 10b1ec38cbd5831a35ea00c5afb41a15fa2a7dfe.nq.gz
    ├── 10c3c6c159f2e36cd9a8feccdf70e3de9e0e6f4f.nq.gz
    ├── 10e435be78c565fadf6a2493ae6640133f2700f8.nq.gz
    ├── 11316b413cae0288d18f33fc8fcfd9b6f228cfc8.nq.gz
    ├── 125f0d3a68fe3bc3552dbedf98d37e3404c1fb77.nq.gz
    ├── 129c794212d20ccf2716e6feff3f848df7048d17.nq.gz
    ├── 1349b80cc5ebc472d6a183658c2a02487bba4c9d.nq.gz
    ├── 13a71906e64350b8835e2d61cf4ea5de949a0f5f.nq.gz
    ├── 13e38b93f7e6c66f55cb52bdbb0c4e205f563345.nq.gz
    ├── 1411621b059f77338596aa4f8ced76ddb2e22d66.nq.gz
    ├── 1444edd8a874e80a933c9e6ff136f7c96925efe0.nq.gz
    ├── 14e06eb4c4e47886cb308e8a791580e8d35017e3.nq.gz
    ├── 1694f9653486ed8f1c359bf3857eb38d9815780c.nq.gz
    ├── 176286c827403bc8ebdc2a41c64c9f445bce803d.nq.gz
    ├── 18020732f882efd435878631011a231c693e8201.nq.gz
    ├── 181fc5d7a2bda846d158c6beb5e04bf5be5725e2.nq.gz
    ├── 1878663ffaa5c2c990cfa9fa5c708f9475dbbea1.nq.gz
    ├── 18d0053436946d62a41afa7fc89c8090b30589da.nq.gz
    ├── 19a630b348ce2699a6715c8320dcb8e0b5f89306.nq.gz
    ├── 19c0a814b2f178d2891a91bf16e384ac084a336c.nq.gz
    ├── 19d4edda33790b9949e1d7c52b2f6b29fa6c342a.nq.gz
    ├── 1a9f6628288139e92447a29f8533a01a9bc73078.nq.gz
    ├── 1aae6f47073020da851a27137f90525012abe5ee.nq.gz
    ├── 1b0462755ee2c006435de04ba1817604f9138cf9.nq.gz
    ├── 1b43f1dcccdbd16674b5633e5421b1c928bf9deb.nq.gz
    ├── 1bb7c78bc04dd20db68e3ec3eed11f0787d659e0.nq.gz
    ├── 1dce0d4e034678b16d8376e7d33ef7bc704b431a.nq.gz
    ├── 1e8c2665967ce4f11e2220abfa0b13af065a4940.nq.gz
    ├── 1eab1847c8089de683879a0169663590f264e603.nq.gz
    ├── 200af7c367def6d8d58c0134f6af0cd5a6b56900.nq.gz
    ├── 201d8f208aa108dcc937db0134677250e6091004.nq.gz
    ├── 205c50fef53f9e81857f2591e083748389870f95.nq.gz
    ├── 2085131378a988cb9a1e7e7e592c1a0ceb46d1f8.nq.gz
    ├── 21ac5be5b535a14836bcbfc2ec518a25ec31e8ca.nq.gz
    ├── 21d6af6280b49f5f2229ece01d3f55b284e6a673.nq.gz
    ├── 223c6036cdc23d749e18e4bccf6154265d9d17a3.nq.gz
    ├── 225fa7f00e661a1388a0aaa1b81ce4f208b69c92.nq.gz
    ├── 228cda4c6acd4691d6e3780af32fc0fe9750d4e2.nq.gz
    ├── 22b91aca48bfd165a904e36394bc820bbfaacb9a.nq.gz
    ├── 22bf5bca6fc22969aedc082e1a8bdb9aa5157190.nq.gz
    ├── 22c914cf3018e92b20a65dc883da99f1d70a1445.nq.gz
    ├── 22d69b555f0ade30b005a69b96752e3e271333ca.nq.gz
    ├── 22eb123ffbfe8cf3eab816da7928f86af705ec07.nq.gz
    ├── 22ed3935f6373891e64db6c1df92ec9c60ed854f.nq.gz
    ├── 231c8b36f5b9501970d9c9a70ff92e4298b0f370.nq.gz
    ├── 2333b609e8ce804eca3de0a0ebcb7cc398804647.nq.gz
    ├── 23626008d07b3eb817a73d1772fdfc17c8721070.nq.gz
    ├── 23af42c4e38818b6e940c623d2b7ad0d3173001f.nq.gz
    ├── 252a78fe610d5773691714dde72ea2541c389d11.nq.gz
    ├── 2578b3575020fea42f556dd54117fecd93e6ae52.nq.gz
    ├── 2698a5b441baa7ba5c7697e81b36ac5df546e0df.nq.gz
    ├── 26ea615df7bfafb9935d82c28e6e4cef51e38242.nq.gz
    ├── 26fbddba6368b02c32a9b5ad442989bc05809bb0.nq.gz
    ├── 278743e7209fbac9e52c62de27b5025e88a21b14.nq.gz
    ├── 2841b43c52c7ded90595aa8a2806a2e12bf56d4f.nq.gz
    ├── 28c63b1320b3fc7b31bb885b2661d3056586e71b.nq.gz
    ├── 297c859524c20b48bfcade453f2dbe03830524e4.nq.gz
    ├── 298361969f82012adbf36318684b0c9910191254.nq.gz
    ├── 2b60b4b46e47bac51e33fce7471ad7afe65b914b.nq.gz
    ├── 2bb75af210162dd8d83e7c76f7028c4426f9ea56.nq.gz
    ├── 2bd4be64ea6f3f10569fa00998c1e910c24c6985.nq.gz
    ├── 2c3429ab706104010b3ea0596de1c16ff3abb8f0.nq.gz
    ├── 2d23f4fb27e6a9685f060c6c59e7a409026b114b.nq.gz
    ├── 2d374b459b3bfc7067cba195aaa4e4a1903ea8be.nq.gz
    ├── 2e0996ac2fcd7656e078286df391f9844feccc8c.nq.gz
    ├── 2e1bbd6bcdd9267dc008392e7cb551eb0bf56e7c.nq.gz
    ├── 2e1ee730cf74b7f38d2be8927c70c31b31359348.nq.gz
    ├── 2e3e0a6565cb2f45fd2b1b5241606e9bccbb3513.nq.gz
    ├── 2e4b61ad0a76cddce32dc2330328b45e2b3dfc61.nq.gz
    ├── 2fc553a58ed9c692ded359e08fcc472e2a565388.nq.gz
    ├── 2ff1e2703c1c1a4c0ae39b2abb5c774fd0bf9b55.nq.gz
    ├── 2ffff220d5b30dcdfd5a96f54e3263a25b025b8c.nq.gz
    ├── 30b903d06de699afcda853795554cfa2ad217f51.nq.gz
    ├── 313cb3869fbf90f6994fe655e358d9c56ab359f2.nq.gz
    ├── 314ee58679cc365fb8239d204cb43676fe1ddce5.nq.gz
    ├── 317617eb978f1967f4fb7dd52e6ab5eba74f7dc3.nq.gz
    ├── 3177be8363c518c99d2ad3a2a92650cad871d125.nq.gz
    ├── 3287cbeaef468b347c5c680de52020ac9c6ef153.nq.gz
    ├── 330158c747eae5d05e7a9cf76b9c827f9f1c5395.nq.gz
    ├── 33c76da1da2ea53d5ac2a95db742083bf2479f35.nq.gz
    ├── 344640d6c4346889308aac0dd7e7502821daecbd.nq.gz
    ├── 347ba67f8331786ad1a336db110f1111242bb5e3.nq.gz
    ├── 3520ae60abfe785b6cf1907d00e66bcb2fd5ae03.nq.gz
    ├── 35d1f78e1d359c3c2b48599289785e3b70206aa9.nq.gz
    ├── 35ee31c788137e4608d9a7b941b41f19613e4834.nq.gz
    ├── 35ffe6c1f1229e65aa55e313417fec7313922ea1.nq.gz
    ├── 363c0d2c1404f3025ac71881184946e763ef7a14.nq.gz
    ├── 36618436edd2ed52ac6a30e023421669a914755f.nq.gz
    ├── 374845842ad9d8629849836a27468cca8f6fe205.nq.gz
    ├── 37a8e202963330169b3f8d82df3212c9f74f27ed.nq.gz
    ├── 37e56acf1d5a1819b141baf616e7a2195b4284a1.nq.gz
    ├── 387399dc8ef493fb4bb58a9724d4d5c78b43b664.nq.gz
    ├── 389cbb27530ac88aa28e725214cb93fa163fe4be.nq.gz
    ├── 391f6238151a5bd7ada83b9069ac9c0193dac7a8.nq.gz
    ├── 3941940dd5943aa9ea94748726bf7af34963aade.nq.gz
    ├── 3954fa03da56633d5edc3fadcb5d47045b95dd29.nq.gz
    ├── 3ba40dee27ea4517218120a2287ff6316acfd939.nq.gz
    ├── 3ba74b5417e49404e24073371d08b78fc17255a9.nq.gz
    ├── 3cd6b1c146a81e295c1486c8aa88aec6dd334fb0.nq.gz
    ├── 3d0a56b0c481b658b9709546a275ca5f4c20936b.nq.gz
    ├── 3d43b61e5e7322ced78cf5740a3944753b564f81.nq.gz
    ├── 405db2e017cb53e7cc9a7d12467930d3123e2b75.nq.gz
    ├── 40862f539f50eeb63e4689c4dffc277c9cf57bcb.nq.gz
    ├── 412f7dea8fa4864e63c2f484aec91b9f1d6cefc6.nq.gz
    ├── 413220ba788ffbb0087dcbf0fb1f47a5162f1f77.nq.gz
    ├── 416ce60e3fb970d73e5fb613b59c5491d49e1cdd.nq.gz
    ├── 41c54cb70c7b558b150dde231f508e7a00f3a19b.nq.gz
    ├── 41c9f2dfcdb1f2d91ecff5551c27e5d5b8b7bf4e.nq.gz
    ├── 41d4f823ddba345d864d4c13b5561714afac125b.nq.gz
    ├── 4262c76a650c08a2c3601b668b0577adfef18c51.nq.gz
    ├── 426bbcb92e639745a4d3ce46b5d3f54e8f8b5a7b.nq.gz
    ├── 426c9435572a50a3bfeb54578565799f2b5efa95.nq.gz
    ├── 427a4d743690141854836daab62aaebaf35c33dd.nq.gz
    ├── 42d97c64845c052acb5174a5bfd2531bf5d3657e.nq.gz
    ├── 43674dc7e9d3f8314ad94b935680a38ec95040ad.nq.gz
    ├── 437d802b45b55c4331decf92364114f11ede3340.nq.gz
    ├── 45d1fc3d9297d2b0a1ec312533850e0acdd2d024.nq.gz
    ├── 45fb7544be9774955dad11752517f32acc355c8e.nq.gz
    ├── 46a2bbcc99fa1792af7afcfe4c47dfe7002a85f4.nq.gz
    ├── 473f69cdb9d8ebd0837cfb69799e169529ea1a54.nq.gz
    ├── 47f69cb8fc3251a9d6ae8bddde31a83c8a6d60b7.nq.gz
    ├── 480dbcafc415f608e42d369477a934fe879ac1f4.nq.gz
    ├── 486d37ad236e5d4fee6243c0a9ef680c6b8ff80d.nq.gz
    ├── 48ffde1db06de6ce00c09027685ae16f5fa72127.nq.gz
    ├── 49d2016e57fc8d94d2ac557f723cd04ffad70078.nq.gz
    ├── 4a03bc75851166ee5495822a8feb45593dff2162.nq.gz
    ├── 4a7ebac4cbe480823ddf8de77f6c3f669f4f3275.nq.gz
    ├── 4aa98fa1114e0b280a0d01a49ad0d2f53672ae91.nq.gz
    ├── 4ba9c6363ae8d1bf7355e184e300fc10ecbf1bed.nq.gz
    ├── 4bdc741efaac6d2ed5033fe8e935b2ff5a94de07.nq.gz
    ├── 4d286764c75b458c2d8070b90d5ab3fb3fc88d5b.nq.gz
    ├── 4d6c7500d65d69150a1e6d29de95fb6798feb46f.nq.gz
    ├── 4f0ea9bd5f809df68249d5be1e5f5dccf75ee75a.nq.gz
    ├── 50b82c4cfe590ea970481da76d45e8a008aae534.nq.gz
    ├── 510cfb681310637de9ab5c6a593befbc53426c4c.nq.gz
    ├── 515b9712b25a2b5d53bb083c15d25194511b0f2b.nq.gz
    ├── 516fc3eb9769713783a3dfc0f858d62c0641c7b3.nq.gz
    ├── 52bf8d393d07c4de80fc6c68e2609fe0e1579bdc.nq.gz
    ├── 5330031be1e89a596f0dd9e2f97316bdcb4ff416.nq.gz
    ├── 53403392e10785c36c40db44d711b8f87123cfcb.nq.gz
    ├── 53913bdabca68b8600ba8fb8bc1e0e7728932ffc.nq.gz
    ├── 5476bb6577a8b9c43ec16917a2962ce3315c8068.nq.gz
    ├── 54c8848c37868c06e520a8f99d38b425987390da.nq.gz
    ├── 54f4a7cc7ae425e005de7341612e83cac46c1875.nq.gz
    ├── 56afb471981fbf339cdc242455c973afc16cdf25.nq.gz
    ├── 573400e43cbec5142b2a39d64291d83428171e59.nq.gz
    ├── 57730c13cca00c7f437ca5b9a693bc2fa5af2cc4.nq.gz
    ├── 5879d7b43d561652ea164a2b818d8731fe5d5876.nq.gz
    ├── 5ab1cb2e536af0a3c3e4815bfe32d7a45479af5b.nq.gz
    ├── 5c3f305f3db17ee1705480f3cebecba124964df4.nq.gz
    ├── 5c5bb5e9aa7b0c9e9ac986843d041b215bccfd6a.nq.gz
    ├── 5cf1ca78bdcd5388e010f72e76585a46fbfd512e.nq.gz
    ├── 5d665058c3bab7c7b1a805952449faf7f2f5cdce.nq.gz
    ├── 5de407d00203979bf0cd1810cf9f6fa0436911f7.nq.gz
    ├── 5dfd8a3d5f70c92d907b3433ca8fe5b209052b5c.nq.gz
    ├── 5e26f6b7e83ea170ba3b2e7bb39267b1bfd03e1e.nq.gz
    ├── 5e4f923271d51475567808632a5506f26ad9d92d.nq.gz
    ├── 5f0254633a3426e628ea51a17747f18bd98e6c2c.nq.gz
    ├── 5f8e9f616f7ad81ad86e7b56b4d7a629109382c0.nq.gz
    ├── 5f979d3ad335aa2b43b82462beee9ce28375389b.nq.gz
    ├── 5fc5150320d829f40e3843a952428c28274f1ee1.nq.gz
    ├── 60ae683201b0e855d1d6a25d5d0684c0cc29c7b1.nq.gz
    ├── 60e83b3aa024494172ad84dc14f33292f0c5e080.nq.gz
    ├── 622fc94f636c6db5d93934246a364f8b1737e394.nq.gz
    └── 62d0dec6aa7e0f617a2ade4178107ccd9b75b545.nq.gz

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

[zenml-io/zenml-io-v2](https://github.com/zenml-io/zenml-io-v2)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
