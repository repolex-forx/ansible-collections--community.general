# Repolex Knowledge Graph of ansible-collections/community.general

RDF knowledge graph data for [ansible-collections/community.general](https://github.com/ansible-collections/community.general), parsed by [repolex](https://repolex.ai).

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
rlex download ansible-collections/community.general
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b405909e51bb5d28fce99a075e420ed17c51b83d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b405909e51bb5d28fce99a075e420ed17c51b83d
│           └── chunk-001.nq.gz
└── blob
    ├── 015052275736f3cfde21d7ecab588dc854848e53.nq.gz
    ├── 018406720720e5216dfc721c8999cfc5fa7652b6.nq.gz
    ├── 01863abe33513ef84b6c4372d950816a216edb0c.nq.gz
    ├── 01b8719fc5536d23e180a54c80025d0f45564f7f.nq.gz
    ├── 035bfedfe432b3373a52f3798e93203593f9db18.nq.gz
    ├── 03f0807fcf5ee6fbaacbe92057d28f3764db8541.nq.gz
    ├── 03fef66e66f0738f02c2f81ee8c6e0c1bf436a66.nq.gz
    ├── 04674df067230c9bc10a260ba346335eaf5b767f.nq.gz
    ├── 046d150e226a57dcb6b454a26282662d8a62feee.nq.gz
    ├── 04906f66aa897ab47487e63d5731fd07c282dbd9.nq.gz
    ├── 05ff166b4cbe5e623895e7c7c192a56301b4e872.nq.gz
    ├── 0641fc5776382c0b2ae561d328f3530336877dd8.nq.gz
    ├── 065bf0f041b94d9fa7208eec5f5392ac02227f20.nq.gz
    ├── 065c777b9c6801cc8f90715e07b476ed22b2b749.nq.gz
    ├── 06c6786ee6b602390a174cee7d4d237e79e0efc0.nq.gz
    ├── 092ad4b61f9889dc7094440722ac60c55482cd18.nq.gz
    ├── 0a85a8d669b1f396c4a84864383ddc1e14af37dd.nq.gz
    ├── 0afed43adbdee64ba7d841f8d73fef3310fea1da.nq.gz
    ├── 0b05eaac03249ca0788934429e12c991e2b1f457.nq.gz
    ├── 0b06951496610904501c7b1be970d637afb44baf.nq.gz
    ├── 0b80bc07002021f02c2ae239d2acc13d557cb2fa.nq.gz
    ├── 0bcea2d9d886070f1d026942a80ee128546f3a71.nq.gz
    ├── 0bd45f4108aeccf3c0b8c8f2fd2e9433e3a50b76.nq.gz
    ├── 0c5875908a623af41fb0bf3a953bca87e2b2732f.nq.gz
    ├── 0d9365ff598e868d4d242e00de5b94aedfe942ed.nq.gz
    ├── 0d951a0cc4d0a82164e8fa55aac0bb281698f617.nq.gz
    ├── 0e2eb4cb91dce95c5807bab4c8038fa4bc0c2ccf.nq.gz
    ├── 0f4c5a0ec69d6c2990d2341e915278b1595d4a43.nq.gz
    ├── 0f95e1aff3cce2fa86309f57a3a0dd8596aad3ab.nq.gz
    ├── 0fb4b462812d68a0c25d16cb916387e3cc47d6ae.nq.gz
    ├── 112e85964b08161fe3dc388e401d9b411c0e4f7a.nq.gz
    ├── 114d45d2daf1d3f691047af5afdff997d1afcbc4.nq.gz
    ├── 11f2d550c9aaf43a894de4e64900634ebf86344c.nq.gz
    ├── 122f18652bba357fbfafb0168d4e0c1597b18930.nq.gz
    ├── 127007288f4880fce285416fb57c0db6e192d6be.nq.gz
    ├── 12d1d6617eba1699f5620c5c20cd776964b16c70.nq.gz
    ├── 12de2c39097688a212625c630ccc68967bb20ba2.nq.gz
    ├── 13f1b8a8d499183041b4b1b457b44366c7dab24f.nq.gz
    ├── 13f24f44961e3f7b21e1157023d5c57d9463bec6.nq.gz
    ├── 1407cede6a8c565dfb5f2821b770d2f4614fe45a.nq.gz
    ├── 1552e98a4ef1380ce0657350a55bf1b8ee4e5e05.nq.gz
    ├── 15ebff63f886c0df03c100b45f2e0e7d1558a889.nq.gz
    ├── 16254343146924c201bb0ef7f55bfb0543f99478.nq.gz
    ├── 164d05f199393259218d56c0f44cc4750436ccce.nq.gz
    ├── 169254ea17b5d58f316af1a9afc030e0d87ea762.nq.gz
    ├── 16be434698880239669a132a051a61accf0bb6fa.nq.gz
    ├── 1728122ac9b486df8a5ed7629469c3021a757f0e.nq.gz
    ├── 18a153f794df076ab4b439c3e3af2359cda3566f.nq.gz
    ├── 18f08c9ab3dcb8b77fc0ab50bcd7812fbc497783.nq.gz
    ├── 1aa413c81f0d215b1f2038deb3da56bd35077190.nq.gz
    ├── 1b5099fd1aad1aa44de86a3b37b583aedf4c826c.nq.gz
    ├── 1bb6a1cb3cc9c729ba6df1ed5d043a2afa7a662d.nq.gz
    ├── 1c470f999843a3cbdc1648fb7e0ae0457285055e.nq.gz
    ├── 1c6c02311667c44328b2a30f4496c900aeab9573.nq.gz
    ├── 1e5000280970a7a60d00ac3b8f92cd7d4f15c9b7.nq.gz
    ├── 1e735070727fe349c05c17b4f1485765505618a4.nq.gz
    ├── 1e74e4fc4737770f498ea3b00768a4d1c9b822cc.nq.gz
    ├── 1eac40737578a6b77c164a25c33a36aa70dab7b7.nq.gz
    ├── 1facb67eaf25e6ca85c205bcbdc9316888eaf6b8.nq.gz
    ├── 1fb4d663e1f236942b1aa70ffe6256bdf54fdb66.nq.gz
    ├── 20415ffcd735c4b0476138fe9e266abae32c239d.nq.gz
    ├── 206adebc3af1f29028cf088dc6b83abb76aacf84.nq.gz
    ├── 21698f0f2853cc097633429de8912374079cabc3.nq.gz
    ├── 217651c8782c1bc089ca12e6b9885977dca04091.nq.gz
    ├── 220d06ad546ef6a70e5f3e62ec500c14076b1122.nq.gz
    ├── 2243e0dba80003bdc7e3e80b992ed37457371fd9.nq.gz
    ├── 234c9c457713d1fe36f14d4b8e24f8cacb901d7f.nq.gz
    ├── 2461f0f91985179d9957aac3f6cd20553b6298fc.nq.gz
    ├── 2633c33a4e5a770b57c611a8995a1c12790d9d5c.nq.gz
    ├── 265d986ff48ec246f47f08cbdb663615efc862f2.nq.gz
    ├── 265f657fe1cf4b3dbdaa4c5fe427b1bd03e02b53.nq.gz
    ├── 2674e0bfc4c76c300e5e3af6235502c951e3b6e1.nq.gz
    ├── 276ace749471bf0985a7038060de8a1ae5a6768a.nq.gz
    ├── 28281cffb4a05778cc761b1de32ef5eb859aa3dc.nq.gz
    ├── 28b5bce5b3ced79e83f2ff10d52b61e4fa71af20.nq.gz
    ├── 28da08289841fc4bdc141e2b7bde5df48772965d.nq.gz
    ├── 29224f414ae735f93fdcf9a79a442977ebeb1436.nq.gz
    ├── 293d34520e6f3d51cc4d5526d5b2556f4f1263d0.nq.gz
    ├── 297d2641c52d5660dcdd1606c363d5be533e7328.nq.gz
    ├── 29c6d5d15e5363ac68cd55539b5c52ae439991b7.nq.gz
    ├── 2a0da1df6c87429b8d5363a292777885bcb32ef0.nq.gz
    ├── 2a73a2b777c1608af8a2176639a3fe54a0b3fda0.nq.gz
    ├── 2b20d4fc3abd4af3db722f469e2c4c9f9a1dc186.nq.gz
    ├── 2c6056420529ecab4e47f3d573326e98fd6c35a5.nq.gz
    ├── 2c838b8b6eb23bf6c563d3c066dc4c84038f884e.nq.gz
    ├── 2ee1a0b9ab7eba136196711894efd9f4c59ccb6d.nq.gz
    ├── 2f2fd11fa0b77342d7b4a75c290f9fa354d1711a.nq.gz
    ├── 2f91e7ae9aa374b11e7d7e685b605a1c9703847f.nq.gz
    ├── 2fcd152f95cb8146ef0d4c0a1c9f97751b464c2a.nq.gz
    ├── 301529f9bd2645f5f010c3e3ed14353c5427f831.nq.gz
    ├── 30742dbe29806b378266be6343a21fcc3b4e1e77.nq.gz
    ├── 316b36eacef4199c16fdb571603536cfee168b7f.nq.gz
    ├── 31cee39a67207159164d723ce92d90628b619615.nq.gz
    ├── 32276adb8277c5bea7bc9e7dc11a8fe927518b7e.nq.gz
    ├── 3231e55e5c4d6a8a29bc89d7a8f3a9994ff2f875.nq.gz
    ├── 324883a7842254ddde5a8ad7b928820f3d47b145.nq.gz
    ├── 326a499c3e3c56d5c9dfb63477b46aa79e4bb70c.nq.gz
    ├── 33855521a00d44ce23d1801de97f1939dfc7867b.nq.gz
    ├── 343f119da8eadc44708843144766e68ed09a390d.nq.gz
    ├── 358a26d07ef9e3d4d587c88cf632c2dd0d57deb6.nq.gz
    ├── 35c79500ced548c421c79e195f00c06a81b2c522.nq.gz
    ├── 3628b3709aedec3f1d1f1de8d565f09932638d91.nq.gz
    ├── 36e90346348d26031624d3f796696772c68e3fe2.nq.gz
    ├── 3767a6e80174f3a973b344897b5ac8bc2ba99413.nq.gz
    ├── 37f965b282355c4ec603182788097044d2d3dd3b.nq.gz
    ├── 385a3e97c1394417ce205089cbc665aa92d6ea74.nq.gz
    ├── 393eddcb3afeccde7972fc65221d9da3ddcad2f3.nq.gz
    ├── 39cc8b62a33874647afb0ed0ffc8a8021cf3f577.nq.gz
    ├── 3a54a9e13c39197ec5d956205d700b03043354f2.nq.gz
    ├── 3ae04decfa7effc26e1e1f37cd47c2f146be7e0e.nq.gz
    ├── 3b4f19810878853526f23b5dae4ee9f8b234e014.nq.gz
    ├── 3b8c3bdbb4a264108513ee615b990aec68409941.nq.gz
    ├── 3c268746da58cb83a77e6d0d8eed61dde7b8666c.nq.gz
    ├── 3c37366ca6b688466883e8a863e5c16e540e1e0a.nq.gz
    ├── 3c8c6f3222a55c77a133c4794293255e1d2f4935.nq.gz
    ├── 3ca9b099ff215c2fc1e9963ae60b2ed725065810.nq.gz
    ├── 3d1b398ff17561057d5fbf5365586e6abe6d1663.nq.gz
    ├── 3e1584ac84248f9834647f54eb0ab5ed3ca82e3b.nq.gz
    ├── 3e2dd244c18fbb5942bd7ebb89111886d78fce0e.nq.gz
    ├── 3e60e96979c9d8fc6a90502dabee804361447e36.nq.gz
    ├── 3f5456ad2e8aa9ae87b18ffb862ed0c59b64c67a.nq.gz
    ├── 418b5de92ea745a53b7806888c77e3a905078798.nq.gz
    ├── 41f4c92d986fba3378504fec98506d71713cf029.nq.gz
    ├── 428e8289dcfae6405fbac751bdfcb9dc455dcc5f.nq.gz
    ├── 42a0309202a2ae27683c0c85d892b6670f369aa3.nq.gz
    ├── 42f05247b8bf4c250673cc49c5cd4f3ad9b9533c.nq.gz
    ├── 430cfded03c0576e59ebbcbebbd7c41e866ff8d2.nq.gz
    ├── 435f4752fca36fc99024db6e8036e0f8f6fb4c30.nq.gz
    ├── 44273122c7d79839d52aa3597196d361db7e00f3.nq.gz
    ├── 44675bee467a573c7ca6be72e7db4bb00f6b88dd.nq.gz
    ├── 446cbd40d7e4e67a16eae9debb482e34268073e9.nq.gz
    ├── 44a456167fd18165ac3f4bda1f1365b0ddec92b4.nq.gz
    ├── 453b542cd654c247da7c9516e922a7bf171063d2.nq.gz
    ├── 4607ff1d153ece958d2d44fad53e840c6fa69877.nq.gz
    ├── 466c72872b4737b243e015643644a4308084871d.nq.gz
    ├── 467385a2091cc2697e4db0fefbeb952ded67e710.nq.gz
    ├── 46fc58644aee44b5345a75872582c13d039fb1d1.nq.gz
    ├── 47062478a8a9f17db51cd82a5755220791c6f303.nq.gz
    ├── 470a9acde44b22fb45d7ace3884e223f1afc804a.nq.gz
    ├── 47de792d8bc85ea449ff391db6f4405f044bd90e.nq.gz
    ├── 47f62b2da6d18994ae7a35d8f79e75beaf7e5947.nq.gz
    ├── 482982fe1e6c4eadb2e2e74d84532f908c4e4f93.nq.gz
    ├── 488c355d0660d6754b93973c26b314da09c56862.nq.gz
    ├── 488cbfd358c49afa9af120c952f6b20bac58284d.nq.gz
    ├── 48b82f5fd4a35a75e200019e5d737623db7cf8e4.nq.gz
    ├── 48efdaadaa8e2d9b85647b0388254d5c9a149f13.nq.gz
    ├── 4a0ebc6ec09ee825a3f8719f6f90b8ddf4e4f4ba.nq.gz
    ├── 4a216308a23948ec99cd5c7caecc0fcf9ed8bfee.nq.gz
    ├── 4a4854b380e1dd14b1c67c770d62307a1430a55b.nq.gz
    ├── 4aef5530926c6da1cf285b4fd6779d5172a64542.nq.gz
    ├── 4afa2bc0f4a9cb85646b3df8b21623d9573e55a7.nq.gz
    ├── 4b2d079d0fa0a8792d2ba5473f41f8a685b1a642.nq.gz
    ├── 4cde1db926efdd9087eeb272a002d496dfa79d80.nq.gz
    ├── 4d266c27a4e6c57981f1f42ce30b5df8d1fe892a.nq.gz
    ├── 4de2ab24ed8070312ff90ac85a442b7569c99623.nq.gz
    ├── 4e56ed29c742e336fe490fb11af1fcac5e8e33f3.nq.gz
    ├── 4ea78d178a35f1062fafde8a0a2b29f08883d628.nq.gz
    ├── 4f1a6e247341c43abf8fda99c0fc06661f8df27a.nq.gz
    ├── 4f65d80c8c2f21a78cec03164091f30ae5c6f37e.nq.gz
    ├── 4f89effb5848157cf99b4828aa797afb70805e21.nq.gz
    ├── 4feb4011fa365c0c581c4542a281e221781f42af.nq.gz
    ├── 5072b9e98de667e55e6a1e75740043b5184130b3.nq.gz
    ├── 50e321a9188480ddfdc316f0e8bfff20216efe1a.nq.gz
    ├── 51a1c196e5516ea36624744ebdb5e7a8455d26bc.nq.gz
    ├── 5204ae45151c2bcd414a4c321048faa93f630b03.nq.gz
    ├── 52c59e4486ce82ac789c4042eb81ca440781f863.nq.gz
    ├── 53b9a3a03132e86dac35ad5fa957f2ce7ebae3b9.nq.gz
    ├── 55696ddcc1de7d0d131fb2832bbaf1253ede7aed.nq.gz
    ├── 55d9e6ea0de4f702cf921eec22c0498b1ad61778.nq.gz
    ├── 55f9f411b276f133aee94e24305002042209e84b.nq.gz
    ├── 5694de7989a865b5df2a8f0a0e5f2c4ebe98b311.nq.gz
    ├── 576168304a6c5c031bb13cd4463b2d54a7e7f0f8.nq.gz
    ├── 5761cda3f74526e476723734c4759210476f794a.nq.gz
    ├── 5769ff1cb38a979c670dbe3a6d608481904e5a58.nq.gz
    ├── 577ca5abbf5a9e6f424092064f124f81aed96074.nq.gz
    ├── 57dca672500ecf14c28e8d7bc2cbc44ec284ae9c.nq.gz
    ├── 58d9872e560deb395f7fde683af00d74d5229920.nq.gz
    ├── 58e33e158dcb151a9351556d271499d07141d5a7.nq.gz
    ├── 58febcb300ed310e6fac4e18cbe284d3716f49ea.nq.gz
    ├── 593925f04329d0a63e92a0a0c527c4cfae7166e1.nq.gz
    ├── 59e04bd6134465e17fd8bf2f741312fbebff0484.nq.gz
    ├── 5a0c47032371a2e2f4100a6ddf55bf8fb150c513.nq.gz
    ├── 5aa02e02792f87a7567be193a724b819def8bed7.nq.gz
    ├── 5b32b577cc6ea819fa0ebd847ceff3443214cb12.nq.gz
    ├── 5b677ba08b0fd62d7db8dea57463c2d5dd2d4f4e.nq.gz
    ├── 5be1a026e0d88ec5e36396c8789e0c3acd321a09.nq.gz
    ├── 5beb18340c7f3e55bfa449686f249996c678bbc7.nq.gz
    ├── 5c0f69736c3af714f921bda74621865fb797555e.nq.gz
    ├── 5d6db82a05335dfd494dba6c5006d5c71df9d477.nq.gz
    ├── 5dad87f12a3493e5275ddd7e170b8afd45f4f3c8.nq.gz
    ├── 5e371d40d635400bc2480cb1fbf50331c33bb022.nq.gz
    ├── 5e3a32488a6a6ec208b440b9029fc80b5b945a3a.nq.gz
    ├── 5ecab798e9e39529fb4a711370f3c94cb291abdd.nq.gz
    ├── 5f8d3f74de1f24d1576d44f396ad3b747774f681.nq.gz
    ├── 5fd032d20259823abd3467f25f912a651d4457ba.nq.gz
    ├── 5fd99ce303611497a5775ef17d6b3e87d98b13c7.nq.gz
    ├── 60ad02bae3fc158d271a44164e97cc92121e8a3f.nq.gz
    └── 60d22a11bd56191f9bd3fa6cc76a6006de4226e5.nq.gz

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

[ansible-collections/community.general](https://github.com/ansible-collections/community.general)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
