# Repolex Knowledge Graph of rthalley/dnspython

RDF knowledge graph data for [rthalley/dnspython](https://github.com/rthalley/dnspython), parsed by [repolex](https://repolex.ai).

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
rlex download rthalley/dnspython
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 68f8eb23106026eee0532a494bde74dd8cad6c3f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 68f8eb23106026eee0532a494bde74dd8cad6c3f
│           └── chunk-001.nq.gz
└── blob
    ├── 00662bc5007dbbcbb7f615e6db62e7e315782bec.nq.gz
    ├── 01e4743c53f2c6f4f67ee2303b919a8d1c3b5fc6.nq.gz
    ├── 022fbecd7649a2bbe3ecdd7db073f35d391cdbb5.nq.gz
    ├── 0335f700f7aee095dd32c3a719adc9d2fcf0c0a8.nq.gz
    ├── 03a16bbf6fa1ff6f836b310181debaa89767bdf1.nq.gz
    ├── 0406264fa200dbfa8e88e1627f44cf6eeb626fd9.nq.gz
    ├── 065c0a66766a0f34918f5c44a6956da4cb3a7f62.nq.gz
    ├── 06edbb77894afa31c7f29887394cf05474281953.nq.gz
    ├── 0760c26c2c4c98be5615793d67e9480c982077bf.nq.gz
    ├── 076d7a09b7ad00a461eee77cd6126c388018ed33.nq.gz
    ├── 0886dde4fbd4329a0fdef6050f1dc59713ad3a82.nq.gz
    ├── 09406fb168b90068711c6bc3c497a7f739107965.nq.gz
    ├── 097169851d3db9184dd4098f5eeb47f181404519.nq.gz
    ├── 0a2f3e798716ca0703bb1952f458817f0e0b5c60.nq.gz
    ├── 0c300c5aad68b14b3b5fed53b0aa92c6ea96eec4.nq.gz
    ├── 0dfeafbf9472ca2e906a002ecc7ade394f02479b.nq.gz
    ├── 0fc7cd416a1be2502d2a060dc6515953331eab08.nq.gz
    ├── 0ff104c8423652582cfece775833d2d019840706.nq.gz
    ├── 1010b675881836726d092804d480afa92be1f5e8.nq.gz
    ├── 1019881d9fbabbbd897fc0225cbc608e12700182.nq.gz
    ├── 10f1a254b11dd7d142a9c27953003c7570078d89.nq.gz
    ├── 11207980f2d1cc4a4e638cb1c6994bb4770f51d3.nq.gz
    ├── 11aa19e473216accd392052467bd912c24aa5ae0.nq.gz
    ├── 13395472d4d764e349a32e4b23cc176004c5ab93.nq.gz
    ├── 137ef77dc479a99561a66718206fc5439b2552ec.nq.gz
    ├── 138ac3ef551f07e8d79797228d5ff7d3eef2d286.nq.gz
    ├── 14385d46265d7098b074bf7d8a49c0a3c77b481a.nq.gz
    ├── 149b37925439d71871f27e97c1e39c28116f86c3.nq.gz
    ├── 15464cbda7f387d8b73d15605bfebc49d1402c27.nq.gz
    ├── 15b4117f38c1ecbb4258ded8412d3793547403a2.nq.gz
    ├── 165c137ddf7fb026a7595d0ad6c09ec8e28e670f.nq.gz
    ├── 17d9e9dff87fffd1e1d85ccbbea7846a9953c8ed.nq.gz
    ├── 18013f0917df522d98f9046bddd5f633e9df070c.nq.gz
    ├── 195ee2ec9b5f62e15d27f196d5f4244f4290f0b4.nq.gz
    ├── 19fd7a5fea874fe86e4389ef16632f34e3d2540d.nq.gz
    ├── 1c66063bdef693c019cc0ebf73b12669bf1fcc01.nq.gz
    ├── 1c949e68df67e29e5c329de4d28662c0ffb15b39.nq.gz
    ├── 1df3b7055799edf4e15b2c90c735a3b69a5c8de5.nq.gz
    ├── 1e24717a51fb718d84bb442b60f1feaecd018f0f.nq.gz
    ├── 1e3ea59fef6b81d1133ad5827490f4e8513570cb.nq.gz
    ├── 1e7cdb63979ba391299180356da85ac227d573fc.nq.gz
    ├── 1f4142f217c29439a4c3e196382a22762613be32.nq.gz
    ├── 20852f7839da07efcf148399a4aa6763e0624bc4.nq.gz
    ├── 2342e7009d243fd726a6726c120d6a157a13cd42.nq.gz
    ├── 23455db37403f201c22bea60e59afb0438d59fdb.nq.gz
    ├── 23909092cc8db17342e99f3cca4ccd47d0945e4c.nq.gz
    ├── 24a29bd88ba2eecc947ebfd8d6166a00d3a23920.nq.gz
    ├── 24c5a2d3ff63ba676a9fa3c061dda6c02bd5039a.nq.gz
    ├── 24d61001fbf4ce4c00687aa3de368044f53f4bc7.nq.gz
    ├── 263d7da05b105b47b83edaba36b59e03bcf6185d.nq.gz
    ├── 264cad61fe5b94563c7dc61b47924eb5f02039c5.nq.gz
    ├── 281b96dd709a23f3dc419f3dbfdc8142f18959c6.nq.gz
    ├── 29816569e824f036f70256f927096b398394c49c.nq.gz
    ├── 2a02cbedfdab73100f0e4bccb03843463f7380b5.nq.gz
    ├── 2a6fb21afffe59fec10a2a5262f91db6a32d351b.nq.gz
    ├── 2af65ea0cf20557e7091063485249444e5edd6ed.nq.gz
    ├── 2b3cf4d6bc63854ee8a93c4dcd6d1eb4b3029b70.nq.gz
    ├── 2b640a3520a883a720ed91f7e5d30b5a80c4b802.nq.gz
    ├── 2c472184790bf4cdfebdfb998df87b4fba31fce0.nq.gz
    ├── 2c9fc23e4411a64115b11f6ebb5b299e18e54016.nq.gz
    ├── 2e2e1427cbe51c4eb0ae5ae6d5168fab6f68b9ad.nq.gz
    ├── 2f79343db4c2623be869c6fb8e9c10a7a8486335.nq.gz
    ├── 2fed8ac75efa8560e6de7d9a94f3028910108f2d.nq.gz
    ├── 3090882380fd78bb9d98735c3cf4f4db291870d8.nq.gz
    ├── 30f2fed5c04dd321ef0405b277fe93bc94daeb56.nq.gz
    ├── 31a13d168e33c4b8c22fdac2274912d3029a5bc8.nq.gz
    ├── 31a7b2c819af8a59112ef1010f9fdd51204ff250.nq.gz
    ├── 32537dee52f5d259c5f89f45f4c09fa522433ad9.nq.gz
    ├── 334ad3dabcab04d0a81e5770b803b17bd13b53de.nq.gz
    ├── 344bef88c72186ed9fadc64c0fb3e11844858c3a.nq.gz
    ├── 348deefb903faca8bdc23e86010f2cffc59acaa8.nq.gz
    ├── 35f54c5ed7d777e0b798f49fcfa5e6f9c372373f.nq.gz
    ├── 363a34aa2fbe53143faf3e86842f95c69942de4a.nq.gz
    ├── 365b9936c66b31643a247aaad7c902af599eca8c.nq.gz
    ├── 384bfa89b1bd9c4367b0e985bf6cd9a7288237c7.nq.gz
    ├── 390a726dceb02e67bae01849000eb44632f01703.nq.gz
    ├── 3941b2ecedb14f303e79959ae1a1bee91f03995f.nq.gz
    ├── 399ded66466b015b83ac7fb12f07db4fe0551084.nq.gz
    ├── 3a29728229916df416932f33f0f9e382af0d4a7a.nq.gz
    ├── 3a33e1b1e0c3304e26ded046d7562419526b288e.nq.gz
    ├── 3b4d0bdef3730e4e218dc74b3be3743bf7b28237.nq.gz
    ├── 3be5877b221c60b9a292fda1079015351e3eeac0.nq.gz
    ├── 3c57ee1a8149511d73d370d6af7a1487d4ea3bff.nq.gz
    ├── 3c91a73cb22071cc01d65b4eb7c419689f237bd8.nq.gz
    ├── 3ede7595f3fc753dfcfaed12034a7e9e53f2384c.nq.gz
    ├── 3f3b9f1d2b871f866bfa9fbc17c0df3d6e0ff4dc.nq.gz
    ├── 3f7733b85274a2fc67f91dacabf6479069276e5f.nq.gz
    ├── 42531ca37a2b23c7b928762f56138c3f72a3ba7f.nq.gz
    ├── 43566714be80d4786e92e0ec33259a7c727c412d.nq.gz
    ├── 43e9863b80c06489d56858eb782245d29d06b2e7.nq.gz
    ├── 4439ff61643762fe45f8d70fa19bfedb7030e7b8.nq.gz
    ├── 4730666a2560a5446815d980d90a742ca620d1b1.nq.gz
    ├── 485bb4c30451b1fe93969b6409b29b2172fc295d.nq.gz
    ├── 49c97fef05a93561ca7935cf3e52725c2fcc66fa.nq.gz
    ├── 49cfee9c96df5083ff82214b79bec4160dcb4b53.nq.gz
    ├── 4ab71c9dc411ab8af0e1b06a5450ef8602b599a9.nq.gz
    ├── 4b8aaca9c8e4d4caea8aed5406f1a7c7d34f8494.nq.gz
    ├── 4c30eed129311e89585381e657e4c14778b65e59.nq.gz
    ├── 4cabea8e97d6d39ec66fcb62b830da7710f3951f.nq.gz
    ├── 4cc2536b9405f1bd6101730c797321878c32ad61.nq.gz
    ├── 4dffc5534c9a218f82552acc572d06d346a6b07e.nq.gz
    ├── 4ecea243b349370b908ecd75607df6afe2458320.nq.gz
    ├── 4f6fecb93ac7694f17536196b05f7af4ac16f7c7.nq.gz
    ├── 529cd26868b80e78e0558034a3539ba37f4a1c77.nq.gz
    ├── 531ca78a3a4f6e033a8a117bce62b49a8a143846.nq.gz
    ├── 536192a59f19eb066a16e4274bb7ece0cf5a7dfa.nq.gz
    ├── 53d094c7ba9f5ece5aca039526b54153647b615c.nq.gz
    ├── 540e27c006578e6ea3a35299baae0dddba26b384.nq.gz
    ├── 54826c3eddc87bd06ccd4a6c48d79dceaf6de488.nq.gz
    ├── 5526322ce07d30af2d9654b3dfd105954d817325.nq.gz
    ├── 55c10be5c4fc186937527547a561840cd3541a17.nq.gz
    ├── 55d87bf85cbe9d9f98bfddf53e2646db789742ca.nq.gz
    ├── 55d9326e48823e8749f1dd4a427a0e40fe243f4b.nq.gz
    ├── 572c063a989092513a2b2c2400318e457282b3dd.nq.gz
    ├── 573469ae953d5daa60ab64532b87ecab292b1140.nq.gz
    ├── 5757d209e265e11011ebb89f474dafb20385d693.nq.gz
    ├── 57925a91a8e865f7a7dc91c29aebfb1418c3b4e7.nq.gz
    ├── 57e342b619b831fc36aa4b2116d8e7fa998c940a.nq.gz
    ├── 580dac7ae857cc5d294311ada47105ebd1a819b1.nq.gz
    ├── 58b3108dafb6fbe457021a4341e74924f1ef87a5.nq.gz
    ├── 59dd01c40f02fadd93cc46d36656a2789b7efb74.nq.gz
    ├── 5a4d45cf1229d89dec78fcf979e0bdde8b5132f5.nq.gz
    ├── 5bd0933b576d25291d58b5d5bf7e1c046e695bff.nq.gz
    ├── 5d4739876da72d3cba156e7f8d537a98d0e1a4c6.nq.gz
    ├── 5d58760b1eedd5386917e0be234ed1d55f8ff179.nq.gz
    ├── 5e9075b46add6587993993eb139f40dd2afe1751.nq.gz
    ├── 5f6003c7abb6c4efe476a8b8cb99bb85336f0ab9.nq.gz
    ├── 5fb60daa9c1e1feb72f5019a2de369abdca1925b.nq.gz
    ├── 6004b699e982ca223c949b165648b659ceb0905a.nq.gz
    ├── 6073df47b3c1c7921431da0af514b511713b89ad.nq.gz
    ├── 624e2e936ae54b1d7aeb1ed3cc04529ea0a62e48.nq.gz
    ├── 627122bc6e4b55f5ff2a5b4cd3681e25ca242b37.nq.gz
    ├── 6299693cd43dc84d7cb75bdd8cc477e2a855c69f.nq.gz
    ├── 6357321631979bde6444f1fed266a1f1a8a81276.nq.gz
    ├── 6359fb3d8d6128995c9f5c27fb5795f92dced786.nq.gz
    ├── 64c113a09eb96ff59ff7a47213adaac42bf442a2.nq.gz
    ├── 64d1f0d24948862c6d737537ed669cf637b842dc.nq.gz
    ├── 657d1b765d978928255f546ad4ba93ecebc9a6d7.nq.gz
    ├── 65a9079cb9d5e58284210b6d4b0538d34a1365a0.nq.gz
    ├── 65d7ee28173b2f69391a62b0ceba6676320dc144.nq.gz
    ├── 665e407c9b3a5dee85b44a72bfce2b4992536e1a.nq.gz
    ├── 67b038896334f864ff707f4815f2b5d58715fd41.nq.gz
    ├── 68cb0920727ea174f34e1044b7c86cf95bcf3cac.nq.gz
    ├── 6ad05a8399f3b7dac4b500f2f74262a98a3360a0.nq.gz
    ├── 6b19acfaf129fb932ae56ea3a16bfe5f85a4dc46.nq.gz
    ├── 6b2073b7e9762a85ccc53b14f4795cb53e1a85c2.nq.gz
    ├── 6c134f182b84d9229dc4189e8802e7bd220b7f97.nq.gz
    ├── 6c73df7a8fa4b8a350be03a91e2409d1c37f644b.nq.gz
    ├── 6cabb4d22de5d2b33519573507d6ca072aa1b476.nq.gz
    ├── 6d4dae27add2bc505e4e89578b8963438a6d1e74.nq.gz
    ├── 6d556c7e99dc833e943a5945f269e89ffbf2ea1e.nq.gz
    ├── 6d5fcf24aaea7bab8920d5e234efe5ea70f092a7.nq.gz
    ├── 6d961a9f53f6eb622726e55d7225551288b6f077.nq.gz
    ├── 6ded05ce25890664c2b506ae368db4fc5929bc0e.nq.gz
    ├── 6e15ce9ce7877e29b021d0b32fdd7c6a61ec32c5.nq.gz
    ├── 6e549e6634a40b79a84a65f2663d29782de83c9d.nq.gz
    ├── 7104ecadd6054440e270c1d2363c7fcb906edc00.nq.gz
    ├── 719e0c0b50b62ce49a1c60dbfddea50a2a5d6a78.nq.gz
    ├── 71e275c576270dc16714d3a4e365302f2ee81c23.nq.gz
    ├── 72be01819b0bd3eaca69f89da3a35697190fc036.nq.gz
    ├── 72f04136b3bb3105a6ba2a885f89f1016758e7ba.nq.gz
    ├── 7396021a14363c5c31542949916af5f23cde73aa.nq.gz
    ├── 766f65f76a0728ea7c885afaee20ad0da3d686d2.nq.gz
    ├── 76c8ea2ac47e8af24e927ec6ce05b113e33404c3.nq.gz
    ├── 778df986f3755da2a9008c04c0919cb262992418.nq.gz
    ├── 78c1c9c3d24b28ac0804600d2bf9753130ad7c35.nq.gz
    ├── 794b7753926f6e90db33b4dd5894ca2124711367.nq.gz
    ├── 79f763100b3e0fde2646233a4670e082299755d0.nq.gz
    ├── 7ccf402f3b2a7592f57597f38d31ae1e92a516e0.nq.gz
    ├── 7cd26daff99615ca060bb13881af15a181db0b85.nq.gz
    ├── 7d2e94b25151a474766a8d2c4a90fd3ea8880942.nq.gz
    ├── 7e218d390503a9ba5ac6a8eef63b630178d2c728.nq.gz
    ├── 7e792c07188c7b3101117dc4b4f0bcc39118be84.nq.gz
    ├── 7e8722c1f3e8060bd92a0dfbf8504b2dcf8b7fa4.nq.gz
    ├── 7eb8fcfccc3cc5d05de9b8ed8d0649c3f5fa49c6.nq.gz
    ├── 7fe63d94a8c8a0813a19b5a577dc8575e7c55365.nq.gz
    ├── 7fe755f4f6b00f2990b3da04e265cfc91c041a0a.nq.gz
    ├── 7ffdb1cf9eb982781ca90ec705b5aa739840023c.nq.gz
    ├── 806af099eef577a22e352d12c81623375a1aa9a9.nq.gz
    ├── 80c46abf2eba31f3f476fb09c922de042368f31d.nq.gz
    ├── 81390a71173d8987b4054cca76cc814e5524d336.nq.gz
    ├── 82d364b22460f5e53f75ad206f63890aa11a1964.nq.gz
    ├── 8312b972a5b785c321493c875d65a7ef7b75a1b2.nq.gz
    ├── 8415d9483bde9f4666c262996b0888811ad81e2a.nq.gz
    ├── 84987ed0945e23dd679db6ac3890dd8402255aa0.nq.gz
    ├── 8574572c812ad47ef066d660197f0923f0e171a7.nq.gz
    ├── 85de5071df0c2413ba8558ed3978b570b932fd79.nq.gz
    ├── 866b194e060b54ec0369c5402b7b21f43e2a9009.nq.gz
    ├── 88ac1e6ed14c2a298dcc7354dd046c6f9352c105.nq.gz
    ├── 8a41ba90a3af62f4acb5abd903d244a066950c90.nq.gz
    ├── 8adf9a03842952d6f70150dbc6f65a9b4e143fc8.nq.gz
    ├── 8b677bf14e3a3846695864460ab65e3ca5556ec6.nq.gz
    ├── 8c218f5e96979b7870fc6d00eba728539598ac28.nq.gz
    ├── 8c3d7902b1593f95ccd8ada4c5cf043be0de2b88.nq.gz
    ├── 8d1eb6faccb795835c3173e6afc1f1c57333eda0.nq.gz
    ├── 8e81dea29f41ebcf636b9df1a6527e8dd8c2af28.nq.gz
    ├── 8f21e9094be4b458d5b561e445ac5e5618378d23.nq.gz
    └── 8f56d156ccffba857ba1551b48c18416d9b57986.nq.gz

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

[rthalley/dnspython](https://github.com/rthalley/dnspython)

---
*Parsed on 2026-10-18 by [repolex](https://repolex.ai)*
