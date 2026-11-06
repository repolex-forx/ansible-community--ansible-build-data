# Repolex Knowledge Graph of ansible-community/ansible-build-data

RDF knowledge graph data for [ansible-community/ansible-build-data](https://github.com/ansible-community/ansible-build-data), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-community/ansible-build-data
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1db43b29ddd6ac154ccbe890136ddf21f49a31b9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1db43b29ddd6ac154ccbe890136ddf21f49a31b9
│           └── chunk-001.nq.gz
└── blob
    ├── 000757ef1fb0c4091b27f9494cc4e6c112b1ac58.nq.gz
    ├── 004981e11e0988b77b4b423ae4d4453eb6471dcb.nq.gz
    ├── 02c67ce9b8f007c545f96575c8d2f613d153b7b1.nq.gz
    ├── 02efa35f8afa1e974a4236835a6c9ec3db46d5bb.nq.gz
    ├── 0421d15e3d01a721b9f44433a8b9f665c71d4ab7.nq.gz
    ├── 048640c7f011b4a3e7b6de981828311d41b95c84.nq.gz
    ├── 05d04e04c45cf1ddcf578781ff6d1982fc551db4.nq.gz
    ├── 05d2e18636c15f53cb7679182e7a782455218153.nq.gz
    ├── 06966afd5140e4f1c671186fa544f5e41820deaa.nq.gz
    ├── 06f83ffa25a456d373f8b64365fdf390a2a90b79.nq.gz
    ├── 072eb6530768fe3a04f886d18f5b87ad9ee30963.nq.gz
    ├── 081ca9184fedbd0aa1ab13a84e78d7c99e0ae136.nq.gz
    ├── 098bbcc70cfda3ad9b9931abc0f5236dfd2401cd.nq.gz
    ├── 09a5a61d3eac131027c5fef9347201f39571d480.nq.gz
    ├── 0a18e71a5ce8ff7747d49d6591e48b862b7d2243.nq.gz
    ├── 0a212542704c256408dd3f06a6f353eafececce0.nq.gz
    ├── 0aa2822023e8cd3caf255666403f195725e6033b.nq.gz
    ├── 0aa74824d16fcac435526db7a11410002c0b7020.nq.gz
    ├── 0acc1bdc8f90807a114d307c0d86135437c225af.nq.gz
    ├── 0b0cc7b6ea198b205dda57c7600e8c19e81c5307.nq.gz
    ├── 0ba48f73fbbd91df661fb04c4a4e1531f72e252b.nq.gz
    ├── 0c7cc1792984d7801d4f0c651697d8f722193e09.nq.gz
    ├── 0c89a435ace77acd2aa77d943db113ce43c34367.nq.gz
    ├── 0d3ba841d066f44789ee29adcdbf30fc1b15fad7.nq.gz
    ├── 0d8d310df4e05b0776484dadc7874fe7791be58e.nq.gz
    ├── 0dd41b14a8ca64e9b6217e97201ddda30c66ab66.nq.gz
    ├── 0e0f2b3b28f95bded5c05d82ac73def22658ba10.nq.gz
    ├── 0ec94026e80ea9392fb5e823f5bec86dac6f17f8.nq.gz
    ├── 0ed592e5ac3cae95c5067fc283b316851c0eaf20.nq.gz
    ├── 0f9a80bb8a824a2b97232e9a7312bf56fa905af8.nq.gz
    ├── 104b0a62b3efbefe0ba20b6937835d440c134fb8.nq.gz
    ├── 106b3b7a6e383f192eb49566a4749895c2243eb8.nq.gz
    ├── 10f751272fe7e75dae02cdac72f1dcf6100041fa.nq.gz
    ├── 114ecffc6654a3d6b2cd3bb27ae449ecf0af4b6e.nq.gz
    ├── 12665185df3345f7da64a4f2158d0764063a4758.nq.gz
    ├── 12be6f179d1b981065467bac0e565c2d9ca4f95d.nq.gz
    ├── 12c8c26015391364205318fdfcc10fbc2c43cf12.nq.gz
    ├── 12e405474aba7f38d3f6798160cc6cc5c554a53b.nq.gz
    ├── 139b04a4e89efaa9bd27bdb66c933d7d4425572c.nq.gz
    ├── 13bcc1397955b4e632d6e52fcb8a4ca9883f439b.nq.gz
    ├── 13deefa7bb0995e82db427009dc5cc9ac9e57284.nq.gz
    ├── 140890aa530a3a2b94af0ff44737fbf15f423534.nq.gz
    ├── 145dc25e0030ca23561bbb3d22dfc0e5ccf491f6.nq.gz
    ├── 167103514f16ba33ff8b9ea3686cc1d2272ec45f.nq.gz
    ├── 16b185850047af8758c7eb60a75d62b439078d42.nq.gz
    ├── 16ffd1569619837640a0685bbb699e327c7e0d97.nq.gz
    ├── 172bf2bc96e689cab7da73098fea568c1411b6ac.nq.gz
    ├── 184a241af31d470afc997dbe7406deea6d1fe0cf.nq.gz
    ├── 19204c692b9a54cf73371942086738f6b5c8c8eb.nq.gz
    ├── 19459bcf020848f6af7aacb1970659930655cf1b.nq.gz
    ├── 19559be70ab092433582e4014db1769a8cb2d52a.nq.gz
    ├── 19e1bf6702abf546a4aedfcdf147fb5b03f986a6.nq.gz
    ├── 19f51be4cc792dfdf7bfe3c31163c12985432acd.nq.gz
    ├── 1a1fda83fee2b9ad9194cc2921b21241a98d4097.nq.gz
    ├── 1a24aebe84c48dda3a9cee8890c82f50a9bc9514.nq.gz
    ├── 1a2f09432e6afda2081f0d4789f4cc320d06bb5e.nq.gz
    ├── 1a36b3fb00ac5b9f817c63e477e9c1384edbf8e1.nq.gz
    ├── 1b817a9df117910a1825e1dc7559c510871a1063.nq.gz
    ├── 1bd15af88cb9375b1d0d107156caa37fcfc1c663.nq.gz
    ├── 1c2eb3858c9661139dbdae9ccd2a79f98244cd09.nq.gz
    ├── 1c540ae329f18ed00748f8c873226effd02b07a5.nq.gz
    ├── 1c9f439a677f93ca029860ebe6f03c351825c8dd.nq.gz
    ├── 1d22829ffa394756a88d31d49bf32903c16f54e9.nq.gz
    ├── 1d6058c0b8de78999f08079ed813d63e8ec54747.nq.gz
    ├── 1e7fe1850cfa5d6c3bb0f93f79c09c25aee0992f.nq.gz
    ├── 1eb2f09020797cb1fc528913c5dc0ef2ed1bc45e.nq.gz
    ├── 1f76ce623a3d84175de6dea626343046ccfbf708.nq.gz
    ├── 202deadd4c93083e222b3254a55b86b71e8c6ee3.nq.gz
    ├── 2145769c25bf4cefde36ec0db98aee3f3c099abc.nq.gz
    ├── 22c235c499e6bbbd86dd7b6d2db33f03acee6861.nq.gz
    ├── 22d56c77764602e6caf97b9f674a35e491442b6d.nq.gz
    ├── 232c0b58eaccaa3bb9849134c9adb96987ee71b0.nq.gz
    ├── 24bdeae6be3c0ef92c78e9fd709d22f679378443.nq.gz
    ├── 256acc00a5ff42b3669e7028b306290c45010e3b.nq.gz
    ├── 25dc53176bb02747c795a46db37eeca0debbdfb5.nq.gz
    ├── 260ad7ed569b7128db4145fbaf2507b235ab4106.nq.gz
    ├── 2647d551e6c78d6b9290709c21e01301c80f6a21.nq.gz
    ├── 26da6254afc6f4e39d0e7c0a62e6ce6892eb7b7a.nq.gz
    ├── 28f01c5c504fdacef1e9144f6e540d6711e6bb56.nq.gz
    ├── 28f1327441cdfd1640f308d6e060026d785d9517.nq.gz
    ├── 29f5ba417dea32ce9b4f40e3fd4e96498eb3909e.nq.gz
    ├── 2a5868da7897631e4993fd864b88a637ae46aa1c.nq.gz
    ├── 2b0451f35c6cf10a60773fa1096f7375ba7e8d62.nq.gz
    ├── 2b0bc4efd1043c6fa19cefe73102b81d8f2ea671.nq.gz
    ├── 2b49144f75eb241bdd6837e0ddcb3b1388675a6a.nq.gz
    ├── 2cdcde9b63edd8a473fa0a1f41513caf15d33551.nq.gz
    ├── 2d2ee864539e440ef4b46cddcbd8b32c2450031b.nq.gz
    ├── 2dec76d802ae1aa356834ca076388fa94cd4dd95.nq.gz
    ├── 2e28230d85f1203ae7ac018f3014d6f22adb27cc.nq.gz
    ├── 2e4a0142d42b9881eb0f3eed275b722ddc86fd05.nq.gz
    ├── 30bd4eb8d78c9d7a721ce17baa9db025522dd0d5.nq.gz
    ├── 30ccad5e6e2599b906725782ce9082df46f1702b.nq.gz
    ├── 31630269833d616ebe190a4891d26e4db3524f7c.nq.gz
    ├── 31821c8de24adcc4311b7959d028d9cfc206f0f7.nq.gz
    ├── 321a09d25cef428e369ed65f3658822e20d5e38f.nq.gz
    ├── 324764acfc58122564f2c66c3f6b4f5bfe718453.nq.gz
    ├── 324a5ded9962ff738e5f7c37eb32ba5c2bc49a2c.nq.gz
    ├── 324b277d0cf1fa0e9462142cbea1b2f4b757737c.nq.gz
    ├── 32d46ee883b58d6a383eed06eb98f33aa6530ded.nq.gz
    ├── 32e791f7b4973615a8313759e78afba3431dc192.nq.gz
    ├── 3355d66c0fe1ddf2c741bdacf9515318a2efdfd9.nq.gz
    ├── 338a7949c3d1c5f1e3b36b02c94e2c1bc32d99b0.nq.gz
    ├── 33cdfb02170b60152126d02c1d77485b728b6168.nq.gz
    ├── 33d1515c2c0bba3d91f9219dd740e648d95799e1.nq.gz
    ├── 34230af8e7096480005932e46d9096c7f10f5ff6.nq.gz
    ├── 34871571d8b95338ef20fa9d83a437c706b54054.nq.gz
    ├── 34ac736453292442bb429d0d24e81daac5a192c5.nq.gz
    ├── 35cc214addd874a041a4ac9e2e68c96d609bfe33.nq.gz
    ├── 3717d35db0b4dd253683e2303e75a27ad3228741.nq.gz
    ├── 371c290ba86ee465a27781dd0d2c9e4592b7223e.nq.gz
    ├── 3723b07b05fc287fe54ccba4729dec9fb7ff3ea9.nq.gz
    ├── 37557ac7f4ed641ba3470525c8549460c5946640.nq.gz
    ├── 37bf4c409a05e79e0720afd40c6d37ed6d5ab862.nq.gz
    ├── 37cf9295da8e266520902420cea5be88cc3d8119.nq.gz
    ├── 37dcee5a4cd764a33e132bd9b5a2737ebc96585e.nq.gz
    ├── 3875ded1b9297e7167255c1a712d443af16874fc.nq.gz
    ├── 389386eb4c5c939402fe78bb1368af3b5f1d045d.nq.gz
    ├── 389c11227b29a864df39e543a548722e8bd5e116.nq.gz
    ├── 3903a83661378fa41970597c134dce4194534d58.nq.gz
    ├── 393a2c83a72de2a61ca239ee70ec0f8805400624.nq.gz
    ├── 393faafca34bbece0280576868ab166b21375ef6.nq.gz
    ├── 399e2698a1e6e781ae372bf57b6fe7f8f73f2b52.nq.gz
    ├── 3a981fdf75a39968f278afd1ad2ca4eb0d2e220e.nq.gz
    ├── 3ca6f9607582854bfa0ca62a27a483f3671a48b5.nq.gz
    ├── 3d0b9dffddd1a4d7c62575998fc6e5826ac76371.nq.gz
    ├── 3e179ab4a1ba2ae3ba59f84dc3f0099860d46224.nq.gz
    ├── 3e66dda96effad4ca84d7a666802c0759bf2a602.nq.gz
    ├── 3e72ea82b9d0e80d8af10b921dd7184e723ff0bf.nq.gz
    ├── 3e938e91820a93edaf28fe511ddb3b482905e442.nq.gz
    ├── 3ef04f0624d2a0028e3d13473bb3496d114be2c8.nq.gz
    ├── 3fb4626f0f5fb9fbb8ff1a604ec249e307ed2d18.nq.gz
    ├── 402deb3c5f90f24e3300f6f910480dcce19144a3.nq.gz
    ├── 4069dd34e3f6c3b34c492c67000f38688ab978e6.nq.gz
    ├── 40c7a66cc8461c69e1062620bdacf5ecd8f5fa25.nq.gz
    ├── 418a4c72c3a3c59cda5c09751b286ea14c3ecf8f.nq.gz
    ├── 4327dcf24bb90ed7f2a40996d91b60b48b03ae5f.nq.gz
    ├── 44103ef16a2cf28891584268588c2d578f4d9e80.nq.gz
    ├── 454e6dd77bdee5925cff1606bcb2d4cb737495c4.nq.gz
    ├── 45b487722d7e820012e91f73f9558e736cccb754.nq.gz
    ├── 4657088f7a2b5aa9fdb8be0454aabb58ea7c146c.nq.gz
    ├── 4a0130301c7717992f8677c6fa3b55ad3e63ac94.nq.gz
    ├── 4a222ff5ae467801a9d85d84d5ea42673f02be2b.nq.gz
    ├── 4a3e2a2afc72e417fa10dac4a573af38ba55600a.nq.gz
    ├── 4a9879607b520a449ad2e56a1ace33588889d27d.nq.gz
    ├── 4a9b92909b95907b4ee315d4d448be06a7a8d5e0.nq.gz
    ├── 4ad3be0eed29c631d6ed04c297e18cb379b3703f.nq.gz
    ├── 4af37eb336c47138a89db360eff3766b02f85996.nq.gz
    ├── 4c330f363462a132cb5b0c56af1859c445886189.nq.gz
    ├── 4d2395eb66dc5874fbbcab0b735f47336b886cfc.nq.gz
    ├── 4d6693cf4aacc830e82e9160ab212afcda392902.nq.gz
    ├── 524de2c59bf604a41dfe6f82e6420f7f70a96e81.nq.gz
    ├── 5296a2ff1290655f0aa729517be98eebf03f1547.nq.gz
    ├── 529d68f8041317a3dd538e6dcc910066fb2783c2.nq.gz
    ├── 52ae4fccc56102b77e0db07c865dd910c9d75480.nq.gz
    ├── 531b5c61dd2406dd973636061ada523ccd5b8ae8.nq.gz
    ├── 53980d20e8b71868423ee13c3be3704977b893b9.nq.gz
    ├── 543cb1f04c74b0b135d4a0596a15d4f926ea3b72.nq.gz
    ├── 545b033394a52ed2e9a2433c4bcba7c326b5b9ca.nq.gz
    ├── 54feb9f9a36d2314f02766dd21623a7a272ce0a0.nq.gz
    ├── 5531b2fdf008c693e112966ff09860a4b1ca5a70.nq.gz
    ├── 5575731ef62defdb9e9b6d420042aa455f381e8f.nq.gz
    ├── 563a3621369b4ee98b5a59871d75d2c8cf9fe6fe.nq.gz
    ├── 57b52ab2f12f3f1804e6d3540ef6f5e6df55379f.nq.gz
    ├── 5aab93aec03c35cc036f54d16dd8248622246abe.nq.gz
    ├── 5ab105ef3144b616c454aa24cb68b5e3c9c3b13b.nq.gz
    ├── 5acfc64ac5b7de2a49752422b582752eb89bcacd.nq.gz
    ├── 5b01b5008f64731da96ae67192492a5fa597238b.nq.gz
    ├── 5b0b5bc91eede40b0efabf4bb58f8d6b950da22c.nq.gz
    ├── 5b4d59566a11575800ec6dfb43baa3cb3c8c0340.nq.gz
    ├── 5c528f8f40458a17e26a44f354db0d6baccf92d7.nq.gz
    ├── 5cc77acf3d019d3a7baf4057e350ed3c64a8a80e.nq.gz
    ├── 5d4394869e5d952274846f8de8acc48280d3d770.nq.gz
    ├── 5da66d61f37a9d6e4fbe0dace4164ae8e75cf05f.nq.gz
    ├── 5dba2aedf1e1a31595bb4ef35ec6bb18b916accf.nq.gz
    ├── 5e08e049a7422feb9e9f553b9b705fcba99133b4.nq.gz
    ├── 5e22ff253e6cc3949593a892c96ecb9f9976c8e8.nq.gz
    ├── 5e321929c80393e31d88638a951b98f15e870601.nq.gz
    ├── 5ef50f91a535a46a18191c2f267886c034932b2e.nq.gz
    ├── 5ef5952781fe7c08bba8055e4982a8a6951a4ff4.nq.gz
    ├── 5ff19d0b06b46c5e9bb16b8b27dad279d72106df.nq.gz
    ├── 608b8bf5a3a7e720b5e40748b0c76fa545d26913.nq.gz
    ├── 609584c0b51890286835bd69701fcfe02b02e913.nq.gz
    ├── 61e66b09307a0cc69ee0aebd420efcbab5a57b5c.nq.gz
    ├── 636c3eeab0a46cac72bb54b10de929295e8e8f65.nq.gz
    ├── 63bfff46cf10f1fd819ee28c21027cacc96bcdfe.nq.gz
    ├── 6404eebe8dd28d8cc26263856970887c1c109e1b.nq.gz
    ├── 651dceb92399c0f85573adb07650d0622002c381.nq.gz
    ├── 65678e1c68822d99e33966c11e8eb922208cecaa.nq.gz
    ├── 66708518ba145f4da9551c867af8c2b602db16d3.nq.gz
    ├── 668bcc031352a90d1d29012a22a5f6f3528c190c.nq.gz
    ├── 66be7b8ae8cae9d943f07613a8c1c5d2c9d51509.nq.gz
    ├── 66ffc3698c8bd41906078edb07f8f556b3a13bae.nq.gz
    ├── 679c04b3f9193a439585fb2e8a42f81d1c79b1d0.nq.gz
    ├── 679d26667fbe595704af5d3cb21da69af05861a0.nq.gz
    ├── 6823d6d919522eeef501e56a4311ece3227c3ae4.nq.gz
    ├── 6906861ac9af8373d0f2e483d2df6cabd88bf9d0.nq.gz
    ├── 693a236d9591d3628034c76a2e46dce2ee13dded.nq.gz
    └── 6a299d840c7d35556c059cc928a088bff36a4adc.nq.gz

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

[ansible-community/ansible-build-data](https://github.com/ansible-community/ansible-build-data)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
