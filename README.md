# Repolex Knowledge Graph of pydantic/datafusion-table-providers

RDF knowledge graph data for [pydantic/datafusion-table-providers](https://github.com/pydantic/datafusion-table-providers), parsed by [repolex](https://repolex.ai).

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
rlex download pydantic/datafusion-table-providers
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 2064c60b06831835e4ed9ee7eebfc6e595c6b468
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 2064c60b06831835e4ed9ee7eebfc6e595c6b468
│           └── chunk-001.nq.gz
├── blob
│   ├── 018b9f9eaf8792b512100ff4b713fdf2013fd2d9.nq.gz
│   ├── 02cc74add0d90a1d9b65fd39e31f30cc9d569f0e.nq.gz
│   ├── 04a7e546b85f4f764f667e47bc651e83a1d588e9.nq.gz
│   ├── 07daa1267843f8af3b5cee4a7eb5fd82b4fe32b9.nq.gz
│   ├── 086e648a0d4f21320910326c6f2ad4312748fbe6.nq.gz
│   ├── 0971661c1b833d2de196efd7dee1bada666ff986.nq.gz
│   ├── 0ce7badc388baed6bba02b0d2166bf872a34058c.nq.gz
│   ├── 107735a1d1d5511324b160fca842d2dde8974d94.nq.gz
│   ├── 118f4e3a4f0a0c2a9c3ff09e01686952d2c0618d.nq.gz
│   ├── 11b43d91fc343cdcdb46120a19282ef4aed179ec.nq.gz
│   ├── 14c06f8407b18b3de0ba959360779b075c56d339.nq.gz
│   ├── 2182c3b301e6b8c4c5810ddf52fbb8e33e72eff3.nq.gz
│   ├── 21aba7baf93f011d1915c46706f43d740da4ada8.nq.gz
│   ├── 22933b489d4526fdc5f4a99d6180742589416d82.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 268daab8f05404752498d5f606bb9171a7b42000.nq.gz
│   ├── 2d33035e5250a624b5beae71f8d255e40563209b.nq.gz
│   ├── 2d9cd5fa8c1bc1ea7470d5a7d3e1c7a1b762892c.nq.gz
│   ├── 2dc546cebd6fdf3af320a3cc6987e78b2e51e86d.nq.gz
│   ├── 33c12a88615185f815341569618419c800d154c7.nq.gz
│   ├── 33d14bd18079f24bf3b79d26a0f88807c0e19c20.nq.gz
│   ├── 386157e1bfb48a1b5143a1d243012e8660034718.nq.gz
│   ├── 3d933dc341dc292351b7acae3fe11f8af2895fc9.nq.gz
│   ├── 3e785fe67d8d08bf5481869913eff96307c90cd1.nq.gz
│   ├── 3f81ab22f2a5ef4f424665eb8d260e4b387a4970.nq.gz
│   ├── 41efbaf344b26cd6f10d07e67d23f41ecccf0984.nq.gz
│   ├── 46b0eaaf1581bf8bd36326e3cb353256dd57845c.nq.gz
│   ├── 477e8c992a0fd5d8b346e31953ab8091a4ee7cac.nq.gz
│   ├── 489db21184fececa5074b1795e2a33ce5372a4ec.nq.gz
│   ├── 495464277f1779e1d148aeb35ec12ae8e883efaa.nq.gz
│   ├── 4d313255d348937d8f41767e1858489bf997a551.nq.gz
│   ├── 4f28d3eb32a76b518e976f1619d70da3149a1a75.nq.gz
│   ├── 4f41f04259336ee8860b0b3a1c5b38957b7a3fb1.nq.gz
│   ├── 4f562481025047cdc5d902f9dd537d9f43df36fc.nq.gz
│   ├── 4ff572f9e90d384e598ae893cc7991839a663091.nq.gz
│   ├── 502322c3a38d1041415a6f91c5c7f1cacda2b8ac.nq.gz
│   ├── 51df13d8edfcacb8525dac4f6e1e4df43359a767.nq.gz
│   ├── 5251d0f38aa4263fe2dd72c5947d5a9a19bb7464.nq.gz
│   ├── 5472089c4aff599bf3b0161b9280bbca4b5a315b.nq.gz
│   ├── 54f1d778401fab566ff125ff5061ceecaf0daf06.nq.gz
│   ├── 5560bd99b38913e5bb5c4ddcf5f17f7d7a157ad4.nq.gz
│   ├── 57567552e782ac8acb819a74850a47a24d6ed754.nq.gz
│   ├── 593ffc9bc08ffa6d3550d9a4c8a0ec04e246c8a4.nq.gz
│   ├── 5e6d88fba2cef8e2a587cb03b398045a3ff4fcb1.nq.gz
│   ├── 602a7f9b41370e26b4fd1ba62484d7f59734ad48.nq.gz
│   ├── 606b831a7b04d07c96d9a5ca8621c965f60b488c.nq.gz
│   ├── 61fe092253477b02afc71b5442b352a58b0f69f8.nq.gz
│   ├── 6487da412f42d6a05bc47e25c57f2be00e47c6e9.nq.gz
│   ├── 65c42662605dc95b54f73881ccbbc08e1f0d231f.nq.gz
│   ├── 66d7f14a7888e745490f12ef5fb9e84bb0ca1ea0.nq.gz
│   ├── 675c86b7212047c61ce3011e67c61ca058b5fe9a.nq.gz
│   ├── 676dcdef1dbcfb3637a5ea6ef1b941f7077506f1.nq.gz
│   ├── 688db25a6957660899ceeec86d90b24f78833267.nq.gz
│   ├── 6900eee64db2872f69987006fec1545dbf62d242.nq.gz
│   ├── 69d599ac61fd73f6e790f8f8be0fcc3bd0e79db5.nq.gz
│   ├── 6b9e6e8490d9215fbf1d2cbefb9f96bd62f83ad6.nq.gz
│   ├── 6bfdb0815974c39691d182b2e6a0b7eb96fb7cff.nq.gz
│   ├── 6cc9912e729565be973d2a86e7a1521100a50ba1.nq.gz
│   ├── 6d8884f80d5d7064f4db1b1316e65820f3e89f88.nq.gz
│   ├── 6e8682dc2158e121ff9167e80ce1644e85ef99f3.nq.gz
│   ├── 7254746a74e98828b097860c61698e8df991e0bc.nq.gz
│   ├── 725b00aab2a45bc7811a589e0078af2c3cc1ce35.nq.gz
│   ├── 73c6b4490ee77c4e00868e270ae0f814afc2a08e.nq.gz
│   ├── 73e097851587abec4a8a62acb14c058b59ed147f.nq.gz
│   ├── 769039d7e0d394aa031b69d4fc20ea610b4fc435.nq.gz
│   ├── 780227960ffef07f1385073fe50c86b6d89560c2.nq.gz
│   ├── 78c1ae6f462ea546fc091455f5059a004f4a72be.nq.gz
│   ├── 7aa0afe2fd003729f5965e759259ff43dea587c0.nq.gz
│   ├── 7d5c698e4daf96d85e56e0c29fcf6a776ea7b3ab.nq.gz
│   ├── 7e532a8d94566e3ffa5a05418e1e63a19944b5dd.nq.gz
│   ├── 7ecb9c241107576c017c8a2f123c3bd5ffd8cb14.nq.gz
│   ├── 80347cb6c4ddc711bd7ee917cb972a0d6f8f37bb.nq.gz
│   ├── 806c98286f142a28e02065ddfbc0d618de54bfe9.nq.gz
│   ├── 8384078639ce4782c448647f65a921fb3a81653b.nq.gz
│   ├── 844ffac008806e8d10e95a02571fd264f27d6c3a.nq.gz
│   ├── 845ec823748001c0f7d939331f0f20979a4d0aad.nq.gz
│   ├── 8509d7882ec73b856c79cc91948541dfac61172a.nq.gz
│   ├── 86907d617bb508484a917a90a833735f32addf17.nq.gz
│   ├── 898c9efb5e753496c373b5c1aa32b56355b2a319.nq.gz
│   ├── 8e31298a52f3ee11c9aab784852c239ea8cd8fa9.nq.gz
│   ├── 8e569a29cdfcf48c8e81e18ca041922240a80bf7.nq.gz
│   ├── 907cb8c9708000c97ffc812f26bae575942c0d36.nq.gz
│   ├── 91a099a611cee3a16c4509bc47f5dc53f4e1da43.nq.gz
│   ├── 91c237f4c642396846128e6c92f57005e1b9ab86.nq.gz
│   ├── 9241ee970dd6c4609c36c3c06e79dc31a7f9b813.nq.gz
│   ├── 924bbd47e9c2be3e3ff2404b04176aa18c07a16f.nq.gz
│   ├── 92ab867f8358c801fbdf78129b655800a48fdfe6.nq.gz
│   ├── 92af15631434c86510c2d615f6388451825f8163.nq.gz
│   ├── 93180b00e372b8159d535d659a5f9cbc3539c837.nq.gz
│   ├── 94aca061c758764e827d419c2c4117599eef407a.nq.gz
│   ├── 96f11d55b0e400fac8179a5fd37cabfd8b098971.nq.gz
│   ├── 970d5363d2120c81c156b26f1fdf164634f992ca.nq.gz
│   ├── 97f1ec319bc6e7f586aa7d2a55bf6f7db14e16bc.nq.gz
│   ├── 97f9cf724fd20ceec6ff5491058246a2a31aeb42.nq.gz
│   ├── 981792ee011454b04de1b8b7cb7f66eae9c2b87f.nq.gz
│   ├── 98dddcf9aeaae5f6c46dba8c7637294565bd3ee3.nq.gz
│   ├── 9d4a5cec789e1a966b5e425bfedc5571cb791b0c.nq.gz
│   ├── 9ea5de3ead78e1426d78ebfe71e325d6584332b2.nq.gz
│   ├── 9fa98bfca75a53d913ca069eef8028b838dce3b9.nq.gz
│   ├── a1f8f57dc540e1cef673fb2328115512ed85681b.nq.gz
│   ├── a249e4bfadf41ecfe5603c6cc8993e7a8c1d3484.nq.gz
│   ├── a673d49d940ca9f4c465732eb34a22ea365bb482.nq.gz
│   ├── a946b01509c4db63253941c5666a8e63c68ce994.nq.gz
│   ├── aeb71e65cef4d692acdbde61ab9c6d66222e2c08.nq.gz
│   ├── af5eca0547bb3a6cbf1733de875ca3d496636bed.nq.gz
│   ├── b0b021471a3d7efe6e9b37403547db889a60b398.nq.gz
│   ├── b45c65f25065d017c9d71563f792eeed3142c7cc.nq.gz
│   ├── b46ab4ac49282e1ce79b18ae3edd1f2b382505c8.nq.gz
│   ├── b623f89450a86858e0c9e9301d5e8a9de14d5e2c.nq.gz
│   ├── b846877f33a268985db4b161dd56b8da5d26b31b.nq.gz
│   ├── bb82e6fa762cd641d50547110738475a9a45aa82.nq.gz
│   ├── bc7a0a21ef24ca2f9e615e82991dd3ec88e6bdfc.nq.gz
│   ├── c1a9d56751820238a217f253b4b5d72ddc8be126.nq.gz
│   ├── c3c5516a2b8fdcd5d6dfc1d03828d603a6cb20e5.nq.gz
│   ├── c411c35222917ccb877737ee20e8496be7954b59.nq.gz
│   ├── c59f33afdec07e3531bc3cbb901200bd3873a648.nq.gz
│   ├── c91c6e3fe4c7211a4f839b1aa2a634a3008dab11.nq.gz
│   ├── cb11e8514d17e103b413fbf8fb5ccba6013aff15.nq.gz
│   ├── cbc1baacc13232da84df33b6e7f92903475bbeab.nq.gz
│   ├── cc20c1574a03756f263e6586bf0e6c9458a89f00.nq.gz
│   ├── cd14a8d123607ca888aa2bdfb1a31f9ce2575272.nq.gz
│   ├── d152bc46c088389c2144c30edb05b2767d185b48.nq.gz
│   ├── d3beca61a08abb2c91db2bba64459a70f81e92e4.nq.gz
│   ├── d633a50bac66c7a1be32355b37221ece6bf9d82c.nq.gz
│   ├── de867b33ab8a46aab9759e2a1403675ee0fb8e75.nq.gz
│   ├── e1a60d27e86871d4aaf4dc599837a5aff1f576ae.nq.gz
│   ├── e3349445cf8943f4db18d0b8caceaba5d1ad0570.nq.gz
│   ├── e62b96d4745dc086a600bc33e23e5e326c980c19.nq.gz
│   ├── e70ae1ad199c4ce8ebf17a632703ec77f4558840.nq.gz
│   ├── ec7a29566711872b295492863165574e1818b65b.nq.gz
│   ├── f6ea05dcad7e5717e1b50831d241b0c7c5f43203.nq.gz
│   ├── f708d78c359a03235401ac3f42753990f28bc1c9.nq.gz
│   ├── f8c2bff47059b521108258a287e1644d619d274b.nq.gz
│   ├── fbd6d2b51c51bce4db07b3a7dc9deb9bc37b90f9.nq.gz
│   ├── fc238bb94f332208f92ecdc0c002459a37704b35.nq.gz
│   └── fd1b376b54e0af759db0893a4a1b0581670f2110.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 2064c60b06831835e4ed9ee7eebfc6e595c6b468.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 142 files
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

[pydantic/datafusion-table-providers](https://github.com/pydantic/datafusion-table-providers)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
