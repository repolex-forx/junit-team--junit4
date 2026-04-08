# Repolex Knowledge Graph of junit-team/junit4

RDF knowledge graph data for [junit-team/junit4](https://github.com/junit-team/junit4), parsed by [repolex](https://repolex.ai).

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
lexq download junit-team/junit4
```

This will automatically download essential data files from the last parsed commit. Consult `lexq --moreinfo` for other options, including downloading multiple commits, blobs, etc.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 05fe2a64f59127c02135be22f416e91260d6ede6
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── 05fe2a64f59127c02135be22f416e91260d6ede6.nq.gz
│   └── repolex
│       └── 05fe2a64f59127c02135be22f416e91260d6ede6
│           └── chunk-001.nq.gz
└── blob
    ├── 0025178910127ba810963d2513b7e1854407cbf6.nq.gz
    ├── 00267dfb8056a6dd01b71099d7a4bf7790b62354.nq.gz
    ├── 01465a661230906d0a4ea8c188970cc304f43e12.nq.gz
    ├── 019bd74d766ebd4c033528112148d866555b5c9e.nq.gz
    ├── 01a476bd73414136fcd7b41da9f31ba9f368d8f9.nq.gz
    ├── 020d39445d8028b34880446e9c8eee4a37bd0b90.nq.gz
    ├── 0287351f47df782b08e83786c56259c4c166de6b.nq.gz
    ├── 0293cf8e464b13a2d045580260f2e1edfb5969a0.nq.gz
    ├── 02ade826a888e1fc6ca474c5f7115468eff245ef.nq.gz
    ├── 02bae09e5f9bb6be8ce533f954abce92be36ac86.nq.gz
    ├── 0305102d27f4fe83d5dfed1315662ccc81251e09.nq.gz
    ├── 0331c8f2079973e535c29b6fc734dcae05bbb757.nq.gz
    ├── 0433e72f3343b7863050f10b729b77c9b828ef63.nq.gz
    ├── 043f1df72734830c1c92caa648cbed3c6b3276b8.nq.gz
    ├── 04d7a683652f6e0ed4d94beaaccfc4ca40b87dd8.nq.gz
    ├── 054f0428b4bcef21ff9c36e51cc7cfb233db1def.nq.gz
    ├── 064d4a3aff77be19d4a5e70d65e0e11ea1388678.nq.gz
    ├── 072149fa7cebd3e671b4d6319d1fc8960c3f5124.nq.gz
    ├── 0743bed58bc298b8426e10ff21caa296e9ef6ca5.nq.gz
    ├── 076988bab965496b3541e0bd26332aa7c454d46f.nq.gz
    ├── 0846a1e9d31b80d96bf0034678731406e3e18118.nq.gz
    ├── 08792f202978663d578a07e5e590e1352deda9dc.nq.gz
    ├── 0896c1f3973d8a58d8fb149fc7b21e76cd79452a.nq.gz
    ├── 099b50fe14c422ad68dda1b16e9dd66223dbce11.nq.gz
    ├── 0a017bb5631e27a9ee2ef63466312b4e75fc47d5.nq.gz
    ├── 0a0e7cb6a5833a6e8ed8ffb30ff5b8309d513d74.nq.gz
    ├── 0b9f2c4121fe260b0b904d12d843bfba300aeef5.nq.gz
    ├── 0ba736648bfae36ba36efe08083d399dd356a5ec.nq.gz
    ├── 0be3cecb5903e24269cdfc6ef2b72b18a7f6f8a6.nq.gz
    ├── 0c05c92c2c2eca993373ec89f5ff3f83849f1a0b.nq.gz
    ├── 0c59f330a371b126f94ce2e0b2fd9297f2d5c016.nq.gz
    ├── 0c73ed82afffbf2b43e4c456df59e3de76474502.nq.gz
    ├── 0cb1aff10a45b643522feb6b2a175a295f06b2c5.nq.gz
    ├── 0d0ce93780e6bbc7ee826140f099943be5ecd4b7.nq.gz
    ├── 0d51541adcf8868e89033c30dadc6c9028654608.nq.gz
    ├── 0d893fb6268061f40ab51e70d1265af1e5864572.nq.gz
    ├── 0e79b562f5f2117bda6ff604c25c44cd2ae0ee54.nq.gz
    ├── 0f67766f914189bcb4ecade68e5e011b13939f4c.nq.gz
    ├── 1036cb69bf0a9f120af94090d52757b78866b817.nq.gz
    ├── 10f13a4eafafb3ef750edae95ef4418131b86a0f.nq.gz
    ├── 116d7559d0490e5b1237e9ea35510e0ed18be8c8.nq.gz
    ├── 11fe0c51d7b1e8c9fe888d2889e2ba1b5c766ba2.nq.gz
    ├── 1233cce75aa509e537b5daf25ba985c562ce9bbc.nq.gz
    ├── 131fc1f815434dc9d2a675a570cbe6b30b2e813b.nq.gz
    ├── 13407cc052176e48c5d077f548f144f49f617a8d.nq.gz
    ├── 137617121b2d4f05263ead72270870cbef71c506.nq.gz
    ├── 1409545b5ab9fea37211df850ec4740292026c14.nq.gz
    ├── 146a5acb5218e4f2222c33802a772a164073281a.nq.gz
    ├── 153a1c856f0b8ebbf1c8b40c6a6b6c30e528e81d.nq.gz
    ├── 155a478a4f2c0d564435fcc9c9ab813c5d8cc486.nq.gz
    ├── 16328b47a45ffc960f8a70b98c73e3a887e83c8c.nq.gz
    ├── 16443368d7dcfabc29930e24dd77af26cb41471d.nq.gz
    ├── 16e0b4edb1c19d88ce747ae06dee7eb396746570.nq.gz
    ├── 16e804b9450fcfa2a5e3a7de8d343f19abdb2f62.nq.gz
    ├── 170363aa18d01a87065b36a5a290cb6f81cea2ed.nq.gz
    ├── 17b2665c8909f930c11a99544d9b0c8ede3b2c33.nq.gz
    ├── 17ff2af786ce683ba6638378e30b9e6210a3432c.nq.gz
    ├── 1802390a87d494e319b792fb12cc8674aa0602c9.nq.gz
    ├── 18880b714e2d16b313fe43e9f5933b911380bf41.nq.gz
    ├── 18ca07a4044d59edcd6fefdfa20378b2b8c05ea5.nq.gz
    ├── 18d0d31ce11f877747f8227b055158123ecde854.nq.gz
    ├── 191c23022536a4d9d1d438cac77ff38ed1236aca.nq.gz
    ├── 1934fa2d7e27a5c66b2f242f4afd06f974f34f5a.nq.gz
    ├── 1943d567915c93ddbc7f3642726df53ee5f0f63c.nq.gz
    ├── 199c36d05588845f881c95e2184f398cbaed1297.nq.gz
    ├── 19cca6369be8a2a4c93e67da035325c9d79d8c45.nq.gz
    ├── 19f111831ba1de8094c174c3968563b538d74de7.nq.gz
    ├── 1a0a67b89fa778cfec19264cad3ebe2633d8bcd8.nq.gz
    ├── 1ba6136a2150f89b28e76babd0f823aefeef594d.nq.gz
    ├── 1c1d9d1c34eb79cc20439b2be81adddf43378d40.nq.gz
    ├── 1c5abd9b81b0161e91cb13e898cda20527353d48.nq.gz
    ├── 1c991a9e80e55c170f6a5174ae66fef3e1f47173.nq.gz
    ├── 1cbcfa5a8952a81b9ed1b67e8b1d16fe97fa8735.nq.gz
    ├── 1d62190a231518ccfcdf5ffbff78b5e616f8945e.nq.gz
    ├── 1db6fc7ab0736a013cce145598b243ee5651926b.nq.gz
    ├── 1e74ab91acd4c1a15ef5aa342c2c1d18215db5da.nq.gz
    ├── 1ee4d0c8eeeeaf78b8a559e51d55795944a59c85.nq.gz
    ├── 1f3ab90844b310b0abd18102ac412f7b36076b7f.nq.gz
    ├── 1f96070741067bbf1a4e28ac4d52454ebf47e31c.nq.gz
    ├── 21095fd1574244ccb2ba180f0bc68d0194c40def.nq.gz
    ├── 2138b03b448031aaa54fc833a3ed73eff00a9ac7.nq.gz
    ├── 21935bde64cf7a72a28e81c8afac36b19d8afc37.nq.gz
    ├── 21943e922608493be6a7cef4c1acea79f3f16e19.nq.gz
    ├── 22907e07c56fd241a1486618fcaa0f71b3abdd00.nq.gz
    ├── 22c690a9401bcae605ddb86fc121a9a44a396f60.nq.gz
    ├── 2419f7b364aa09ea35b518bc117b68d593406fc4.nq.gz
    ├── 2429514258f67f74bce618deecccd27d2c69283e.nq.gz
    ├── 25cde879385cec99681d5560e16acb25e5df92b4.nq.gz
    ├── 26465caecc9a21876fdafed4071023815ebd3dcd.nq.gz
    ├── 2695af30ee349536f899a3d3afe5eb29e650381a.nq.gz
    ├── 26d2e2bf41a4aa9ee0598485d5e00d10d976f971.nq.gz
    ├── 270d80086149c97b3b82b58288e84367515e111a.nq.gz
    ├── 272263133ddbd91e56d94d584b87f5c2dd9dd11a.nq.gz
    ├── 275f663c8795a0684029ac4ed44f3563d1041a35.nq.gz
    ├── 284b7f56210243528a4427e3fe068ddd83c1e1c9.nq.gz
    ├── 285ebf522379aac4d85735d928708b1c3140de45.nq.gz
    ├── 289587a447764aa28da022946f67bece8a710654.nq.gz
    ├── 28cbe76300e07101ff15568b8ebc50637051c0c4.nq.gz
    ├── 28eafb3a10509df36c6565e5f4f563e0ad0f6966.nq.gz
    ├── 293fdb32a5c68014e85a2f009e7c7a4132967cfc.nq.gz
    ├── 2965187e33650dbcdec0ddb16001f397556ba3ac.nq.gz
    ├── 29b705be6988477bbfa6fdc486c046f033be7f3f.nq.gz
    ├── 29cfbd14391a8e1b1b9df830088506bb219454b8.nq.gz
    ├── 2a1d50c5767f1d117e07310c623d1c91cd4f8097.nq.gz
    ├── 2aa5176db7757c745e1dc4bf4f80375af3853e66.nq.gz
    ├── 2b149cae9cf105cb90f8b61cef7a7b5eafc39006.nq.gz
    ├── 2be5e49bd01fd8bc5c20edcd9e3591cfe0e754c6.nq.gz
    ├── 2c5e408ed74a2fda8a40f89f630bb1903477bc94.nq.gz
    ├── 2e111372d933e2b727048bfe17b317598418d2ef.nq.gz
    ├── 2e3046a8f8eb7ba20d04bc2f0c7603653d0ea1a4.nq.gz
    ├── 2e876c410587a40b409f9134fd75cd5427e2474f.nq.gz
    ├── 2f22c9620873adf76dcfc46100fba40b5f6865d3.nq.gz
    ├── 2fc614fee482ad399a4e3c724f215da0cf0e04b6.nq.gz
    ├── 30ddd8d38a036546d9db363ca52f928ab50f5bdf.nq.gz
    ├── 3182cfdff39936b253e5dc69c4186f42af90ba91.nq.gz
    ├── 31bd66019e09f6ae22bf02d499aa52c978058e69.nq.gz
    ├── 31cc742527fb74b2a522034d4dd8d7bec4f26bb6.nq.gz
    ├── 324f12bd0e235fd2229eab623014ecc5a9b971ba.nq.gz
    ├── 32c872ee81094b9d6fdea195a25eefc8f7ea460a.nq.gz
    ├── 32d1a7f23180204e5bd237e3cdf9d76081455541.nq.gz
    ├── 332f39daa17bb13b1a5b3c1401c2f4cb0c6c16f9.nq.gz
    ├── 3334b40d0a0fce2f8365c17df08375307b0eaa73.nq.gz
    ├── 334a9235cd26358104e02aefb0bead4471dd4aea.nq.gz
    ├── 338340789ee8127bbcf46f3ee8022e020e03a8fb.nq.gz
    ├── 3428ee28add4591599cf7e7d7afda3a0c8dc45ff.nq.gz
    ├── 350e0df1042d58913bfb96baa5b17475c9b48038.nq.gz
    ├── 36cb8d92106f97288c416261c00a4f08f2252b7e.nq.gz
    ├── 36de4f1062972ff5295462b2c48bd5f0d33aba69.nq.gz
    ├── 3725db81f9543fc2a1b5e091e876e61c241197bd.nq.gz
    ├── 37cb61582de0a5f47e3db35c21dc7cd472dc97f7.nq.gz
    ├── 37f065902884fbd9c9175208fc90ddbaeed2a5be.nq.gz
    ├── 385a1462ac70db9954a674d9f12d9a601af3fe7f.nq.gz
    ├── 386b7ffabbc73ebf57a66497cb0bae124a9df8d6.nq.gz
    ├── 38be96092f241cb4e1ff0d9046b323b67d34b127.nq.gz
    ├── 38eb6934c81289d63c6f95b8ecf6efdbdb3c7972.nq.gz
    ├── 398d4ccce7e2ba35ada1bb748bcf480ea7dd7c9f.nq.gz
    ├── 3a30b5205a3034b9300e3fd557c7c43def470f5f.nq.gz
    ├── 3a6e366b53b5e335a74d619c97d5f0aab10e771f.nq.gz
    ├── 3bc07f403a74f827ed286ca68dce0e68e5a61c11.nq.gz
    ├── 3bca103ed5a414421da327e6c9ef4f99ebb070a9.nq.gz
    ├── 3c13c5c965df37c707b3a0ca21ea3885866fc9b3.nq.gz
    ├── 3d792225d179f1f38a57484a0f30124c017d3e67.nq.gz
    ├── 3e2dc7cb76da2b4eddf6305728228c923e195010.nq.gz
    ├── 3f0f7a33b05176a2a1300ceab77602c38c5318fe.nq.gz
    ├── 3f4a7f40435ccdd9cd44a29f0413d4368fd994ef.nq.gz
    ├── 400fed8fcebff576e71ccce61372ec5dd7b1b313.nq.gz
    ├── 415253ebc62d79f1da363564be3cbf0c2c5b0aca.nq.gz
    ├── 416c99d3b59df6412aebc90d8e77f89536ea49c9.nq.gz
    ├── 418acaff0363e99ad40f4702dbaddf92b7235888.nq.gz
    ├── 41c70a7e0b7da7ecbbcf53b62aacdf8bc81e10b0.nq.gz
    ├── 41d653bcf77a8a985ec11ff5b4fc83cf2f071d48.nq.gz
    ├── 429bde6910e72d95798f865829a574e1b5cba0f8.nq.gz
    ├── 42b492edaad119628e5463e08c785d4ed730a71f.nq.gz
    ├── 431ad495b12f5c953dd07bb7a66b5f94f7010955.nq.gz
    ├── 43482a16b6f22c6da97a728b2875be71734167fb.nq.gz
    ├── 43cf4920bd13641c107f87eb1a0e89e038458d1c.nq.gz
    ├── 441e595a368094f88eba22dff7ba44a061e09c41.nq.gz
    ├── 4471407bab2f39d644a1c4165260387a8ff02f5f.nq.gz
    ├── 44d32a3e5a2c089435523c0d6e7d9efcd237fdc9.nq.gz
    ├── 44e16fd599d03fd66ee0453eacc9f9af0fcb4a40.nq.gz
    ├── 45071ed0a36f77f65417d601ee9c623a56b38e30.nq.gz
    ├── 4551302807b3a765254ea0bfa79ec39e39400648.nq.gz
    ├── 455341aa0cb902052cf2f2f7e4621b288c6a097a.nq.gz
    ├── 466e28917a689e98ac356a26a88ea1f07ee27080.nq.gz
    ├── 46f996b3da3a8373f9511856e03a508050a2a4ad.nq.gz
    ├── 477b1509ce456053d064b40446d8a7720a36cf6c.nq.gz
    ├── 47db56d82ac360df9e0d39dc051d218f47f7f852.nq.gz
    ├── 4804493290ef1e05daaa4940e09c35120f8f9ba8.nq.gz
    ├── 484f58d26d6968e1b298fe6c15e321851abb4fb2.nq.gz
    ├── 48cbb44e4950cd2d388c4b476ccfe20e7d5492a3.nq.gz
    ├── 491d8accb58624eb39e12fc89a292daa6a3b9349.nq.gz
    ├── 496eeb03b820e5a35e5eb6a3e12ef3c738a2d540.nq.gz
    ├── 4a09bc78fb04a2d32995ef8abfa3a51315ec1708.nq.gz
    ├── 4adfac2250fbdfd957bcb2d940809b4d938b3bc8.nq.gz
    ├── 4b5274c31012545cae752e8c35ce51042cd85225.nq.gz
    ├── 4b5f4a406238efc6e797dcdfaf307d74bc7111bc.nq.gz
    ├── 4b7e87847f4cbfec83ccf23f78136d451bb686cc.nq.gz
    ├── 4c5c2cebdcec6f3532c2ee095b374c3870133973.nq.gz
    ├── 4d055d7a401931551a04420025a1d686678ff749.nq.gz
    ├── 4e1a3f42548d41fea9687de74dccdce8fa49b0b8.nq.gz
    ├── 4e249581af73cac2d61689f35b36330ac8ebe182.nq.gz
    ├── 4efa20f634a33cddb269e59daae029d0c2ab8d08.nq.gz
    ├── 4f85be096fda716be9452fcbd53ee72946169ad4.nq.gz
    ├── 5015b76c69bca4f6d954eb35386be59e5e49af8e.nq.gz
    ├── 50cd5f8d120bd75244e08c55cfb6330ec15922c9.nq.gz
    ├── 510468fce2b18129519d1c80e73936f6b7eb0d62.nq.gz
    ├── 5143a738fec8ff46031edfcbc742f1291a67efde.nq.gz
    ├── 5177f48a256eab70dc3c6537e28b8412e9cd6ba6.nq.gz
    ├── 5190e9439f5ee92a08027d61f3b6834fbe1021b7.nq.gz
    ├── 533bb5e1318fcd9949fd22d90346abda4527de99.nq.gz
    ├── 5393c637226eb4885ae69c234ad96e2e12e90ea5.nq.gz
    ├── 53cab04897444aeec258a17c25da68c15c224fe2.nq.gz
    ├── 53e2f708e27615aea2d54888865d9dde50ff08f4.nq.gz
    ├── 53f858b50fcf2464934456cf13b1218e75499d13.nq.gz
    ├── 541a25b94a59d9af54d34d066ae8db47e418fc58.nq.gz
    ├── 5464fb27f9ac2e585e89ed75bdae3c9a0f00266f.nq.gz
    └── 54daf8dc59a7f273bf15bfebf2d7c5a8a768a96c.nq.gz

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

[junit-team/junit4](https://github.com/junit-team/junit4)

---
*Parsed on 2026-04-08 by [repolex](https://repolex.ai)*
