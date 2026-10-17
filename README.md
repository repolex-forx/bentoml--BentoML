# Repolex Knowledge Graph of bentoml/BentoML

RDF knowledge graph data for [bentoml/BentoML](https://github.com/bentoml/BentoML), parsed by [repolex](https://repolex.ai).

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
rlex download bentoml/BentoML
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 517b343b81aeb0b01bbd908e58e53ad9c12ef7eb
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 517b343b81aeb0b01bbd908e58e53ad9c12ef7eb
│           └── chunk-001.nq.gz
└── blob
    ├── 006069655ff2fa629406b7fec94ed8566582aa07.nq.gz
    ├── 0097de9552e0a857d054013765d45799cd55be32.nq.gz
    ├── 019a4c6f136b90ba6bbe6b2a165c461a31de9230.nq.gz
    ├── 01a21b4f7c5e0aa36239ae43aaa14cef1665f49a.nq.gz
    ├── 01a59b011a48660bb3828ec72b2b08990b8cf56b.nq.gz
    ├── 02360af4a54f2aadce55a13a35f1b5832f8747df.nq.gz
    ├── 02a1276eadf75728dac93d16098cb66615de1e66.nq.gz
    ├── 02b8b452d6c56343ee3305e26ece765b491d0d59.nq.gz
    ├── 036f5fb61365800c7066208aa4df1de7d2a1b6ea.nq.gz
    ├── 04329bbd804be79250f620b885ed47c4e0f000cd.nq.gz
    ├── 045fe4327feba6b85c6620e528760b69612f6cbf.nq.gz
    ├── 048c23684b2ebd60d2c13884464af8060d05c58e.nq.gz
    ├── 04d8a6361735dc3fce9d45f0976ad67837aee64d.nq.gz
    ├── 057d0a665738c4f504bc4910f166b34c224a30b1.nq.gz
    ├── 0590fcc444e46fd9d525e972361944e99ed532af.nq.gz
    ├── 05916bac9a32e61d7e5828428d016fbefef8507a.nq.gz
    ├── 05b72634506f22ae18835e7581c1eb3db287f771.nq.gz
    ├── 06b4722a2b992b0fbc54df809074e53a785a4b00.nq.gz
    ├── 0730e63fb8f1304c500a7278ef765b1f6f4f0924.nq.gz
    ├── 086b54055cb2dfbeff508820ca97184acdffb3c4.nq.gz
    ├── 095b56258affe0162a09cd130ddb489c6217418c.nq.gz
    ├── 0b95d6f7e3108be55515f04f7668451aa28c0059.nq.gz
    ├── 0c647eae59b3039750f8ef2e2a5e48521770d448.nq.gz
    ├── 0cf17c97e845d0d44f39b223a45fdaeee71d27e3.nq.gz
    ├── 0d23a2789f2880ebc2ef9f16ebdc03124e35c013.nq.gz
    ├── 0d24797e7ff7fef9c1f022afb39ffd7dd22cfcc9.nq.gz
    ├── 0d52307be8c3fc38cd4821c6e1cdbc29dfa09b5c.nq.gz
    ├── 0dbfc2640270e9e16c4f3f25a64d38974de0eb08.nq.gz
    ├── 0ddcf1e7a98b6829094805be495662905fcd13ff.nq.gz
    ├── 0df5f84411ba60637fa0f76a729cbf1a68f77397.nq.gz
    ├── 0dffe6f70544a57d5b723b2ac520067c42c3d92a.nq.gz
    ├── 0e41a5cf028401ba7d90be222948fa9994256f4e.nq.gz
    ├── 0e52ddae568ea9943a7a2868bcaa065b4ce5e734.nq.gz
    ├── 0e91f2109c1b434f561a50478ce5124b40b7d6ee.nq.gz
    ├── 0ee62d8691569aaa2e26bfd54dba1426c79177ab.nq.gz
    ├── 0ee773b3e7c110292b7e0f95ad83eb16ba5ddc4f.nq.gz
    ├── 0ee9a36f4d3f3ec8ac293f0e71cd503970d0c72f.nq.gz
    ├── 0fb2a2110cce4446e40f0e0fdc39879e30eaa77f.nq.gz
    ├── 1142e46dc4e841f5d3800aeacf44cf0c286d33c2.nq.gz
    ├── 122186740f41a3b9ffbeafc736d9cd9bb5ef191d.nq.gz
    ├── 12895733023b9b14dd85d1120143852a9e9a75f0.nq.gz
    ├── 12f7f9842f32e9b95312f721b0e0dae863c5f8c1.nq.gz
    ├── 130e237ec806af4e3e9aa261151fbf472574eadb.nq.gz
    ├── 1376462be1b291e16b215a43c76a4dce38ed3e9f.nq.gz
    ├── 14235c07107d3ab0830a7ce6231b9ebf4bc6a4a5.nq.gz
    ├── 14fdc33085c7e6e004008d453763124c579e65ce.nq.gz
    ├── 1507dc914bf2ad257aa5e39032a86f80af27f272.nq.gz
    ├── 150ef0142fd297138e33dcab63a24468c4b7afe0.nq.gz
    ├── 15ea8bb454a81248542d3eb2604853a91da79f19.nq.gz
    ├── 16c8efb27fbb830838730c8c861f01c76ddae7f2.nq.gz
    ├── 177120abb8491c125f248907b5649728e269018a.nq.gz
    ├── 17cbab4fa053e3a6fda44fc9c6cd44c984205625.nq.gz
    ├── 17ea90b33fde42892c7dac6a62a62a53a9a38831.nq.gz
    ├── 1828d4dca9f5e2f527848b4b6bc125c27e284ebc.nq.gz
    ├── 19e74b14f8d817b0ff9dc4988f116ca0600be59b.nq.gz
    ├── 19f88ad3516d9bb4ba63c9fb72e73a07993cebb3.nq.gz
    ├── 1a61e1b294d15dbe75c35ad5b1755aaee0ff24f6.nq.gz
    ├── 1b912faa8526ebcfeb6526d12976dee035e3ae01.nq.gz
    ├── 1c8e6a9d5a8fb847c70da11cecbd30a6d678b9b3.nq.gz
    ├── 1cabb203f3704257d87d2dc5e39850a2178f02f2.nq.gz
    ├── 1d6780d0c260705419687aa72b47bc06ca3933d7.nq.gz
    ├── 1e83d86e5696b7a8db9e85378e2ca88ea96ee3f3.nq.gz
    ├── 1f45df38fc2d00ef3493add5bf4bb431da229bf0.nq.gz
    ├── 1ff00b2ebf8e0dd4299c720c0b45a350ad5bab99.nq.gz
    ├── 20ba75139115f4adeb5e22a5d471355ef52eb3da.nq.gz
    ├── 20caeb361176812463b8f4611b6cc5b2cfccd971.nq.gz
    ├── 20de4b90469d2bd33f85769f3e2ab0a160a389ca.nq.gz
    ├── 20f5cce47b084fa623ec9533a26e5841d61db38d.nq.gz
    ├── 216437ee4fdc045138b0bdbcbb90a251d974b00a.nq.gz
    ├── 21deedb0f17f0cc7687915ed720e373312ae36ea.nq.gz
    ├── 2200abfdb949d4fbc6218b3c8b4dc7d0ae57225a.nq.gz
    ├── 22895e85715e98596af36e45992ddaf77eee1922.nq.gz
    ├── 231bcb00f2e3fc427b6e701bc421da36c597a0f9.nq.gz
    ├── 23ecfb1991ac507cddd1422de468eaf1c369e516.nq.gz
    ├── 241a02348461130d82788de53fc350f97515d5a3.nq.gz
    ├── 257c3720737dc5b02e53013688d91d4c357d1686.nq.gz
    ├── 25c00beba97e79d4e1c878bc05e264875a3f9a28.nq.gz
    ├── 25dee6c839b5a2d65566766560fbcfa225a58415.nq.gz
    ├── 25ecabaca0ff69d648f958a13a08835c1a994752.nq.gz
    ├── 264be793577ee94a31578a63896783d120f90d2a.nq.gz
    ├── 2772c463629e79d00af9960b1fc3a0c2ad45b162.nq.gz
    ├── 2949a955cbca03359b5dd49c7f25294d9176e13e.nq.gz
    ├── 29a97f1d53a77af62dc9a7aafb3e86b4135eebc2.nq.gz
    ├── 29e9415a2b8ad5d0aa1c426eee43cd3dca2714a1.nq.gz
    ├── 2a222a42b919f1a02ac0a0023157e870ff3995f3.nq.gz
    ├── 2b1df661db0b3ddd059bb478c6d0902cd9b6fbb9.nq.gz
    ├── 2b2437eacb86f7e934051466436a7c73139ce0d8.nq.gz
    ├── 2bba3e9486b13420d447003f50f8208510b926e5.nq.gz
    ├── 2c0733315e415bfb5e5b353f9996ecd964d395b2.nq.gz
    ├── 2c0b1a997dfc7b606c4334d54bedf8c11b7f1e42.nq.gz
    ├── 2d06f10ad216e1bf31762ea4b999216dec9c4618.nq.gz
    ├── 2e4033ec527918cc55e8ce4c18ee31cd8f2410fd.nq.gz
    ├── 2e4c5dfece4fc93fb2e4a9e7297e009ef4f1725c.nq.gz
    ├── 2ec1205811e9910bf1d791e7fa0c5b75a1584874.nq.gz
    ├── 3045939dbf77ddc1c1f8d80a96ef5a0596d36bb8.nq.gz
    ├── 31b35c17f6f0257ea71b3244536e21aeae6c30ab.nq.gz
    ├── 3231d7ab8a5c9911146d84d724086d6acf5c3233.nq.gz
    ├── 32c43e067d42d6af59e22deb8c47098a78cbe263.nq.gz
    ├── 32e0138c63c3bef94d10d384053e1c43fd7b8bd2.nq.gz
    ├── 32f24cb594e9870bc14e462f8b0bbd88c6369bb4.nq.gz
    ├── 33792f88b6b66e9816ca05a10ac212acb995e9db.nq.gz
    ├── 3426e1819c2e3ee0ee290fcb715fcab324b8bd90.nq.gz
    ├── 34b137fc5a9a535cb9348e40d58ead2aec0ec414.nq.gz
    ├── 3561143363a322e2344ccf191ad641e29683d2af.nq.gz
    ├── 356ab1ef5ae5552107be0ede8ccb161e4ddac518.nq.gz
    ├── 36ee81184264dd78c04b9fb804d55b93256d40a5.nq.gz
    ├── 3724dcb6e93685d501fed0996b007a91abee7261.nq.gz
    ├── 39babd76acd3e32bc0cd75a56b69ce2862ed04ed.nq.gz
    ├── 3a01346fbac197f27aae4c0ab0e60bb887341df7.nq.gz
    ├── 3a196754c9a95678349232a31fb62577903906ca.nq.gz
    ├── 3a23503429b29f95bb66dd92eaa500b097aeceb9.nq.gz
    ├── 3b4803d8fbd7cadce5907d1a9e8022d70e00033f.nq.gz
    ├── 3b521aceafe339c2b1eb75ff176b333028fd39ff.nq.gz
    ├── 3b8870d4176ea4c0a913996e25acfd0cb8ef394d.nq.gz
    ├── 3c53f28bd66d757c3659126d9c90a50e470107db.nq.gz
    ├── 3c7b858318d92fe4df4b0e9feb1061e7c38cbb13.nq.gz
    ├── 3d2cc9f36691a2c5fdd34a697d9d89825fb6adc3.nq.gz
    ├── 3d9e2f2369bbc20a0be1c5a37e2c951e3472f78b.nq.gz
    ├── 3e5c471e25f1e30beb7517e5ce20a05a970c20fe.nq.gz
    ├── 3ec35a27ad6a2ac4c81d848e7028ef21aaa4f13e.nq.gz
    ├── 3f337e2b8965b6257598a1852277a70be3ce14c3.nq.gz
    ├── 41158412e2116922de5f02b8bfcf53077ba0acf1.nq.gz
    ├── 4148e6493a054e7952d372e09b3473dbc07c9e97.nq.gz
    ├── 419006f44ca7f1b0463a07f2ced80ea459d5b2ef.nq.gz
    ├── 41c352af0ba7eae5e1b034902a0ae84c41caabab.nq.gz
    ├── 42305d357b514007d1df0a0a99e57f8cc47ccf74.nq.gz
    ├── 426baa73762e1aea2fe6155f86e1661b04088fd3.nq.gz
    ├── 42928a4d04b8f87968bb4bee62b0c7cc27ec10f9.nq.gz
    ├── 42b55cfa9c0ca2fd53baf94a231a41cf9aeef9c4.nq.gz
    ├── 42bdcad3930728f4912c8d3ae58ae009251b674b.nq.gz
    ├── 4310b766ec8ff480eddc0565eec8ab50430fc378.nq.gz
    ├── 44037b6aecbfd2507ff5632a61197619cf818b17.nq.gz
    ├── 447bee00c3338e1c0bc901d28925bb69bec51ca1.nq.gz
    ├── 44a4db8778d718b89f9da1d243a303259702c0ef.nq.gz
    ├── 44b5fdba0349df761ff5d6f556c3676298287d0c.nq.gz
    ├── 453b9ecf2380dd11d9a7740d1f1ca4e122426693.nq.gz
    ├── 456079f78b3bf52a11605074cb57a2139f35b844.nq.gz
    ├── 457efbf9fdf46ad6f69958ddc27598f0560f753d.nq.gz
    ├── 47fa3b8216d891d5b64c3e2728fb07321497aec9.nq.gz
    ├── 480e86f28d9bd32cdb73738b66e403d1bccb8dc7.nq.gz
    ├── 49625f5d45e90182e9420cd3c052e57df04b4b29.nq.gz
    ├── 499781179bb231d89295ec9f82098d0821f20f37.nq.gz
    ├── 4b0d7a23ab65830b794b7b62c575550553fc187e.nq.gz
    ├── 4d34a217e5e8b763fc521e8660d9e2aaeebe1296.nq.gz
    ├── 4d4d9c2609b2b26513cb03486b38d82c5bd646c5.nq.gz
    ├── 4d8366ee64c8c93e1d470dedf0480402a9ca3c59.nq.gz
    ├── 4da0e281eb314699173c72d9009ce9bd3ead1e8b.nq.gz
    ├── 4da99ceb8fa3f494d4b2420b207db1a07626f1be.nq.gz
    ├── 4e523283112c51a13a4396ad42ee6c02732569ec.nq.gz
    ├── 4e72ca9f78e9069a08d7cfbda94fcccce3543835.nq.gz
    ├── 4e781072d433fa53c0b021a7d7a27fce9ef90650.nq.gz
    ├── 4eb86600fbb10205104d5b8184b38e697f6c65fc.nq.gz
    ├── 5017ce9c5d599deb400595d0014c4b01d3995f9a.nq.gz
    ├── 51a0eb49542322324cc768c30c57aa788aab638f.nq.gz
    ├── 525371730f6c2032b6cdcbe4c38cfe2f277fccf7.nq.gz
    ├── 528ca026b280290016996124af0dd1ab5c7668a6.nq.gz
    ├── 52a5626c57b7d684ad64ff01e123f33b465a9c85.nq.gz
    ├── 52b43fe2e2a5746e915a953cbd3958c68c0af19d.nq.gz
    ├── 52c2f2a01b1e4dac9525a94af3b777d34e76d79c.nq.gz
    ├── 5302969a1468abe0d7e1bb37fd483d97268d45c0.nq.gz
    ├── 543ce883aed239c5a9172c6acad99fcb66424808.nq.gz
    ├── 5472aa97e76b7203ceadc6269e0e7116fe005eb3.nq.gz
    ├── 5586ee217e310891eed9d37d35f31c5ed4f6134c.nq.gz
    ├── 5654132becf9529b64787febf6468423312d340a.nq.gz
    ├── 565704f333abbacf6d245cd156ea513b4da937ef.nq.gz
    ├── 5710b1791b54c1c90c0587cc3738d055fb1fa770.nq.gz
    ├── 5909e7dd1b012ce6c47d0d5af5dcc929ac4a5a1e.nq.gz
    ├── 59c75505ec30f73b9b329b4ecf56f1620440015d.nq.gz
    ├── 5a5d3010537c58f3b209717ab13583897a57efb1.nq.gz
    ├── 5ad6a6be3171b49eca8e1b62ea85c66f0a072a3e.nq.gz
    ├── 5adde099a7de048c4be7639502151ad1b5bfbec4.nq.gz
    ├── 5ae7c02b34e1135b67207add7a7f1fda678e2642.nq.gz
    ├── 5b37684ab502f7f9787bbcf0e70e701b56fe4597.nq.gz
    ├── 5b7686c9162b787996b96b3c56fb2fce5c2adbf1.nq.gz
    ├── 5be91695a54d16cee4e3894b9dc23f74f7cd9023.nq.gz
    ├── 5c2496055409bcd017c2914b97f221ad8ae48781.nq.gz
    ├── 5c46c42bac71bda16b45fb85a6190bf78c78d925.nq.gz
    ├── 5c6b5faf1b091b0ae99b1d646bf62e43cfc32da0.nq.gz
    ├── 5d117dfc1714ff081878d1955505dc68028fe0e0.nq.gz
    ├── 5d59f9cffc67f8ae592816bd3b4d7a90b9339d54.nq.gz
    ├── 5db9eaa74c03f001ab255346f3f17210176194e6.nq.gz
    ├── 5e44c054d7c97894bf3adc7fa46cf4fa04306db1.nq.gz
    ├── 5e6e04c8b9ddef396ea7692f7f5be83882e165e9.nq.gz
    ├── 5f194d5622a28cbbf0ef1b49e65a80911883b266.nq.gz
    ├── 600540182799726c799adbcdb7eab1b88a92d131.nq.gz
    ├── 6090b058719de0433fa7430fa1aa7bc771f6b7f3.nq.gz
    ├── 61360ba2645ac4a60735bc37e20f102aa457e27c.nq.gz
    ├── 630b74055ad36dd9e6158d9cf728df900869d989.nq.gz
    ├── 634990d14f3adcbcadbd277bc6a3301c54f35149.nq.gz
    ├── 63f34fe0a8bc16dd3c7124df1758cee36592ca56.nq.gz
    ├── 64015b100558e18f5e931512729c10482af4dcbb.nq.gz
    ├── 647bea90b9e62382f3cbd44bf5dbc738d9408750.nq.gz
    ├── 64b7b5de60478b287c41be131c57e1891981c06c.nq.gz
    ├── 6731d2e614bf5845228c023b4e7c7ab07a579794.nq.gz
    ├── 6754be0431a731c4b3d2e7677f6e66161b986df0.nq.gz
    ├── 67b1fac080bc025c8d80c428324c93844b7f466e.nq.gz
    ├── 696ffcce961bdfd2adc24a45387f607b91860230.nq.gz
    └── 6b2536240c8d5a93418eb292f937573138376e81.nq.gz

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

[bentoml/BentoML](https://github.com/bentoml/BentoML)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
