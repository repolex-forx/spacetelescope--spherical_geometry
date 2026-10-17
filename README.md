# Repolex Knowledge Graph of spacetelescope/spherical_geometry

RDF knowledge graph data for [spacetelescope/spherical_geometry](https://github.com/spacetelescope/spherical_geometry), parsed by [repolex](https://repolex.ai).

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
rlex download spacetelescope/spherical_geometry
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── f2b2b5628a0b1d80e98caf841f27e2dfab9d8450
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── f2b2b5628a0b1d80e98caf841f27e2dfab9d8450
│           └── chunk-001.nq.gz
└── blob
    ├── 01675ef3aab5a396c61c2b5a920f436ddb1ba433.nq.gz
    ├── 021d379534b159374f68d413a4d98a8a3cd68e61.nq.gz
    ├── 02f7a5a86651c0049afbcdc3dc06400fbb18e4d5.nq.gz
    ├── 0559ace6d52288d5d551788afc0a100fdf7c693d.nq.gz
    ├── 065daba8e58dc6e8d92031e4ff453a62ac94ccad.nq.gz
    ├── 06c1e76f87b1e19ae4ad0bd5923329a5d9cd77e9.nq.gz
    ├── 09591dec68643a0bb3996acdd215c66f1ae26b2f.nq.gz
    ├── 0aeac575d39a6ec49a5224790dd4489c052df155.nq.gz
    ├── 0b176873fbe4729d4015530e90fd8e73eededec0.nq.gz
    ├── 0e18b42e36c4b3c8b79454b30409bb8b12af6c95.nq.gz
    ├── 0e86f2caaf7abc85d33bdf66d923beae36e832db.nq.gz
    ├── 0f792996e035edf4beba84cc221a2c02ff0db148.nq.gz
    ├── 0ff3370a46a86ec11239803a2264d6fad23fc72f.nq.gz
    ├── 10c19026a50ffe3388f04099ec5f338b16c43d15.nq.gz
    ├── 10e206313ae95a2bf0434711f079fc30451f2b11.nq.gz
    ├── 11c4c7d7f190e93c74320d2bb0136d4c36d23f40.nq.gz
    ├── 14fa6a8cfa0da6372e295b4d8669bba227c204b9.nq.gz
    ├── 17836a5c35346fa4363d412e41966b58b32ac03b.nq.gz
    ├── 17899e582d5630a632613bdc0cd5b26f429982dc.nq.gz
    ├── 19b20b30a2fbc41467fb60fc31f06d7f82463fe2.nq.gz
    ├── 1d408a61dbc774af04b3e11fc3cc2b293aeeed46.nq.gz
    ├── 1dbb062bbd10bee9cd698516ed855b36fac4bb50.nq.gz
    ├── 1df03e2b8c56026600362d8f4d77a08e1e7727e3.nq.gz
    ├── 1f9e42b11e8dffb4cec7131267ea121e829c8003.nq.gz
    ├── 219d14d69ba80b104d1efff2fa96ab99dca1be76.nq.gz
    ├── 2212a974edff97ff2c32f51c0f95df95ccb72291.nq.gz
    ├── 23db0e0ca8682c57accf96a58ced649fdd3f34cc.nq.gz
    ├── 23fcba011321a3a2b3b94a8abb13201dbdd1faa5.nq.gz
    ├── 241afc461e85183a7bce1bdb44ee50bae1a326e1.nq.gz
    ├── 26eeace282b2934f88c7e3a19111c81758644b6c.nq.gz
    ├── 27f573b87af11e2cbbd9f54eb1ee285a58550146.nq.gz
    ├── 28c0d18c12c608d3951fec8adbdfa319705cb2f0.nq.gz
    ├── 28fa5357c354b635489ba6757c5aec19b1a14b78.nq.gz
    ├── 2939a492cac376f9d0d7ee0b34f441113ea51530.nq.gz
    ├── 298ea9e213e8c4c11f0431077510d4e325733c65.nq.gz
    ├── 2bce32e04810c5f17737088ec183563054d0c4ea.nq.gz
    ├── 2c935e648d6b9dfd73f6749cf3ba615e5acd551c.nq.gz
    ├── 2da15c22b146772e78d7f24c7f8141520bdef8ad.nq.gz
    ├── 2f2e1df19e9b129aa46de98fcff7cf54bb4999cc.nq.gz
    ├── 2ff7e2a6b3f5fd926a79e1a55871d18657ecc96a.nq.gz
    ├── 32c0970e984cc3519650139904de05678f0f1f9f.nq.gz
    ├── 32e60bd22b9fe4da34cc0ae8d4bacea550fad958.nq.gz
    ├── 340495b3182bb21cf8128e3cd138d8adfdeefb5f.nq.gz
    ├── 34ff168596368b46c1f2d0839cc694f18f815557.nq.gz
    ├── 354e740c8193cdfad54fdf3113ed4d1f6f03366e.nq.gz
    ├── 36d80fbdda989623e51c6de2ecdc67415bda3a14.nq.gz
    ├── 3a5be340933d12f02a263b108da09b32250371c5.nq.gz
    ├── 3b94c50cd3ef8fed0d20515cbfa56ff725ecf052.nq.gz
    ├── 3c07e462fcaeb8c75dc20a33e7c8c5dd57114196.nq.gz
    ├── 3e35f2d3ab2a853aab1d530ad31f8d346f9392ce.nq.gz
    ├── 3f7519832e78abc2e04bcb61187590982c7b1805.nq.gz
    ├── 40a16ce141a205668888f1bdd37c8b48f16249d8.nq.gz
    ├── 4543507298cde7707b2efcf7c82b92ba1c60250c.nq.gz
    ├── 4695aeecec3a866be45f59824369d457b964d210.nq.gz
    ├── 48bc9344a4d661e116be1483d5520753875b2bd1.nq.gz
    ├── 494cce8c547960729f5959dc53c05e2fe2e66ad8.nq.gz
    ├── 4c6dcbc02d32d5ab155d93489159cad1abb53366.nq.gz
    ├── 4cdbbbf9bd58ba4f99fb17df9b56ce5e707a3f3f.nq.gz
    ├── 4d89efe3b69d3e7d2f34a06c2a252661fc29b8dd.nq.gz
    ├── 4d8cf66070c65997792313d538004210598277f5.nq.gz
    ├── 503fb5a32ae39c020ed687f9d53e3656bf7064fa.nq.gz
    ├── 50ac588879f3d46e7bc62cb013c7a2f5e2013398.nq.gz
    ├── 52425545b01a9647466cba1e606045bb0af0ae74.nq.gz
    ├── 555a268c8dc22194e84bfac376e59badc6395f6f.nq.gz
    ├── 56bc96030c410a25fe8363064bef289bc581d9a8.nq.gz
    ├── 59311b4b96d81129f27f878da2c57db90450e55c.nq.gz
    ├── 5adab0b67f99fe1770d9606c39135bc3bf23af33.nq.gz
    ├── 5cc0758264fb894925f40a0ea8326ca4882ef976.nq.gz
    ├── 5d6525f0a4905700c589cc3aa8f66e4d777431f0.nq.gz
    ├── 5e98ee8376f6f445524d036e7d2a87e489b428d7.nq.gz
    ├── 5ea11258db543769647efeac163a558fae7718e7.nq.gz
    ├── 616c95ee207e68e0c0cc5b55fd20d83f1aa4f496.nq.gz
    ├── 64c24cca29795e636eeaeb150545349831bd7db6.nq.gz
    ├── 6766848f9201c2290d27ad4f03dd457da6b8d83e.nq.gz
    ├── 6b0c235992bd42858029a97cf48d4950a1438b9a.nq.gz
    ├── 6b214a5c09d3a2ed5399a65ba6100bdfd0b070ca.nq.gz
    ├── 6b391623c4bf023255fdbc8eceb7acf110e5fa79.nq.gz
    ├── 6ca235997963204d5b8b4ab67921a8e3b954c956.nq.gz
    ├── 6e3a03835e73b784d7ee156c8f04a4ee3eab2c35.nq.gz
    ├── 6f3a312793adc7b0a9b74f04ac7ea0149cac0f86.nq.gz
    ├── 6f83cbd8193d373b295114acac7e57da3c095205.nq.gz
    ├── 6f93d0e427ed1b7e06dc9b4d8cab2e3a275b53b8.nq.gz
    ├── 6fbefee7c2ef4be381ded62814ef2ff1bbd0803b.nq.gz
    ├── 73c3ed8aff7a9a8e58e9696a729e3f095b79aa45.nq.gz
    ├── 74f03fa5c3e2ba7636a5b6ba39c2c25eeaa92337.nq.gz
    ├── 7aac9fdb4dae8b8244ac4e74da9e41a37584ca79.nq.gz
    ├── 7ab97d33a739bddb0a315702c3ae5150c5f2ed48.nq.gz
    ├── 7b5f9f855fe9eb3666fb76109b3605ae021ccfe5.nq.gz
    ├── 7d35455c50ae883c3365af3cbdfbcf6eb9789f03.nq.gz
    ├── 7de35836366c2b06b61452f803c9295d11b24aaa.nq.gz
    ├── 7ffcb01b4ad12018624e989c81659e43706feb23.nq.gz
    ├── 80aebd7926f317bab6d07f6b7c66db54d7d149fc.nq.gz
    ├── 8635f2b9824b6caa33ec55c2451923a3d7659ccf.nq.gz
    ├── 87633ee7d971226cfb7f6dcb47e57d08ec9ca5ff.nq.gz
    ├── 887e97342b5065bf6dea9ae7d38f84c8201ac0ff.nq.gz
    ├── 888d9c207aa1fa4e00a5ec741af7d98fce4896c3.nq.gz
    ├── 88af4464953321481372ce5dab8e4fae65a6dce8.nq.gz
    ├── 8939e0dffc8578a528b154dd3fa6057f10f07487.nq.gz
    ├── 8a345158cc9833649f54b010713986d90384a80e.nq.gz
    ├── 8d0eaad250fc1ea8f3728338c1b016596cedfc60.nq.gz
    ├── 8d726b0f68187b16e4da4473e5faeda1b8034773.nq.gz
    ├── 8e92cd0482e024bd69ded966ac77613e30bd4f65.nq.gz
    ├── 8e9bd65d46ab113cc8bff767b42e2c891d1f7273.nq.gz
    ├── 9088fa8ac9b10a3dd906f4d042b527b832c706df.nq.gz
    ├── 925a4a693bdc6b49b72d221daf61c650f3c35f02.nq.gz
    ├── 93446a35e657d34d44d244258b1ddfd14d578aac.nq.gz
    ├── 9435678accb39be9f5dc22b7244ef4712cf4c69c.nq.gz
    ├── 9438c4df1ffdc0f627335cafefe107b3ad1ffeda.nq.gz
    ├── 94b082976667c0c9edf2e9ff7a668c1fd7d997bf.nq.gz
    ├── 95cffb35b9e2ee1e03e4a4be63eaaa83c15d97a0.nq.gz
    ├── 9759384aa72c4e4a80362a046b3e71d496e15651.nq.gz
    ├── 975f80675b627d0ea0a15a169e2ec92263791853.nq.gz
    ├── 9945eadb95405febd68ab36736087bb42bcb8973.nq.gz
    ├── 9a38dba4b8dc55e15cec718e0420401d97755c28.nq.gz
    ├── 9b9ee1f185a57591f0ce6ce8d10fd60f5522f25a.nq.gz
    ├── 9beea40703d7193d501185108077ac0e07a502c8.nq.gz
    ├── 9caa00a4fb1613f56b92406e2f635f4002ca9c99.nq.gz
    ├── 9cabaf5238d62b16f3ff3c1fd828130815f33324.nq.gz
    ├── 9d26b7c6b7ed82099e67086799117783ba564fc0.nq.gz
    ├── a38cf841a69cfde8efd5489be3a3ff4de1ceef11.nq.gz
    ├── a486bc5e1e5a9d6eff98654ad75e0e84fcebf1ed.nq.gz
    ├── a56246f73912621f2b1cc6003732fc219243dd5b.nq.gz
    ├── a6210d3d8a7988fdee6556eeba665d6b58ee6db4.nq.gz
    ├── a6ba192a5ef3681869d4672e9f5756f36879f6da.nq.gz
    ├── a968a0faa56592427fc005eda086e7e09e30140c.nq.gz
    ├── a9d307ba75e2b31bf59c5ce280e1c1ae9c4e7ead.nq.gz
    ├── aa8eda2821e10bfd92fc702cc65ab3a5f115c90a.nq.gz
    ├── aa9d3b4610f4fbfa09261faca066eeca0ae399cd.nq.gz
    ├── ab962081737920f3621251a1e743ea839e6489b5.nq.gz
    ├── ae70ab075c232f8b55b0e6299c0d24ab50e4a0f6.nq.gz
    ├── ae7c90613299085b7e304589f2b54bbdeaeca347.nq.gz
    ├── b118f26e226ddb3ed9e315c030516e72203618af.nq.gz
    ├── b2058f807309707c3387a949da18e858db5d03b2.nq.gz
    ├── b342245e9e2d900eff44c741a923a865faf1ad23.nq.gz
    ├── b35a8011c3779f2c0606f07d9dcccbd12104064c.nq.gz
    ├── b5661d2723867ec071dc0d253afed621ed02ef39.nq.gz
    ├── b7d9748e7344f93a2a6c0d7ff06ad813e9d847de.nq.gz
    ├── b889a2c20ecee69aa3ee429c99ec1f7f989f4b2a.nq.gz
    ├── b8a339a3347e1d94f8663b5baa7e7597b86908d1.nq.gz
    ├── b8cc579f47662c52bc671272e8954a4fffd2bb29.nq.gz
    ├── b96f99a3913f8f21e93426200458e7adaa38838b.nq.gz
    ├── bbe953dd45c6061950dfd5401e225c8ce7af1f16.nq.gz
    ├── bfe2d5090eb633d21dd1a68618aca6fac96da24e.nq.gz
    ├── c1396baef8f27ef193e7cb2ba6eedb2bb12e9bf6.nq.gz
    ├── c2991174176105720529d221d643643c995fdb5a.nq.gz
    ├── c3087f05403be8b555ab8f83bec86c33edeb6298.nq.gz
    ├── c60eeffa08343d4d2dd7f6dfecf2101eb053bf77.nq.gz
    ├── c6b26f88f6c3c1a052afa6314ba2adf832d785ee.nq.gz
    ├── c6ce1ef44cfdeb54a30fca8a81d56db34d492846.nq.gz
    ├── c856520e771a1ab896c61ebd3add1fe4670f4ced.nq.gz
    ├── ca4b42cc8bcbd53b9b15685aae9ad8d9cadfbd2d.nq.gz
    ├── cf742d0589cde4eafe0be1da46c4371b560dc2c4.nq.gz
    ├── cf769e8145bec8d4cfde982945b2909fce1d679a.nq.gz
    ├── d0741bde6f16cc449d34f76c74d5f6929f05f389.nq.gz
    ├── d0a12d29a619ca127038ea5cab46172235c2f1c2.nq.gz
    ├── d0facc31f9a33db5e26f2d634ff6c18f34b6d691.nq.gz
    ├── d16696e91d79b46afcb79dcc631145c2f43bb22b.nq.gz
    ├── d291a901252fe92da130dab801f07d84aa905828.nq.gz
    ├── d2f169cee0f528113eb5eb9cd2d358af81efd991.nq.gz
    ├── d4a251e2a3f92224de72cdfd494102f8a729e939.nq.gz
    ├── d64bf839c39f8385b1c5b1911f97d24fb1f098fa.nq.gz
    ├── d6bb2d8faca607fbfd8c9b4195f4c54f5945a220.nq.gz
    ├── d7ca641eac0c0789b4ea6cd228776a16b0ae5667.nq.gz
    ├── dbf3f2dc51c575c947f3151b5f6a92c1780dce22.nq.gz
    ├── dde445e64194489be6057f9028903cd852b9a6c3.nq.gz
    ├── def047e33e621953a1ed328ec505b1a39848f08d.nq.gz
    ├── e0ec184df8abd3dfa0037fc6141401faa5e36212.nq.gz
    ├── e168c531f53028bff691b259006c357490926668.nq.gz
    ├── e38a86dbf02e13c59fb7725890c792b80955e868.nq.gz
    ├── e445e623ff661bd0e604a82135a370b5d930ef02.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e700dbaeca7ae122bf24a09e8ce48901e3228b7f.nq.gz
    ├── e75c64f3593621c23589f19f641119d20f6f50f9.nq.gz
    ├── e774ddfe649edd852308cf7ea04a3037179b0702.nq.gz
    ├── e82394ef3439d90a3c05217df5be97d57b41e54c.nq.gz
    ├── eaebc098eadf4fe3cd18e23112611261f208722f.nq.gz
    ├── eb7bd72030fee503bcbcce71454e36e4d9dba3bf.nq.gz
    ├── ec298b53740270ce82b326c4c2deaa5dcdec4596.nq.gz
    ├── ecd4c48ba0a5a47ed07facbd22ab034c861fee09.nq.gz
    ├── ed61795f0fe309ab8d86d5b199527a0f4552f73f.nq.gz
    ├── ef7e16fdafe243ab5e368763bd4cda18c5872c1f.nq.gz
    ├── ef9265660fa7b4a78c3959c1e8d303ed056730aa.nq.gz
    ├── effa6365913466d4292cd7b29f37b13d3b6eb68d.nq.gz
    ├── f039187e38b7d677f635170d5ef3e000b78171d2.nq.gz
    ├── f30a780c88f4f5214089e9e5dea5f10c76889d11.nq.gz
    ├── f38315b22a4929c146aebfb5f2671bb16c003fd7.nq.gz
    ├── f3f6da87e93290f0e700f1c94c55aa825024be4f.nq.gz
    ├── f4be124b1665e2f90e347f2ec50d6ea265af3b23.nq.gz
    ├── f54a540f5c86a5b2b95846f78ca3608b0d4559b7.nq.gz
    ├── f7727026b7068d7ae16301ef08513ea14e050cc6.nq.gz
    ├── f99ecf2254e9ff5c690245eb93fdadc01136aa5a.nq.gz
    ├── fa04b52a3bf868bd57e7ba796d64385a51e7ec5a.nq.gz
    ├── fb01d86089a011ccacd50be4187f223630577b12.nq.gz
    ├── fb7dd0ef436d52972af890c3a0cd518cdd8b5b51.nq.gz
    ├── fb873d3a5d6db6f4085c40a659e7c93923b63f18.nq.gz
    ├── fbcff86c15231e3eeed4bce8d68249a1c3028ea5.nq.gz
    ├── fbd1dcd3a020e05a61fc3e6366a3dce6e0d7068b.nq.gz
    └── fd28cb17d0309b255d0e3ea65fcbcfa0e7aa4e52.nq.gz

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

[spacetelescope/spherical_geometry](https://github.com/spacetelescope/spherical_geometry)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
