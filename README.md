# Repolex Knowledge Graph of toml-rs/toml

RDF knowledge graph data for [toml-rs/toml](https://github.com/toml-rs/toml), parsed by [repolex](https://repolex.ai).

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
lexq download toml-rs/toml
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 45456abc190bcf7b81dfc96914b726d7b3053e41
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 45456abc190bcf7b81dfc96914b726d7b3053e41.nq.gz
│   └── repolex
│       └── 45456abc190bcf7b81dfc96914b726d7b3053e41
│           └── chunk-001.nq.gz
└── blob
    ├── 00217d79faa1b74a3844f2a1c45abc1be25b931f.nq.gz
    ├── 00529eb3cad9dcf32a3594ca24b1af9f83ac144e.nq.gz
    ├── 0073c4ddab53c6311a616ec901f2d8f128be5da3.nq.gz
    ├── 00a8144c96f1e3dd031c12968f1f251759b8b329.nq.gz
    ├── 0135b9333b9b86e2c85443da45d6971878ae2465.nq.gz
    ├── 0160798f5e1438d1a38f1a8ef5bd8eaac6694525.nq.gz
    ├── 01727d192bec9f15051616a5636eafa189e22e7c.nq.gz
    ├── 01c4d4803cb2e801ec123a6040feca55f3f1902a.nq.gz
    ├── 01eb22007fbc234917236d0aa83102ef6f36002c.nq.gz
    ├── 024839beea010e8ba6e488363aa5a17e328e02c5.nq.gz
    ├── 0267e704256754b747acf73378683f77875116fd.nq.gz
    ├── 02a4319436304630f15c477df304f68246fb6903.nq.gz
    ├── 02d69c9b2512b2dde580694f37c4d1b167f232bf.nq.gz
    ├── 02e8869d80b3b42b0c6949b7868a828576ca86d8.nq.gz
    ├── 034457f08a17ce5ffb212ee4b88491d11ba3a498.nq.gz
    ├── 0416dd9f44b166a16ee9b1e2574c33be2014c409.nq.gz
    ├── 0419d1f4c6c025db8f253cac0eabd363663bbeb9.nq.gz
    ├── 04e8ec3c878d1b7e3e152017db6055e7cf97b7d4.nq.gz
    ├── 0577dcdaf51084d858d714b425a4444267d00fe1.nq.gz
    ├── 0588f38ade22b4e20c8a9bc3ddd322bcc47cf8fd.nq.gz
    ├── 06ccfebe42339db56da38eb9b786e69eede58c4d.nq.gz
    ├── 06d9d504ebf860461b690dfe49084d70771258c2.nq.gz
    ├── 07ae19534014c6f67cb864524eff70389686d7f1.nq.gz
    ├── 07e2fee4c2c972676329207a5967f64fedfc96e1.nq.gz
    ├── 08576a817fc6da0e6549263da4941166bafea9d5.nq.gz
    ├── 085c90b148a56ee159b65d2eb1a87bc3267fb0d1.nq.gz
    ├── 08b46d04a19e1fd94578d9f55d2845e0f8511d1f.nq.gz
    ├── 0904c4370ad802a3ec707b0514c7a71b83404d72.nq.gz
    ├── 092bac47a62ee66028ea53b70c56dd6ec09d6985.nq.gz
    ├── 093234c3db83bbf375c62d40c315c050bf46c5d8.nq.gz
    ├── 0940aa8d8ce5626c03fcf199e1d1fc3e7543ac53.nq.gz
    ├── 09c9feef98b19f1776ca0bad27cad7d2471aff52.nq.gz
    ├── 09cb187df9c8355d04d748b59cdc0bb0bfe6ef18.nq.gz
    ├── 09db5d65c4a7a418f919a422c4272179307c399a.nq.gz
    ├── 0aae2303d8217b3672286264fded735641413543.nq.gz
    ├── 0aea9f56de783bf75daee61c2fe558019691717a.nq.gz
    ├── 0b190583f0ef529536daa6415deea86a1c898c9f.nq.gz
    ├── 0b1f1994e66d8305df220dba8a44710a3f64086f.nq.gz
    ├── 0b53c17efe60100e9fe34b290d11aedc5fccadbf.nq.gz
    ├── 0c2add3d89d5e2d16365d211ee07d0589d84ac63.nq.gz
    ├── 0c4120b6470a310886dd3781621316266e2705c1.nq.gz
    ├── 0c70f28644c0726634592251225089318a97d130.nq.gz
    ├── 0c9d17f03717cec3412750dd20106b8c2ed9c917.nq.gz
    ├── 0cc6c776f3b25ebd5ae8d4c801e6f42cf57727df.nq.gz
    ├── 0ce791c0743c972f5523f46d8bb1ee2b80174369.nq.gz
    ├── 0ceef2135c0ecf6e9bc1274d1aa4607ebc03c348.nq.gz
    ├── 0cf265ee24f72bfdc31b0478fcf77bd61a832ae0.nq.gz
    ├── 0d33ebe342e00f8113a5ab53bd1fff76710fec34.nq.gz
    ├── 0d3a8e8efcf7fed718dd451a705a1cae673e65b6.nq.gz
    ├── 0d692b11a8217c01dbe76dabe48505c20f27aabb.nq.gz
    ├── 0da55ae13f5c503ef90a8c73daf018ac54a2cc3f.nq.gz
    ├── 0dc176d1e09c0767c3405a60d42ba4a980e8b004.nq.gz
    ├── 0dc359b93128299b0bcdb54a416a4087c091b84b.nq.gz
    ├── 0dd49c9988c4cbeca5d0409602a3677dfee7badf.nq.gz
    ├── 0e4eda6b80385154bd17a2d3fe7a5c02cb59b69f.nq.gz
    ├── 0e6c2adf810b3989cc0681e4bf3e11d6631678be.nq.gz
    ├── 0e815a5d84549925077ae85cdf3a5efb589084da.nq.gz
    ├── 0e96b1717b6619339ee7dd116440a80235f3ab68.nq.gz
    ├── 0e9927eab9a766000fb423449b088c9141b2b797.nq.gz
    ├── 0f478e4b5054a36263c05141f1d9b35c83c9541d.nq.gz
    ├── 0f53629de0bad163ffe775197510b5f910b5c599.nq.gz
    ├── 0f91632724d9c105a204289c3571729e5cfceb20.nq.gz
    ├── 0f9455c409f23a98ca6faa15608de36958e22bdd.nq.gz
    ├── 0f978753b519409af756eb63e0f1cfb7e473b5b1.nq.gz
    ├── 1006e2381e284fd055614cbc0bf1aaea495cc407.nq.gz
    ├── 100eacfb36ba21c3f3ec2936637b457d3d1bd351.nq.gz
    ├── 1042a38a26f3cefd03f732877615af496835dd46.nq.gz
    ├── 107e7dd2287ddeed280186cd12cb7b7add44282f.nq.gz
    ├── 10beb5dc830328eae4e82fddc1b7f117b98a668f.nq.gz
    ├── 10ce29ee3de1296494f03381add5bb98027b7bcc.nq.gz
    ├── 10e7ffefcd47ed2c4ebb1efbaa61116f857686aa.nq.gz
    ├── 10ee3e6322dd3f216e99b32586f635d7d65c871d.nq.gz
    ├── 1121258e594f07618ccb40cfe66d3564c7040c4e.nq.gz
    ├── 115ef219d5fd9f17a05a62b8ad7e57ca31ac712c.nq.gz
    ├── 11d8c80aaeb611596d3fc03232ba8743f5f68ad6.nq.gz
    ├── 12bb54dbf250dc9e432c0052ac11163d183a39cf.nq.gz
    ├── 13b0dfe797e30302357eddafafd842ee454d9769.nq.gz
    ├── 13d7a7bd485ae5064071e52ce032369c86f413d5.nq.gz
    ├── 13e1503121adb9d46c404c7bcb396389786ebead.nq.gz
    ├── 13fbb6b975f2c669af7d5e451bf185389faf3e8d.nq.gz
    ├── 14491430b943b75cc2f383c43b6aa597c92f77ee.nq.gz
    ├── 152c4832eb03fb8db1120231a4cfb1717f989653.nq.gz
    ├── 158d52cb4ddf47d84dde45cdefbc72ff01dab5db.nq.gz
    ├── 16761ca2003c03efd974b5e36f3176e934e17dbc.nq.gz
    ├── 16b9e049a01fe4702e8a260c9e00aecadd9cf459.nq.gz
    ├── 16d5f2e7c5654d97cb06860333fc3716477221bc.nq.gz
    ├── 16f871f3896bcb60959cb04abe5e250da2bd2b3f.nq.gz
    ├── 170de947761ae125d7d34f425249187b38ddde29.nq.gz
    ├── 173250d7a8084bcee0f321386e76ad007db31947.nq.gz
    ├── 176605309a294c9c19cb9d14a7e9a02b75feb86d.nq.gz
    ├── 1769bcf7c0c0531605b8b70396c64cc939afa1d3.nq.gz
    ├── 191e83f3dfe251dd114fb96eb505b53a82486c36.nq.gz
    ├── 1993c4be762f9370c0d7d525c312b3cd78f64033.nq.gz
    ├── 19b4a51f64526d51d48ca4a99c47a2b27d9fba5a.nq.gz
    ├── 1a423a116cbe881ff5c9dedaa791978381a80972.nq.gz
    ├── 1a49589df5b5cafcf8289a9f2bdb469c4c527f11.nq.gz
    ├── 1a7d0ae718a5400085326e0df8e51d30441a3a27.nq.gz
    ├── 1a96a38b3f5f652488952e93434b61ac073fb56f.nq.gz
    ├── 1aae9800b7698c1bdc634850a24f0d047bd290f2.nq.gz
    ├── 1ad2adfde3f434010f6b124e695e7a14d354560b.nq.gz
    ├── 1ad4fed630e729eca1391166e2c64881f05ba888.nq.gz
    ├── 1adf56737381a4ac535812676e9a0618e64f3cc1.nq.gz
    ├── 1afdacb30af025835674c25176751651b9765a6f.nq.gz
    ├── 1b34ccc5cba6566457a96a58c994573d932231d3.nq.gz
    ├── 1b499cbd83a06dfe9168363914cab703a9d1bf36.nq.gz
    ├── 1b4b83ec470a3973a3747ddf14e6e6e47a23f072.nq.gz
    ├── 1b8f1ec32246c8273ae12942382f0143ce318954.nq.gz
    ├── 1b9934cc52638e8159cc37718585587ed8392d8a.nq.gz
    ├── 1bd9e1aa20e39cfcebb0209a0fe3a699cb2e516a.nq.gz
    ├── 1c1370b6496a574649f5a4bc44d4cbea6e19c1c3.nq.gz
    ├── 1c4ff7af3074c3453c762d91b652e3a6ec139c6f.nq.gz
    ├── 1c57d9dfc2174774c49860408d37cd98d9557be1.nq.gz
    ├── 1c5eda606cc254f9b4d51a2a189ddfb8e6287ad3.nq.gz
    ├── 1c84e298eecfd19d8129ac125506ec905d36d0a3.nq.gz
    ├── 1cd601d0a3affae83854be02a0afdec3b7a9ec4d.nq.gz
    ├── 1cd99ff6880f78e0b36c3dac6896d73d01dcf3e9.nq.gz
    ├── 1d4c5dc66f4e229b407587965d09da9816e06eac.nq.gz
    ├── 1d4fd850696ddf8d3d0b9e3387d47cb7cf8c66e4.nq.gz
    ├── 1d667a40bf701dfc09600b93d94b9adf54b27e09.nq.gz
    ├── 1d9540bffa201eba89d5adc849d93319441e8cc7.nq.gz
    ├── 1e2aa251156e839c35e04decea287d7142cbef6c.nq.gz
    ├── 1e4212a225c402fa56c7c8506fac864dc6085139.nq.gz
    ├── 1e4ac8ae37bc58627d9cc639a1bac2c6115bd9b3.nq.gz
    ├── 1e568f04b670d887df2e5bdef59651c94c6f4165.nq.gz
    ├── 1e59be8038e0444d74be7fbf18918687ffd9a1eb.nq.gz
    ├── 1ee342aa6aa44cec9967dfaaffed1881a7535c5e.nq.gz
    ├── 1ef0edfb6c62cba044c105bb387e3083ba44f7a5.nq.gz
    ├── 1ef11764c74cee66a36680cc65dd8fdec2ecce75.nq.gz
    ├── 1fc69e8c37b113d05562569ca8489d0ea74c78a7.nq.gz
    ├── 1fd9b2e0050ee0cfed2d5a67c0fa195e54e25896.nq.gz
    ├── 204114b94018bac57900814dcfa418d85c080941.nq.gz
    ├── 209a27a5baccce97def81fbac5a19b08edf0c037.nq.gz
    ├── 20aa253b8c18a4f1033a1ecd358c38804d640cf6.nq.gz
    ├── 20d0b857ff113c1c4441291f4ed1b7159f6aa7ce.nq.gz
    ├── 214bc8f3c205b46ccfaf377fefabd6b18767316f.nq.gz
    ├── 2156cb5884e42d5112457c2bc1ec375c52d8b9a7.nq.gz
    ├── 215f74b199eeeb5a171e1dff61648b3f1267a625.nq.gz
    ├── 216dd0a21916c98f964e0dda8d86dad3ef622ae0.nq.gz
    ├── 216ffe843fbd95f66052cde17ee13711f312cb08.nq.gz
    ├── 218aff8e54cc5003e4486ad2605bf9cc2e74bed9.nq.gz
    ├── 21ab7bc115cd3a1024574e625cbe42c3ec8ea045.nq.gz
    ├── 21e6ca0716225a32f445f7ea8e3df773ac76f534.nq.gz
    ├── 21f76ced16e0927f7ea7cf3997d12edada4b4f73.nq.gz
    ├── 21f8ffb86976721df82ab2d93568cae27d9ba190.nq.gz
    ├── 223e81bd8a7f3fd3d25726fbb196e256b865ebf7.nq.gz
    ├── 226fe3d37886d71f60a8cebe51114ee60250483f.nq.gz
    ├── 23443e1fa15745c93a86190be82ba0ea4584a36e.nq.gz
    ├── 23d8588752f0034d37ddc371509fa2655fdfbc67.nq.gz
    ├── 240cedef23ffee1f8456706342b0bdd7d1872439.nq.gz
    ├── 243503086ecfd719289499825715c9985ad4c8da.nq.gz
    ├── 24b156f0295ed2238f5866a1c4e61231b8c5f94e.nq.gz
    ├── 25d4e6d35b57d8a8c0d4d0baff6505c61f12a0bc.nq.gz
    ├── 25da46c4d5c340a2e698925e5dab90eefec1d5d0.nq.gz
    ├── 2618f1ad110a7d2d0845f498134532f20005a79a.nq.gz
    ├── 2638ad15423b50f60ca26e9ad0c568f6c88798ef.nq.gz
    ├── 2698a8861af1907430a81d4d2d89dcc51757a1f4.nq.gz
    ├── 26a07dae12f5d60821cfcc21aaa3a1642c7ea944.nq.gz
    ├── 281d5368ab85c37f05b711a3d614d054e38e1d89.nq.gz
    ├── 28836ad7b2286601f89476c0367bd0aa621a17b1.nq.gz
    ├── 28bec25db7e26e93d2645ba6a6d37492fb29421e.nq.gz
    ├── 28c25a8cefb2807aa17fd6ce4765af6a3db1c66f.nq.gz
    ├── 295af00b1dbcccc15b1a4ceac65d2829cc5f5ee5.nq.gz
    ├── 2960a15f589e72e76f9d6f7f097dbf235d2e66c3.nq.gz
    ├── 299b73ae744d9f1aaaf35ababeba6f61c1c12950.nq.gz
    ├── 2a418d05092eaa45c7c76f152da25a29f2f09c7c.nq.gz
    ├── 2ae9628935f75f7b4663f798788af19075595e89.nq.gz
    ├── 2b091cbbdf054ca76cf8ac15ff4ab744ba7a274b.nq.gz
    ├── 2b44ad1196e463b0b824100bde88779cfef186f0.nq.gz
    ├── 2bb54c29cc4209a07780d420f2f0d0e1a788480d.nq.gz
    ├── 2c00776039f0faa3f02b44c8fbf99c40024bd72a.nq.gz
    ├── 2c26feefa028b405eda06fcdf9bc3f6bb8d07d49.nq.gz
    ├── 2c5e01dfcd74cc140497f34c73f8ac183740e4bb.nq.gz
    ├── 2ce62b1e851e1caa3c9f2fa7a2cf86b1509a4514.nq.gz
    ├── 2d2d3ec17bce031d54bc191a85fcda41ed65b461.nq.gz
    ├── 2d6c9904624f466271d6743c52de09f46d09b7b8.nq.gz
    ├── 2e8b40b02651d5a591bb2ce9667a7ee097dbdde7.nq.gz
    ├── 2eb9dc70988c1d4c9992d0d06f0b41288415d5cf.nq.gz
    ├── 2f015aff795f3c6b5bee6f884d7d3498fa1e6918.nq.gz
    ├── 2f84dca4ddc83a31bcac884486bd03c31564a4c2.nq.gz
    ├── 2fb4320f256c4ff8d87cb0a1a662deac0ed03690.nq.gz
    ├── 300df6ca6faf415841752f201ffc6fb49572deff.nq.gz
    ├── 303c380d7c6f3866a3e2a3b4fcfaeda9985ed5eb.nq.gz
    ├── 306142e9ef2005a3dd55a4f8ddcb3a3a0546a503.nq.gz
    ├── 308702a38c5437cfa3ac17f7f22fbb64ca813a8c.nq.gz
    ├── 30d27691a396a173adf66154a19e53732b1dc4ca.nq.gz
    ├── 315b4c0fa089928a995e7ec5f7212aa67e7b49f7.nq.gz
    ├── 31f33390c26549a14e52665385386f70fd8e912d.nq.gz
    ├── 32299ef21e7546c731e4a3a122e2423bd1055a52.nq.gz
    ├── 326bc78146bc745259c9362538f668144c53569a.nq.gz
    ├── 32ec3395156d86eab8a53f661b532a35277773b5.nq.gz
    ├── 333f895b1846386050fae5eb09cb7336aaa6ffa2.nq.gz
    ├── 335cddacf1913f7d45d668588b63b9f34017a8e6.nq.gz
    ├── 33788c7a3e2805ead7cf28e468890f07a86e0f90.nq.gz
    ├── 34407a3fb61c37caa77d838f871a35d2e87cf6a3.nq.gz
    ├── 34cefb64984be63cc7c524d0ca9257cc06701c99.nq.gz
    ├── 34d2328f14c82139f0f2ffec0b4a3ae81fc970a5.nq.gz
    └── 34eef8e7a4ac561c6cc72cd4f83362a5277427f0.nq.gz

8 directories, 200 files
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

[toml-rs/toml](https://github.com/toml-rs/toml)

---
*Parsed on 2026-04-13 by [repolex](https://repolex.ai)*
