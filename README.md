# Repolex Knowledge Graph of DLR-RM/stable-baselines3

RDF knowledge graph data for [DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3), parsed by [repolex](https://repolex.ai).

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
rlex download DLR-RM/stable-baselines3
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b2878f4b83e21f16a53c54a62def628e05fd2e96
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b2878f4b83e21f16a53c54a62def628e05fd2e96
│           └── chunk-001.nq.gz
├── blob
│   ├── 006b6dc0a5f3cc8335c12541a697167e58e03e39.nq.gz
│   ├── 021a8e8b704e3d4b73c7e3b333b2dff25d96f1ec.nq.gz
│   ├── 02522159ff95e5db0aa40e8caa67e50653ff67ac.nq.gz
│   ├── 0639c75d580573b16ba5c03f285bd2ddc1829a1b.nq.gz
│   ├── 068347b00f78e16c65ab38d4b8b0f569a9ff5964.nq.gz
│   ├── 06eb1902b6e9a79c758b99c1faf7095c20ffda6d.nq.gz
│   ├── 0775a8ec5d266f77c7e314486902726d754ab4ed.nq.gz
│   ├── 08458fb63aa86259b651cbf76c99aa6f06b8504e.nq.gz
│   ├── 087852157e801806fe584b8045c5299fc93d8802.nq.gz
│   ├── 0951e29b4f9a29265d8f805f8fbba6e948030b17.nq.gz
│   ├── 0a99fb635d597ed5c68216e7f64d3b8675bf27e0.nq.gz
│   ├── 0b60adbd4954f969bafa6794b603fa23b275ac7d.nq.gz
│   ├── 0b61fb688be0dbffcd365a66057814dca6b557d9.nq.gz
│   ├── 0ca0338157b5338bed0c4b719bae985b532b1515.nq.gz
│   ├── 0cb502e20c857e5fd6105d13b9f2c2e211d0d696.nq.gz
│   ├── 0d16d6b002e214cde0c911fa1445d80de275676b.nq.gz
│   ├── 0d5234d7ada7612cc910e33ec7461b4397afa896.nq.gz
│   ├── 0f8ae6253c983d159c312a2aeb9be0c292c84576.nq.gz
│   ├── 1094ad5cf8a47ff84c27aa318b6fe9cb89e1228e.nq.gz
│   ├── 1463a1c65aff322bbf6b094bf4c490f670a71f20.nq.gz
│   ├── 1763d5f09dce12617703fb9d59def7fe2034aca7.nq.gz
│   ├── 1a0e94d9094be30815f46f4350d591eb171522a7.nq.gz
│   ├── 1b8f498ce150395e1908fe202a8251fd9fb0c565.nq.gz
│   ├── 1c7d43c0d3882ad3dfc15e9ef3e121a97e30bef7.nq.gz
│   ├── 1d775aad5cab1a33de4e9419c63537595fd2e8f3.nq.gz
│   ├── 20143ac2d614fe8d0ba2e1c4be9c4cef460ccd46.nq.gz
│   ├── 23062c2fea025fa5680b79907d9d797c44804baf.nq.gz
│   ├── 3569eb8871694110a6c797b2c7a403b438892a89.nq.gz
│   ├── 37b9ee9e0e4179c1771f2c1e47d99d611bee4979.nq.gz
│   ├── 3865d6da77b2b69791a627d3de2553328fd63eaf.nq.gz
│   ├── 3924db15d7fab324711b0e9ab3bea5494dd3a605.nq.gz
│   ├── 3adf0a243b3ab2d65bce4d791cca46d829c40ccb.nq.gz
│   ├── 3e4e48b0b5fe6b468434d6767749b399319f2da2.nq.gz
│   ├── 43edc2f28e272e496b5828b6b67c79f5c0c4915d.nq.gz
│   ├── 44d4e70f36ed768da4e34b60e398856051502ecc.nq.gz
│   ├── 44eb3914c7cd1dedfd8b84147d10705dfd5e299c.nq.gz
│   ├── 450864efed60b0fe8a099fad996c55d5b9f62559.nq.gz
│   ├── 4517f5283ed3cf115ca3bbcb2d66b85e718f30d3.nq.gz
│   ├── 490b9d8f24419bfaf4410206dc717e5fb065ba08.nq.gz
│   ├── 4c6fbdb8b7c43ca231341f16fe507e5b5abb159d.nq.gz
│   ├── 4de05265a6b1192ab35ef6728634009664b966c1.nq.gz
│   ├── 4f866ab215f54ca2c1c4ce1d5d047e62ae7249e1.nq.gz
│   ├── 51863ffc1ee4c0d5d300a408f15f81158e347dfa.nq.gz
│   ├── 52d8ffbaea4ecfb0c8db299dd110b849a7e07263.nq.gz
│   ├── 5319a1589aa8c59ed14366e4b3d448e9f978eb90.nq.gz
│   ├── 538983b9818d4ca7441ddc284282b5841e1ec217.nq.gz
│   ├── 563f46c50db193a6f5d13667feeabc866b4c11ef.nq.gz
│   ├── 56fcc1d320da29ad4938ee11542eec5d48278e75.nq.gz
│   ├── 58b18f4d7ce09117fdd360edb2f6342e52a86e60.nq.gz
│   ├── 58de7747ccc0aeea2b0e9eccc3d24753a0d7aaa3.nq.gz
│   ├── 5934345cbdfd190212633c07561e9f5265e98203.nq.gz
│   ├── 593a3e285836dd981af2d3f6f22c8966c05f5e43.nq.gz
│   ├── 59eb4e56c1c35a25b9701519ea1e5350c0188f23.nq.gz
│   ├── 59f895fdbcba3c3467c529c75a550b199618cad8.nq.gz
│   ├── 5a4c19e5184f039ab4e9a07629b88e887f707b14.nq.gz
│   ├── 5b480ad342f9d505cecdf4d4041a6b1ef81bd6c9.nq.gz
│   ├── 5e6520bc4ce2ce1abe6f714cd4421425a593c9bb.nq.gz
│   ├── 5eba694a4d24b4834a7a0dde0d618d937dfadb34.nq.gz
│   ├── 5fa967d1777ab41df981c7591e941a61736855c4.nq.gz
│   ├── 6071aaad4700a74377a49f62f565c34a1d6d9603.nq.gz
│   ├── 60a3dc4bee9067c72bf00b58dcc293273881c1e0.nq.gz
│   ├── 6227aac23bf1363ef2b9917eff5bda9602cf44b0.nq.gz
│   ├── 66d20f64a092c5af9a5e24b8430d7e2025c42a44.nq.gz
│   ├── 67430428a4af761b8382341bd4d97ee9bd536175.nq.gz
│   ├── 67f58df350f7c2e2e398cf36c89b0919df6a096c.nq.gz
│   ├── 67ffe7f5d4553e58e86025a373b6f0f75a7c965e.nq.gz
│   ├── 6859744609a12ed02c8b7c447cfd03dd3094350d.nq.gz
│   ├── 6a7660a4fc9c4e796db42a5ae11c990dd71f378c.nq.gz
│   ├── 6c72a8d5e5d5593c8f631ff899b60cf4302f2ad8.nq.gz
│   ├── 6fa50e342e5170be34e23a90686f3b9b1851749a.nq.gz
│   ├── 719881e373d64e02e95395ee1c6ca66d09346553.nq.gz
│   ├── 72679b121c86c9f6837c5b3859e957583f7ec1dd.nq.gz
│   ├── 7299b34df478f6392cf5182842dacd83373aed0f.nq.gz
│   ├── 73d4b4260c89e38b022bf0d460a54026f907a2c0.nq.gz
│   ├── 764709066b76874b00998577df626dec5d61a9a2.nq.gz
│   ├── 784022afb01be8c8c02d92de45ed4ebc6fecd495.nq.gz
│   ├── 7a65dcbc50520571bdb4c06f9f5ba232acae6e75.nq.gz
│   ├── 7b26b3257a66b37d0efe633be65ced52b5d5bb71.nq.gz
│   ├── 7d808a91c53af579ea9689d42749320980d2b1ff.nq.gz
│   ├── 7dbb9817a61ff84690ba502c4f83f7c04de76c3c.nq.gz
│   ├── 7efd94caa22d6d3538eb906ea02c41bbe773d053.nq.gz
│   ├── 7ffbec208a9b14ecad3eb50da090c11307f28ff2.nq.gz
│   ├── 810ff45ab2036b19ddee2b56526d24d67496444a.nq.gz
│   ├── 82781133c5246eab3aad271dd6b578434d0f7a1a.nq.gz
│   ├── 82c4616cceb6d3ee36d33a8a6fa301963563684f.nq.gz
│   ├── 846a954359585163d44e7677d5e3083efc08400e.nq.gz
│   ├── 8605c715c31ab8ca94e5513c31fa280e633f205f.nq.gz
│   ├── 874809a03b95aec54263ff9a0babe3838060c0ce.nq.gz
│   ├── 87903932ea5e415d45ac51cc102f56c923633a58.nq.gz
│   ├── 88fcf561451346a6d835c3e7b29786938f1621ce.nq.gz
│   ├── 8aabfc09432a03b332b6c7492f13f5a6403f5b2e.nq.gz
│   ├── 8bc63a9255f3bf12bca03ce1331d0720bd5fe2ce.nq.gz
│   ├── 8edf67dd0904e2a591d5ed60fa83bb0fdf26e1cb.nq.gz
│   ├── 8fae18b5994425c7f87e432ee2821e9235088af6.nq.gz
│   ├── 92f221eb3026972b8ede9aef829c8f08b3714633.nq.gz
│   ├── 93f0a254fe3e4d2beefa7938e0aa2e29c874ae28.nq.gz
│   ├── 945b7e775bd04dd1110c9f90b1182bb018c6a5f6.nq.gz
│   ├── 961ca222e2e25d4edd00450d061c77f147f73d33.nq.gz
│   ├── 962bef27a4d5bd6a0aedbeb85565b4a2e25f1ac4.nq.gz
│   ├── 98bb8a37862427834e6f8e8d064da213aeebc1e8.nq.gz
│   ├── 9a2ebd911cb771dc09bfa64236bb172109196c3f.nq.gz
│   ├── 9b203784d14855d33e0a3abb6dff82f8042840cb.nq.gz
│   ├── 9e78040f8cd20e226002dd07b47e16121a889c9a.nq.gz
│   ├── 9fa58c50880580cd2f479ff181948609d7419b4b.nq.gz
│   ├── a0bdb3e6f78100234874f11d056e7c5c50aabe5f.nq.gz
│   ├── a2b4437ed4f166331d7d074e8d91e129e06ebdde.nq.gz
│   ├── a3000af25d06c650a5f218dca987ddedace69f0c.nq.gz
│   ├── a3650627947e076a6c3da547716c5e91352f7668.nq.gz
│   ├── a3ad98a10383f6d8f1906bd96162fc529dbbd789.nq.gz
│   ├── a437b5e91a970b53e62de675c6b2da2ad23d52ee.nq.gz
│   ├── a52520c7d5f0fe4048075cecb641a5d20fdfd269.nq.gz
│   ├── acceb3b1baf5f562ba81b5240ce369999a55547f.nq.gz
│   ├── ad509538311b3df337bd1257165bc32a7462f26a.nq.gz
│   ├── af050a6816d823395b943970d1ab0a3c9e30f3d0.nq.gz
│   ├── af0ef0930f21e18d5760ea2bb87cda68e9570890.nq.gz
│   ├── af1e39e1302cb309153ee49869bfb2b028697142.nq.gz
│   ├── af5493faf076e972611ed5bbcc2f414d79c853ba.nq.gz
│   ├── af7f48a4de4bb1a7aabd2d44154f10e2332effce.nq.gz
│   ├── b1e2046805b0e2868dc9c0213e56e45abac9606d.nq.gz
│   ├── b428a61fd97082734aa26e7dd9923ed2b485bf75.nq.gz
│   ├── b4fd59ebee0f8a8fc64cd25f9f646b9bb33079cd.nq.gz
│   ├── b8a5891c7f6114ceca56dcf43fe63ed3c38028ff.nq.gz
│   ├── b9df9719850af0e1faf0841e933a09d1ca17f40d.nq.gz
│   ├── bade373f96100982be5ade405da3597ec034aba9.nq.gz
│   ├── baf121cdc516374cdbdf64aa14acd80629ec109b.nq.gz
│   ├── bb79c4b360ad829f7382d46914765508c87728d4.nq.gz
│   ├── bc407ce95190c621e547d6adebd54b9c4d94c569.nq.gz
│   ├── bda4e0d0d1e54ee5aeb68fd2c7a646a7404d6897.nq.gz
│   ├── bffe2ed774a718efbb0178e34115df52f7af535a.nq.gz
│   ├── c165e485d78c5d14b5b0cb7a9e39b929243f37f4.nq.gz
│   ├── c18c9c56aab94bd5a5229bdb7c7c57f47a1491f3.nq.gz
│   ├── c1babd87bfb5d3b418c77effbbcf45dcad212563.nq.gz
│   ├── c28144a110a8347230076904fc16a3abf448ac1f.nq.gz
│   ├── c3628a144514028dd12a3ddede2b5ca7b8d1636c.nq.gz
│   ├── c3f62e1de12b764b47ce41cb1a577e41ca7bed45.nq.gz
│   ├── c5aa72827dc42cb599c22011843e44961788fc81.nq.gz
│   ├── c8f03b212525b558e299a1a05d5f7a3bd48e7b58.nq.gz
│   ├── c966c5565ac2c8fe2427952aeb0bb970520448af.nq.gz
│   ├── cd1f413e852f314741498b97f0d277c28a774929.nq.gz
│   ├── ce487f4407346de538d67b8c461e610b0a321e1a.nq.gz
│   ├── ce6f53ab1371d229f5f63b2494d275b16ead9b4f.nq.gz
│   ├── cf46748f3b3d1fa50ae4b2861a4447dc87d11bee.nq.gz
│   ├── d08e190616135baf19a65904c81b08dc40e24a51.nq.gz
│   ├── d126396faa3bef71c2fbe753687ec760b8beb00a.nq.gz
│   ├── d24444e8ffebe8247ba275885970c14245057388.nq.gz
│   ├── d3e72eba7283df36848c53a01fdc1ad547fe41db.nq.gz
│   ├── d40d0ab98e466b2295c548d52b84fef4ae971f2d.nq.gz
│   ├── d40dc20578b39f3d67643a1db9af3580007d7b50.nq.gz
│   ├── d4c6a93e4f00d4c9ae13544582f2eaf73c07b51a.nq.gz
│   ├── d79389d40dfdc62ebcad18a03490891cccb1d5c9.nq.gz
│   ├── d9b922515a7d0ee21c449da14756a604002beb36.nq.gz
│   ├── d9fefca2cbfc3ef4d68eca2ef5b99ccf763e8bf3.nq.gz
│   ├── da5beb4f66b60d16d4652f3b541c8bf74aa6adca.nq.gz
│   ├── db6c6493b62577134a2d50655b70c088989ed2fa.nq.gz
│   ├── dc4c8c2841b400a2984e40afbef8501e16ff628c.nq.gz
│   ├── de1a1be1f23d8b13aebec0f7825d1f83f064085a.nq.gz
│   ├── dea4f4c0baccc416199f10d5eb024640cbdd6f59.nq.gz
│   ├── ded03f8109775d80716f20f15d715ac48b7c0ba9.nq.gz
│   ├── e10e4093a69e2120f557b4691831a544e9339f1f.nq.gz
│   ├── e11eb15796ca239ca06e4bc9a6319c32f5bc82d4.nq.gz
│   ├── e1216ab6b33c7fa6e7253b59e6a9215e51fe4eef.nq.gz
│   ├── e3c4b6d8cad1683a3c056020411cfb264ad4da00.nq.gz
│   ├── e3e32e85c7ae56c82380bb5bea51709b0ce25c8c.nq.gz
│   ├── e44d8d2d3b519d3cf0b3d1c1680216d2979300a6.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e7be7e4e36910ffce02043060c0aaaf5008f163f.nq.gz
│   ├── ea234cb5ae3dbcc14ab79d87827f496a713257ab.nq.gz
│   ├── eb83da9aa97ff9f3021565fc7df730a047965be0.nq.gz
│   ├── ec4b65248a65c44f3cb653f862a7305537103d38.nq.gz
│   ├── ef2a5a020599886c000f544f22962c64a9c6a91b.nq.gz
│   ├── efdfc9fa8da685de121ef127f6d1ae238813ad8e.nq.gz
│   ├── efee84afb241702857a9e021f67da80e17052a81.nq.gz
│   ├── f6752c5dbf49346ca85cde858662db2aa39aca9c.nq.gz
│   ├── f6870639605da99b11c1a5652d551d043b76022b.nq.gz
│   ├── f8fa40a3cb9ce605e80b182ffb3b3fd6415011c1.nq.gz
│   ├── fa0e374b4ce28b2570a90d6398c3b948c885a2fe.nq.gz
│   ├── fb0225da4a137643913773c42c51c454a607602a.nq.gz
│   ├── fb7afaef13be27ca853b7ef4087864f469a1e3dc.nq.gz
│   ├── fbb1a8eeb24bd50dfb9e00ba80f137b649d8987b.nq.gz
│   └── fd4488f65597795786b83918c2c3537342ac2e90.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b2878f4b83e21f16a53c54a62def628e05fd2e96.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 188 files
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

[DLR-RM/stable-baselines3](https://github.com/DLR-RM/stable-baselines3)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
