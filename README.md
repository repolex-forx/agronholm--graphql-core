# Repolex Knowledge Graph of agronholm/graphql-core

RDF knowledge graph data for [agronholm/graphql-core](https://github.com/agronholm/graphql-core), parsed by [repolex](https://repolex.ai).

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
rlex download agronholm/graphql-core
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── fa8f9b509d557341c033ef6d05884e2683cc7ed9
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── fa8f9b509d557341c033ef6d05884e2683cc7ed9
│           └── chunk-001.nq.gz
└── blob
    ├── 008836040e67498bc65f41ca02274e31b775bfd1.nq.gz
    ├── 0121db2302da65cbd98acce47c01793b9907fd21.nq.gz
    ├── 0159715d8e48bce92bcf4ad77980cc9fcc0e9e1a.nq.gz
    ├── 01f7e46415e3b5f52761fd9f79d6f9b666782452.nq.gz
    ├── 023fc2b27f37b579e19d658a2092f52e475be83a.nq.gz
    ├── 03015cd03c5b96c93f658b11f1542f5fe7363b33.nq.gz
    ├── 03af63355ffd0c21c7d8268786a3d5276cdbfc8e.nq.gz
    ├── 03b85dcfac3d9413bff5e11b514ba55622784f2c.nq.gz
    ├── 03f1ddc8acd661c66b69237835e3238e0817268e.nq.gz
    ├── 03fbbcbbd7bb3bd1524184bf3dc1562c3750e09b.nq.gz
    ├── 049fd7b32558966f7289c662c2300c484f5cfe91.nq.gz
    ├── 055b4231365c9ac1969c52b8263b6844ee80d53b.nq.gz
    ├── 05ef249aae5b1be2cfc359e304f66fcdc1de1c9d.nq.gz
    ├── 0689dbd4aa05c820d5c25321f9976771bb45adfb.nq.gz
    ├── 083c437ccca1c3388f61481037fbe7e161eddb48.nq.gz
    ├── 083dcd0f598c2059648b29957fd66338c513b399.nq.gz
    ├── 09567645460f4b193a48a9f22502796cb2b1a18b.nq.gz
    ├── 0997f14094f6333d10dd628330dcc53a56d8ad4b.nq.gz
    ├── 0ac606c84c30920e8c3d7f499a8b180923f31c0f.nq.gz
    ├── 0c2ae34837df5899e9a3de65596a5c2ccb56ba32.nq.gz
    ├── 0cadce37c32dd4a735b627bebd5f1b94300fa908.nq.gz
    ├── 0cb2b5b9f602d9267aee0116d947000b3fe970cf.nq.gz
    ├── 0cffd533551efb7e6a55f70e71585f77f138babd.nq.gz
    ├── 0e17b4d4d1fe4ea1444b1664b8c4610f21bab2a8.nq.gz
    ├── 0e2cbd0e22e0df58bdfff2fd7472c3015c3e7642.nq.gz
    ├── 0e9607a98f248172ea09bca1d556237af040937f.nq.gz
    ├── 0ef5e5487c50310eb8e833ef0f2af1275cc9ced7.nq.gz
    ├── 0f5f35b297d6c23b65192cf6476d52d8fa836c23.nq.gz
    ├── 10acd68fcf12398fb1d8f04f0b33ecf8ee7caf5d.nq.gz
    ├── 10b6b3dfccf0d98915eb7bbad78b5fd4cbe4fcd3.nq.gz
    ├── 10e2c69e15f24fe12ed36209ddb157701e41d8fc.nq.gz
    ├── 10f13c159e3cb7fee36b8c0ade689d653d5806a8.nq.gz
    ├── 10fc411d6b76053649b0eb11152656aa108d0d15.nq.gz
    ├── 11748a474ff06c7bf0c14cff3a7136cf552ecf90.nq.gz
    ├── 11af8aff9593dd10e8db57761ede332583fdf9b0.nq.gz
    ├── 1210795ad5164434f3be714bf9fabb8565223c47.nq.gz
    ├── 124aa6e68a9198ce4cf1ced19068bf793bfcc962.nq.gz
    ├── 1455f4736f0323e0176351c8cdde7abe90510155.nq.gz
    ├── 147ccca9fbb933d69f8665c0543fa38070af895c.nq.gz
    ├── 158bcd40b92dcf72fd239f644d1386d497fe6e6d.nq.gz
    ├── 158bf93739aeba6e7b6037264c6d57510405cef6.nq.gz
    ├── 16d66bbccfc09869566f5f8ebdcf77af1d92d9f5.nq.gz
    ├── 17d5e15d2c0b7be6e5be0b56c65489fb56e25471.nq.gz
    ├── 1a13936b64ecd6a4eb7688a5aa448c711feccbef.nq.gz
    ├── 1a52f7a25ce6e6fd007fb0d732f426f8fbe6fdf5.nq.gz
    ├── 1a8f768905e3bd70740e00af8a893f085fef521b.nq.gz
    ├── 1a8fd2e2b15cb995039ba7884b0b4c1db6f082f2.nq.gz
    ├── 1b0fabbd89e719dc3fbb9a3d9e709c5d3a1c51c5.nq.gz
    ├── 1c8ad24c6be0871fe064cb4b1c796d1e9a5baf34.nq.gz
    ├── 1c9dbd5265a4b52e4e1f13a34168be2b435a0587.nq.gz
    ├── 1cb9dc58749097aa93549add9180218eaa349782.nq.gz
    ├── 1df28d83c2595c7704012d9ecf10be08272abbb4.nq.gz
    ├── 1eb98d388919d31c6097de0fdd87cbbf265f9aae.nq.gz
    ├── 1f9bd1638eacac0d5969aa1a9f31ed8e1cadffc8.nq.gz
    ├── 1faa946c4598768d17af5dedbbeba99e5dd41dcc.nq.gz
    ├── 1fcfa25c60b24c9f4a90c948a9df791c18d10fac.nq.gz
    ├── 1ff03b8f2996b92c2966f8f3657d8abf67993a2f.nq.gz
    ├── 2040b1a7dc38ec7f26cbaebe939e9666f9e5d8c6.nq.gz
    ├── 20f5a7c54fb228c35d4e73636903f940efc6c520.nq.gz
    ├── 20f8b5f43691c5afb8e89e0e9a227194c0216f84.nq.gz
    ├── 211445245ab8ff522766ea57746fb27064196a6f.nq.gz
    ├── 216ba3c5aaaf37937aff0030c23143afa9b2a336.nq.gz
    ├── 21fb1b8ab2d8e2a6cbb3def2147c0f988ef44720.nq.gz
    ├── 2274e750245bfd4227cfd24b1967c2ee58077e71.nq.gz
    ├── 2323e57f4221d00bc05b4327a495e6b594903ca7.nq.gz
    ├── 23c157e2dbd8240d496829b0fd1206773601d2cb.nq.gz
    ├── 248927b4ddb5e9f3cf9b9d630477057571c630fa.nq.gz
    ├── 24d8066fc6ab13ecda9029cc2ea74bddb6b9d7ca.nq.gz
    ├── 24ffc55d460fae364d7b370146fbe095a4a3e65c.nq.gz
    ├── 26ccfea2457d6f80b8d8dd5afd1d595199f1a5ee.nq.gz
    ├── 280662f851ba037839b7cb3598bf37425c49a5a7.nq.gz
    ├── 28e78653252b9c086c4859189b616adb9f8d02b8.nq.gz
    ├── 2ea665e4dc9f89a9a41ebf3b3598507495b497e6.nq.gz
    ├── 306984b79bfdb533c00afd6a358b07341114e3d6.nq.gz
    ├── 313c3679b7b234612ccc9694265be55b12181253.nq.gz
    ├── 31e423bcc9f0783ef1c4f0f5bbfcbf70e29dd178.nq.gz
    ├── 348d2cbf4f47e19fdc679f4a4a00d13960f30429.nq.gz
    ├── 35240c77778535dbebaacb6f6e938723f1bff7ae.nq.gz
    ├── 354cfe74bbaa2c0bc10bdaacedeb1b9fbfc4e458.nq.gz
    ├── 368e7ae01453f49910b794d84d95adf8cf142740.nq.gz
    ├── 36ac493baebabec315cb1e98853369dd524eac3f.nq.gz
    ├── 37370c9d3390254204a79af55b0c76b1c070a3b0.nq.gz
    ├── 375ec40032b13167a1f0378f9ea777497088a9ce.nq.gz
    ├── 37b95f9be322224dd30811d13b29fd2ea50b6c1c.nq.gz
    ├── 37dca7412848f2e46822d503ca13d478887d2110.nq.gz
    ├── 399cdcb4883d1fa5b9ca02e231367fa3e036ada8.nq.gz
    ├── 399eee06e0ebf1b2f86427f78fa83850184cbaa7.nq.gz
    ├── 39aad3ed967db0e25ef869ae679fd1f1e291d696.nq.gz
    ├── 39df72031fc771167736ee3d90b677d218294a84.nq.gz
    ├── 3ba13e0cec6cbbfd462e9ebf529dd2093148cd69.nq.gz
    ├── 3bc60a0ab54eb891a48439d26aa330d0058d84b3.nq.gz
    ├── 3c3cba60d7c3ee6dad2ca346e9432ada9e0dd620.nq.gz
    ├── 3d2fe46ff4d01af0f0aa0663400d09db1eb6616b.nq.gz
    ├── 3dfdb3ed9efbd7d98f727c95d770949950ff4ee4.nq.gz
    ├── 3e60fbcb16a59577499a87b46f3ccfd1b27c6d39.nq.gz
    ├── 3e88d3b8c2d092b1d7b4fb0aafadd2a4b2f14f06.nq.gz
    ├── 3ec027bb271fffc50b37bbaa4f6704357c7beaad.nq.gz
    ├── 4142e203cf2b6508124b96a30972d4db166ba35e.nq.gz
    ├── 425310965b3b8cfb178d75e6274c64925de24a46.nq.gz
    ├── 4257d81f2beb95955127f976a2678f83b1ba1345.nq.gz
    ├── 437401782b48eca8c885a55c107b07dcefb3fac8.nq.gz
    ├── 46b3497dc250917a7e8feaf609aa800793a2f26b.nq.gz
    ├── 473e0c881cd3ea67cf86f9a12017952b52600baa.nq.gz
    ├── 49dad199be0ceabda18c75d3d111d0651a5f02b7.nq.gz
    ├── 4a21c63b65e4397cb38e995fa01b69400852109f.nq.gz
    ├── 4b211e27e5efe2d020954eca5521a1dcab7165ab.nq.gz
    ├── 4c088d93a979f4b7e8d576ecf6561a338f0532c9.nq.gz
    ├── 4c21842caefedb4bafa3c4f393fb9eef9a15d86e.nq.gz
    ├── 4c276e07fc9285388c654e779a5bd83976b570d4.nq.gz
    ├── 4c30d96596b4f7557e4a86de0095f55a0d01251a.nq.gz
    ├── 4d7645626c177c2e495712f6e54b77d312095b19.nq.gz
    ├── 4e7a85a2d5e9230ac9f1fa2062624076ca6ad3de.nq.gz
    ├── 4e9199f33c1ff2fa43174c6846a0c04ecdf89466.nq.gz
    ├── 4eb79748c37b0c19f674b6cda883264d6af1a75e.nq.gz
    ├── 4fe3f9985956157830a51ab5b25bdd36c00c32df.nq.gz
    ├── 5012202625ed555651c74d5676ed0c0171928baf.nq.gz
    ├── 501599951b265fcd6fb9249fc062ed2e070f4809.nq.gz
    ├── 528e3df3ed16b0e18d140ea4f71721ed07455c65.nq.gz
    ├── 52e9b679d2bac5e8831b7d6ff1612020e37178db.nq.gz
    ├── 5309996afba97a19dfc1c7b160255fb23de04f2e.nq.gz
    ├── 552fe91b02dbe48ef928e8bfe86a07d8e8ea6635.nq.gz
    ├── 5611b45c1375a6fd67fcd4dc780e0fb96e164faa.nq.gz
    ├── 5763f16e8071379e0341e67f7b0de04ee12b7932.nq.gz
    ├── 57ebf703aa9fd3fe42a195b89ada4e45b8320be9.nq.gz
    ├── 581528cc81abd44299eef86689fe25c1c2115239.nq.gz
    ├── 5882e5c53c5881dd9fb943336e35b67823628c02.nq.gz
    ├── 59299a1de2a747d77ceddc07f6eecf2113eba26c.nq.gz
    ├── 5aadcc31354571587f61dd867d7c6a6899aa95ee.nq.gz
    ├── 5af7f5aa829aa131d1530573024584053105d56f.nq.gz
    ├── 5b9b5b8ca5aecec13a5b5ac3c00bda58cd367c7a.nq.gz
    ├── 5c20d64788e9f712e2c70d6efdbbb9ddffbb2091.nq.gz
    ├── 5d7b83d13a5a644fedc162674d4d88c1ed40839d.nq.gz
    ├── 5d87057680ebf1f371ba7686451f5b24f117f37c.nq.gz
    ├── 5dbac00b0581f7e4f846d62c314a86c76e09d2e6.nq.gz
    ├── 5e4058f95a85f103d00a3b75704a24b04b7d4ada.nq.gz
    ├── 5e9b1c216b0d434141ffcac293354321e6a68d37.nq.gz
    ├── 5ebbc1b33cc20bd84d6a4cceed4b945101fdced9.nq.gz
    ├── 5ec97db1af5961d396315c6bf4fc0a350ba64135.nq.gz
    ├── 5f4c0809f8fea13e28d995cf3fb4828b36eaef1b.nq.gz
    ├── 609c19b6f8891e3d8f0f210c9906049e225208e5.nq.gz
    ├── 60c77b30dfdc2503718d8ff98fdf1418c8ad2c00.nq.gz
    ├── 63bcb3a5ff9abfbd99e4bfbf26b7307286045b05.nq.gz
    ├── 643300d04ce5e85dd3f89c3d20f8ae96acea37db.nq.gz
    ├── 64aa2b952dad40f871eaf62fe845e612d73887c9.nq.gz
    ├── 65169b399272b2baa04ad61e45d8529aa84b9111.nq.gz
    ├── 6622b4dcbcabea61373de656b6c6306a032bdfe8.nq.gz
    ├── 66a71fb301b1fb4929bba615639edc4a79ab666b.nq.gz
    ├── 685389e6700490c900b1f65fc6d9ae3cea50449a.nq.gz
    ├── 6938435ad788111d38a3c2b5d3fe6dcc12797377.nq.gz
    ├── 69c62c181b5362bf9ac8ef10bd86cbad7a59d2af.nq.gz
    ├── 6b688133ec82721f23c98fc3fc58d77ce44fa471.nq.gz
    ├── 6c4c33db8b9fd748110fb6563bab7ff5a427d5d8.nq.gz
    ├── 6c98eb67f93fb7a4aa2f664fbb44b6d2fabc9b7b.nq.gz
    ├── 6ca01a9d2b46e4e6747221e0c7b529d6642700e5.nq.gz
    ├── 6d2d8429fa6cdcb8c6e334e8701d4575ade111ca.nq.gz
    ├── 6d99917155b677106cd8cbc591a64a92a8f31c97.nq.gz
    ├── 6de707bc6c80e906f50f506c377df99ea1425e84.nq.gz
    ├── 7020765033a8b4be246421b8cf8c1a6bb9a2b704.nq.gz
    ├── 703a56aace56cb33a0f16059be8ab26ed0fb9024.nq.gz
    ├── 70849608fcac6450a8346e9d2a33d58cf468cccb.nq.gz
    ├── 7096c5fb49ae4222e4178aba6b9acaca5302217e.nq.gz
    ├── 70de87293b565945817e51b468691218247f3c08.nq.gz
    ├── 731c021d7e021f1edcf79ae2df465ab7f6fa692b.nq.gz
    ├── 7348db9befc870ca544c0b555345d5ce88e1b121.nq.gz
    ├── 7352a87fa38804531b2cddba2e8bde1e9b3766b8.nq.gz
    ├── 7366ba55fa3ab9d0c0c3594c63fa1d9b4f0d85d2.nq.gz
    ├── 737fb2df57d804cd460a592904683a7dfe7885ee.nq.gz
    ├── 73a51c78595a8121f4cc6441a6f8b27e8817060a.nq.gz
    ├── 74099ca65199660f7567479a28111d6fff03d65c.nq.gz
    ├── 7509676c4be0e2d6e5bb328b218855a91038b41e.nq.gz
    ├── 76b359a9bcb29ca4d94b9167467f85e842b2c64d.nq.gz
    ├── 782f6c70c845c7a44bba5b56cbea6c5bc5228fd7.nq.gz
    ├── 78efbce9c248c0380827508fd5dbc73a320bb5b1.nq.gz
    ├── 791edfc157068ba3d6a33d0d7578a4985d903dc0.nq.gz
    ├── 7ae78ea9c9da6635adf58ad3acd8cdd70f161c8b.nq.gz
    ├── 7cf2064819dbaca7ab23ecfd3cbcd733a7ebff60.nq.gz
    ├── 7d48fc4298664b0a00f90117540f525ecf577665.nq.gz
    ├── 7db8ef2fdad5debfaedc820b1f273e4726c7c338.nq.gz
    ├── 7f7dee8f065b6552bae9da6f8304ae20f77c4974.nq.gz
    ├── 8059154f8a57a95429d14abb1ce19e732bcd8794.nq.gz
    ├── 806292f9fa2cd29b35b333dfe39d3e8d2d7975b5.nq.gz
    ├── 81102c2d2d4c9835ce178b8710261804207126e7.nq.gz
    ├── 8123a713cab6092e2fab20a40129eaae966000c3.nq.gz
    ├── 82b238550a5741f1610a6f6bfa53a09285dc0ecc.nq.gz
    ├── 82c611f6e80812dc705138c7f0eb113e2f2b6e1d.nq.gz
    ├── 83142faeffcd942d6b24260a3ef5804d3b73cabf.nq.gz
    ├── 83e431bf4ede0d736be6dabf5e9f5bc43a8e88de.nq.gz
    ├── 8446dd065b16df670c3c88b1c101441bb88bad57.nq.gz
    ├── 857118da4d9b50961d05fb7fcc784718abefdad2.nq.gz
    ├── 8745f67eab64f0330f0d2e44891b6bec2c282603.nq.gz
    ├── 8a9b864b4ca19f1179696a845c198de25acfc366.nq.gz
    ├── 8b82734f4129a28be941e1fe1ade9e143a105ea1.nq.gz
    ├── 8bd8c296c1a80d840f047bbbed9d3de6b0a59a94.nq.gz
    ├── 8c41bd28f840e86fc6a3198ebf5b489abeb8e3d9.nq.gz
    ├── 8daa2e27e13228559904adcf3b28909a56f4447e.nq.gz
    ├── 8e59821cfc89ffd5feba99c07eb38041faf59148.nq.gz
    ├── 8e633faefb73a441768e02f85603ca8d693a8c06.nq.gz
    └── 8fef324c4869aefe82d3f598c09a97c6a92ec563.nq.gz

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

[agronholm/graphql-core](https://github.com/agronholm/graphql-core)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
