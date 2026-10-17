# Repolex Knowledge Graph of Nixtla/neuralforecast

RDF knowledge graph data for [Nixtla/neuralforecast](https://github.com/Nixtla/neuralforecast), parsed by [repolex](https://repolex.ai).

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
rlex download Nixtla/neuralforecast
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6c11accfbcfdd62a40ef69a7c81e3d9c7f272682
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6c11accfbcfdd62a40ef69a7c81e3d9c7f272682
│           └── chunk-001.nq.gz
└── blob
    ├── 00a70cce4c6eada0a8b70d77e9353160559b66bf.nq.gz
    ├── 00e06b3d76ad4c6924e129f5090d4fe0dbe04686.nq.gz
    ├── 01605df9abd09552be6b7b30258d0e575da177d8.nq.gz
    ├── 0313bd567239be715af423df954df35cfa07a93c.nq.gz
    ├── 03ea7cf592b1ba2ccbd6e6f304c5b588f9f6befb.nq.gz
    ├── 040d21a29af96c60aba20c2f08816a493c2f3862.nq.gz
    ├── 046d9539b02ba639d01991f2b7254469d0a949c7.nq.gz
    ├── 0471b84ed31737a9f5200b41cd0b44921abfb0ef.nq.gz
    ├── 0524f90015573c4906b17b98b7cc0fd2664b3aa9.nq.gz
    ├── 055456a63723993267ed3535f856c21fb056a0f1.nq.gz
    ├── 056b9b7497c26ce49f48d15df049c8a549d4ca6c.nq.gz
    ├── 057af097ccff970d0939952153733e0aa3005bd5.nq.gz
    ├── 05a083c2553a5517e414cf8886374f2020c7408e.nq.gz
    ├── 062b3d75fe52f654a92b691e201928bce06db7b4.nq.gz
    ├── 063f79a24121fa0a9a51025b1d599f8bca121e7a.nq.gz
    ├── 07293bf8b2131289b2b3345ed8a18792c0e2d830.nq.gz
    ├── 075a48ba24db62f9aaf63823df5d4119638504bf.nq.gz
    ├── 07d0167798300d9947d8fe39362f710aa234255f.nq.gz
    ├── 08d21f015041d709f671fb972a6935ae02a34ac2.nq.gz
    ├── 09b0741ba7dc89fe9f1f5168b68052a644251c8e.nq.gz
    ├── 0bd11bf85b61c8367a6149a9bd1b97738a7dc53e.nq.gz
    ├── 0ceadef05c4c4cb34d75da2143ce5a882e314bda.nq.gz
    ├── 0d70979f44bd0d039aa76d996ab97c9a63a6fbcb.nq.gz
    ├── 0ee62b44592699a547daec36e044289606324233.nq.gz
    ├── 0f00d372b9b0234d2a088c8d24532589890abdd6.nq.gz
    ├── 0f044b3bcc1c7ab15b577845f9d7f32ed533385b.nq.gz
    ├── 0f507ad4e22d86232499af7f47044ef765a9f653.nq.gz
    ├── 0fb7796e83e90f64dcf2716781fb37301dfc3edb.nq.gz
    ├── 0fc43982e4219a351fd2b3132173819fc57d8826.nq.gz
    ├── 0fd3e1ad2a5dd2f23f45a132757a574d357d2313.nq.gz
    ├── 1015b687b0515fcdefc78951ea779eb0392d6b9a.nq.gz
    ├── 10223422604be1bcf90b1e24e1f85e2909f7e2e8.nq.gz
    ├── 104cfd9a73006351e50d53dcdea822b18b032396.nq.gz
    ├── 1079b0fd4d38c4d34dcfd9decdeeb7bcf6e10aef.nq.gz
    ├── 10efc82a410f6d74d061cd2b7a59b8252a8472d2.nq.gz
    ├── 110948633b0707cc9c561dfd15cc882d1e4ad621.nq.gz
    ├── 11c7cf4dbdccff578a93510e3e1bfc3df30ab48f.nq.gz
    ├── 12bfad8d257865940c830d16aee6f308e349d874.nq.gz
    ├── 12c5ef41dd99885dccce74864d9354a8f932055b.nq.gz
    ├── 13e32743490ff3c9cdd910d2f29ebcb6f3dfedbe.nq.gz
    ├── 14233d7c46ad8a2f7bd596fa79da13fda1a2d19b.nq.gz
    ├── 145a0415af2780bfa02028b782e9b4fbdfc7937f.nq.gz
    ├── 151296a4ae66065a078c1aee9697db96dbde8f96.nq.gz
    ├── 15cf190cdf34d8712ddf2e0e7be1a270122de85c.nq.gz
    ├── 164d2d57d16b2f4ff32e44d466ed41ef8eb54890.nq.gz
    ├── 1660ac2685a04ab01771a2eb985bf5a44a76c499.nq.gz
    ├── 171cee676da1e821659194927ed3c83a313e1d21.nq.gz
    ├── 17c27b439f624ab41a801c8af67deec41ecdbbb6.nq.gz
    ├── 1a6632a7ee4f9110fe9e0949e6041ceb2c014ab0.nq.gz
    ├── 1b4c360450b3347a4eb0b3bb95671d794de8cbf7.nq.gz
    ├── 1c5cc457e31c73094bf5169a2d2d54c3a630c97b.nq.gz
    ├── 1fca14ff73844b59ae9954668b25661d400c5f12.nq.gz
    ├── 2084e4104dea94a173d6aae7e78691d107b7b69a.nq.gz
    ├── 208fac4f3594b54c76fd4c8a3db2088ad3ca814b.nq.gz
    ├── 20db8f1675675acfd1da70bfc8a3c1c17263f956.nq.gz
    ├── 22632cb873e98ccfabd5e3b42175f6e6e5909dfd.nq.gz
    ├── 22769965ce82f981baace234b81dcd47400f3d9a.nq.gz
    ├── 22d7903619deeabb10e692774f3582681d5a0aec.nq.gz
    ├── 23a7efbeb47d056ed05d4e17b3c5ee92cdbb44e4.nq.gz
    ├── 23d3350ca2b9a85780d9650be25b02e99d7688f9.nq.gz
    ├── 2438565c8c5e56d9b65d2b05515bda65cf6636b9.nq.gz
    ├── 249b6c199beb1665880a39c67fd1c60b329f6610.nq.gz
    ├── 24df045429b004d0a04d012c8b297db8d425fa62.nq.gz
    ├── 24f25604c10c2aa7295a23c3a54ff76d0459d1d5.nq.gz
    ├── 2576e992ffe97faf03b6c227694054aabbef6983.nq.gz
    ├── 26c7065d40414a0a52a1d07dae7b48a0cf514ea1.nq.gz
    ├── 2710a2658a7295997e0afd9335ed6855e00ecaef.nq.gz
    ├── 278b615dec3517c8745306ff5d123faf47d26faa.nq.gz
    ├── 27f78caf154513e26527d387bf2bc91f1f1ab3ac.nq.gz
    ├── 28439071ea8e626c3460bfa975715dc744af4e80.nq.gz
    ├── 29dc0fab16dca1c512a73857293b15c8a40e8323.nq.gz
    ├── 2a2e31fa2f976a3d29e1797563af842eabeca43a.nq.gz
    ├── 2b87f3dc15569c9d10f9de5a8258a689f54af126.nq.gz
    ├── 2b9f7e198868b22ec8e3cdb4e61a188870d58004.nq.gz
    ├── 2c0e0b027cbe2fb59b0f17781ec1b3b7c6f991cd.nq.gz
    ├── 2d2570b17ea0bef8915a6dd63eb627a3396f1ef2.nq.gz
    ├── 2d29ed590411f40f237b399c781bcc9ec9147e7a.nq.gz
    ├── 2d34d6b6fc0865fb8aa32a2f20c15a0f4956de41.nq.gz
    ├── 2e53c67666f021a17cf7fe0847c279827d19d724.nq.gz
    ├── 2e7d8699c158d0435e2ebd5beded2b11e2321cd3.nq.gz
    ├── 2e91695e790d4474a8d86287802bdde0118d6529.nq.gz
    ├── 2eb900b7eff870cabe778afbedacf5c0ea1c61ba.nq.gz
    ├── 2edf5fab8d2c2b61b2398dcf9371e808b2f45326.nq.gz
    ├── 2f39fdebc93db6914e8a98796769303fa94e4b39.nq.gz
    ├── 2ff5076e3a6aefece9f8ede3dec2f57facc52a5f.nq.gz
    ├── 3241705b998dc9fa5a472ab22095557386ba113d.nq.gz
    ├── 324d02137ea93fd8daadf2dd3683dbc45405ec47.nq.gz
    ├── 32e9c1bbc08a47873e84a5f56a7e29ab7f8d3803.nq.gz
    ├── 33cdbb05a84e8939229fbe55cd5321c1511a1986.nq.gz
    ├── 3405ffd786b2ea059173f7b9d1825947228d38b3.nq.gz
    ├── 34511a1906948a952792a8cc56d1acf1fca2c5fb.nq.gz
    ├── 36e712ec37c72fb6c5fbcc605678577550e64bd8.nq.gz
    ├── 3721f560f64b679827d492ce8f53eb909220751d.nq.gz
    ├── 37b020a522221e5856b6873163198e3378aa9965.nq.gz
    ├── 37e39ab33176a603534f51f93823712361f87963.nq.gz
    ├── 393f9179e6d565d85a74e518e88c165f35e86453.nq.gz
    ├── 3953221247ab7c0991197caf44fede7bf72990d0.nq.gz
    ├── 39a05b2eb39036a632724030ef7914704610f81c.nq.gz
    ├── 3a4c3f382aa2022c8219697147185bb0fb3ca18c.nq.gz
    ├── 3ab0730e0a97567e6e7e15cff4fd782089ec2db9.nq.gz
    ├── 3b368deef9c0b3f2c911bcf6db8f0a1b89740993.nq.gz
    ├── 3bdcecbeb6dd61b6feb27b45746e8bf5c302c894.nq.gz
    ├── 3be88ac425ce40c9831936fdac1e364585a71b33.nq.gz
    ├── 3d26badb6fcd1453e9810c1d177cb343c7872a11.nq.gz
    ├── 3eaf667ead02e0985c62512be8df3ed6aecc84a0.nq.gz
    ├── 3eb12548087a527065315bf9d09d31ab3a707901.nq.gz
    ├── 3f5d8a6d6b348c2c90b494c6ff751235ee56515c.nq.gz
    ├── 411cb66dab3d83ca89473d4a56523e3f93e5d674.nq.gz
    ├── 4142a0bbde38d8801c80e73a8fa18df0baffb465.nq.gz
    ├── 41fb820b3af60abaaaa6e5e4157373bac6cbeec4.nq.gz
    ├── 4237c7b7140398df0419184a1d01952a180b3ca1.nq.gz
    ├── 42a8e6849601fc7fc6d052b5d1bab613d0614998.nq.gz
    ├── 43d24692dfe2d91a8417afa5d6a6f9194d2e560d.nq.gz
    ├── 458bce70b8f7792d2343f868eafcbe066a66ff4b.nq.gz
    ├── 46112179e3f3270a96a0c1ad7539501d918ae0c0.nq.gz
    ├── 463d888082a3553d75a71835f730ea7ab26eff98.nq.gz
    ├── 46558f67f0802e65f77cb8239399be5c6afcd37b.nq.gz
    ├── 467b4dff57b982eab8f93c7c0593420908cc447d.nq.gz
    ├── 467d1cb93a9763755b4e7d429f96108d836ec7ee.nq.gz
    ├── 471fee6bcd45a9a5030b6c28477c7fe9f92dc995.nq.gz
    ├── 4749acbc8b4640019d25156127aca0d72f007688.nq.gz
    ├── 4771167b1038184a60078bc0a9183c4ac9306109.nq.gz
    ├── 47a131cdaf464123c6f06283bf7206255e50fdc2.nq.gz
    ├── 4a9684db576e0e8f920ea02b6dcd45e6603a9776.nq.gz
    ├── 4c87d7eba94c7c183107bc0b15da621acca08c69.nq.gz
    ├── 4d0013e3a8ff4c346c5d049d2b09bcd0c9828577.nq.gz
    ├── 4dd133df5cfe0fb7b083ce8e0e56a70801781891.nq.gz
    ├── 4ec79f0bb2d93a10e3197129d7fe93640fc7db7e.nq.gz
    ├── 4f02e9e87455046517b0c0d306443fa3ba7f42cc.nq.gz
    ├── 5008ddfcf53c02e82d7eee2e57c38e5672ef89f6.nq.gz
    ├── 51976d649a10f96e46049a37fc45e5beeff3407c.nq.gz
    ├── 5209c322ff8537e3825733492197635c5f6e88fb.nq.gz
    ├── 536d66dfa57c9407a792dd36d80652fced315159.nq.gz
    ├── 539dff008cf43cb34340283ebf419604f2156c89.nq.gz
    ├── 552e16fd039eef04aec434e3504241b37ccd489c.nq.gz
    ├── 57247535e7abf9b9aac7d47ac2deb32ad65c89ec.nq.gz
    ├── 57e69afde41618f1862157032f6798a75747cff1.nq.gz
    ├── 586b58d6583eddb2c8d59559c46ed0a3435e688b.nq.gz
    ├── 597561e592bd8cb0c7a46364abebabbc34da9f43.nq.gz
    ├── 5a12e20f7bee73e1f2ac7b87e2143d92ecdb126b.nq.gz
    ├── 5ae0c0b6ba0478652583a901dbdfbe3b993fd687.nq.gz
    ├── 5be63e165f2eba278763f3f2faff79568f6b8dd2.nq.gz
    ├── 5c5e163b40543350945361ad9c92bfda1042970e.nq.gz
    ├── 5cd6f242342f2aaf3b69f92d2b0709c793f1bfc0.nq.gz
    ├── 5d4345671a0cb7d193abeb9c26092ca227286e61.nq.gz
    ├── 5dc4eccd1dd68dbfe8bab18a61e0d1ba3d66021d.nq.gz
    ├── 5e2e21fcba75e4867c8e372bc8ac78512fc80289.nq.gz
    ├── 5e520fd9c8b408cc738c3fc440b7be43885367fc.nq.gz
    ├── 5fc2d3352eeea4ae2e7401d70419bd93c92b4848.nq.gz
    ├── 5fd2c15431258e2f7dfd57c9e03e185a868263b5.nq.gz
    ├── 5feddaacd3267d44a8a49937a3299444e010f8ba.nq.gz
    ├── 60220b825317138bef7a64bb04449e328271b0e6.nq.gz
    ├── 611b4c6b635755b3a6e64d7c0a50348fa7752b62.nq.gz
    ├── 613f4e3f25ec7b029001e8b53cc7d53e3a223d8f.nq.gz
    ├── 6363c133b3f0bca2d6ef769e0ecb3c3d818e18f3.nq.gz
    ├── 65d36995b927e2617fbce9981653d3cdde2fdddb.nq.gz
    ├── 667ff215c23d1bd4ab12a1f449753f958aa9e8dd.nq.gz
    ├── 6768987325e50c9617d572fafa8d2e228959cfbe.nq.gz
    ├── 67804e992aa5df55f28de71032b5b385e3c57874.nq.gz
    ├── 68629516850485f0e1517bc9c15288a2c7ceb754.nq.gz
    ├── 69e561d2159671b37495f1edbd77c095d9ee7a25.nq.gz
    ├── 6be01d70c64c82490a5cf263dcbe487bfde47af9.nq.gz
    ├── 6d1ac5edec14426acbccf010b53b638626586d3f.nq.gz
    ├── 6d4bd570bc77274d05a219fa77f05c996a065584.nq.gz
    ├── 6e3383d7d9bf50cc3bb1f483d97341906c220202.nq.gz
    ├── 6eec62e544d68300d723a189cdaea19101b542b7.nq.gz
    ├── 6f123efa8d916fa06ec388f3e817fd032965c535.nq.gz
    ├── 700de2f36519df70fc20cf815c997ca151c794c7.nq.gz
    ├── 713711bfc2a8db85423594995951f981ef9a0914.nq.gz
    ├── 71415a60d079eaedc27e13019a4b4ba87a6a0bef.nq.gz
    ├── 71a5bc068e0a9ffd99ef96ddb5702e289fc3d4d9.nq.gz
    ├── 71cc4d4d922b68b9cf2114644ccb0efc568291e9.nq.gz
    ├── 72251f403051735a86b5320edeb857d9639db786.nq.gz
    ├── 724895a02dde72bed865a58c453eee9642fcb3c9.nq.gz
    ├── 7266a88c7776625e72940ca1cb1eae219f6b4bf0.nq.gz
    ├── 7404181df2222101a3971d74c105ae4ac0e923a7.nq.gz
    ├── 7646d6e2f35cbc86aaee0a4d7a7866c8103e25b0.nq.gz
    ├── 77aaebde974104162dcaf0eaef2ac2fba082b011.nq.gz
    ├── 77ccf1ff6f7cbe042c2763025bc39aefc4cd5b19.nq.gz
    ├── 78b38123afda58bc5e8e17035cbbb02a0cf597db.nq.gz
    ├── 78cf9ec6d861bbf0945c15840c41c3312f582b59.nq.gz
    ├── 7a43fae903df82e358e1664ecde9f71d4443a438.nq.gz
    ├── 7b40204bfca07271f0297d2759d6a6852941d1e2.nq.gz
    ├── 7c1d0e40b7d2d204f8db89593552bf068f6a1bf2.nq.gz
    ├── 7c7684de22282513d154d0f8fb2a7c09e8bafa69.nq.gz
    ├── 7d5186699063140401c3d3b49bc3096579c5ba9e.nq.gz
    ├── 7d78ad959a1bccaeabec3116e6e146a4b136fccf.nq.gz
    ├── 7e3f6da3a6bf2413b70359e9b903625af399f234.nq.gz
    ├── 7edd7efb9630afcfc4b5e2da99f01271f8de264b.nq.gz
    ├── 7f6576949aebb5b01b79a12bba16dc21724c7a9b.nq.gz
    ├── 7fe75886041890042ad3ac663ebc0968c39ac9c5.nq.gz
    ├── 8045520730b1d19da862644a80d9b3984a7b7fd7.nq.gz
    ├── 808bfe2f0b4f032ac51b606bb353d0abb9e9ff6f.nq.gz
    ├── 81e439698571ff598860e20c1127b9bdc5f30ba3.nq.gz
    ├── 81fd07a892e2968d67c03d4518d00f9f3dcecea1.nq.gz
    ├── 83c6c7232789dbba8ab8528b8d4ce36491f785c6.nq.gz
    ├── 894d9406c156a3ee857d2cfa77211b31ed863e00.nq.gz
    └── 89899330f0a42a5d995c81d07ff5091933980c90.nq.gz

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

[Nixtla/neuralforecast](https://github.com/Nixtla/neuralforecast)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
