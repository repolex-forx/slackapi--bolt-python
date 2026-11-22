# Repolex Knowledge Graph of slackapi/bolt-python

RDF knowledge graph data for [slackapi/bolt-python](https://github.com/slackapi/bolt-python), parsed by [repolex](https://repolex.ai).

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
rlex download slackapi/bolt-python
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   ├── c64d69d2b64801602c849aa56e0ba2d4161e1f98
│   │   │   └── chunk-001.nq.gz
│   │   └── efc36b1f381854268276a9cb384c22cfe1f63072
│   │       └── chunk-001.nq.gz
│   ├── lsp
│   │   └── c64d69d2b64801602c849aa56e0ba2d4161e1f98.nq.gz
│   └── repolex
│       ├── c64d69d2b64801602c849aa56e0ba2d4161e1f98
│       │   └── chunk-001.nq.gz
│       └── efc36b1f381854268276a9cb384c22cfe1f63072
│           └── chunk-001.nq.gz
└── blob
    ├── 00200b6dab270a3ded870e3d53d4190e36badadb.nq.gz
    ├── 0028096be06c393a4097dc1924799961575d912e.nq.gz
    ├── 00300929ff958f0351599417f235f31e0ce3349b.nq.gz
    ├── 013c0f7be82f1b2abd0dac367fce231031d58290.nq.gz
    ├── 016549bd6ba491168f3dae18949c22548d5b5683.nq.gz
    ├── 01716f6130ed1792931a1933366b2357c6d7ef01.nq.gz
    ├── 01c684e472fc028746411aee59927f3eb1a8bc5a.nq.gz
    ├── 01ca417ac67603cbcb9ef32e9e1781838f0dbe4f.nq.gz
    ├── 02009162f2a290e0c7e9c6c6ef69a92d41e1625d.nq.gz
    ├── 024c29e5992b817fee49e3d0cfef4c6e8d910628.nq.gz
    ├── 0283bb3e85ab7fcd2c76454b48c8c8819c4779be.nq.gz
    ├── 029f61d99617e0e5ef5c3ea3aebe15ac922fe433.nq.gz
    ├── 03d2a394a1bcad761f057abed123c9b9591cc3d5.nq.gz
    ├── 03f7c607643f187b0e3bc43768e58534d1e41f37.nq.gz
    ├── 04203c8a5e49f21fe9e8b8cad50fdf142428ad85.nq.gz
    ├── 0467c01f55730581e4509769313d4b45828b5a70.nq.gz
    ├── 049a205705536bd2b49995b184a5ad59efcb3ecc.nq.gz
    ├── 05959817aeecea56c6429e4ff1c0b2188842ddf2.nq.gz
    ├── 05cb048190b2fc9d81da5b3a5bca81b47dd94906.nq.gz
    ├── 06a2956dbb0a896d8792b944c61be35f006738ca.nq.gz
    ├── 075c7658da1270c7ed0dfc5454d374848b07bb65.nq.gz
    ├── 0789badb64edad22da5e51dc39b6bfe233e37f07.nq.gz
    ├── 088c9665e29b429cb31fe290df248fd46784e2ce.nq.gz
    ├── 08af167661e0ffec32c7305c34e624146e7e0a83.nq.gz
    ├── 0901588a87054770cbbcf5a3d10a10fa320b6f19.nq.gz
    ├── 090d5679e37faba3f71b39b8803891d89ca186e7.nq.gz
    ├── 09584a3654ba49c8a6daaa21cef2e33e16883ac8.nq.gz
    ├── 097e2d17e11d7826c2bb55fcd099cf46725459ee.nq.gz
    ├── 09e3ea433883fe9c3d16d41aaef18a724b4d4d82.nq.gz
    ├── 0a5a43f7b3abf5eec949533c5b01348a06ed39ba.nq.gz
    ├── 0a5c3db076e8f4644cb8f1afedd6c2fdd156712d.nq.gz
    ├── 0a69a671df12f99d7f9b15f01199060250599fe5.nq.gz
    ├── 0af27913ce842ad9c646d4a7873a1b0763d70eb8.nq.gz
    ├── 0afbcd1bcb8458a88e31aba6efa9f9d0538ca5f8.nq.gz
    ├── 0b10523a3dc666d1c417ab4f4e474f63c7522eb5.nq.gz
    ├── 0b29a3e5aa273fde7ad9cae2d40eb0e9d8ce5f4b.nq.gz
    ├── 0c079eede94063bba8a74d4853725728509fec2a.nq.gz
    ├── 0c53f96c4077015462dbbf2c266874acbeb1b4a2.nq.gz
    ├── 0cb3e60d165a53ff1d1b1e672129b4374957c566.nq.gz
    ├── 0cc6641fafe23a6bb0664fa8598d1260c8c081c7.nq.gz
    ├── 0cdaa0fac02ae9079a50afd8accc0b5068d20ceb.nq.gz
    ├── 0ddb6281dff9461c52a7808bcdc34e0668959eee.nq.gz
    ├── 0dea272ac7bedcb78cad9f4264867a836aa709c2.nq.gz
    ├── 0e59ed5a55ba0f99a41695aad7c9b52d4259f543.nq.gz
    ├── 0e5be334927de4d97e58b80860e89bcfbad754cd.nq.gz
    ├── 0ed612e16561aa36733bb1061527a47d61a471db.nq.gz
    ├── 0f16f68515c9f24811beed11558bc7f52a33274f.nq.gz
    ├── 0f5b23f8539a5aebbce1b1ec66b00b17b6bae784.nq.gz
    ├── 1006df42260f7b4c4974498537be0631598bfccf.nq.gz
    ├── 101035739fa0ef22f99f97adb8afe6bbb07069d0.nq.gz
    ├── 1038d4a281c24e3d510d9419c23f282bfcf1ac1d.nq.gz
    ├── 107154439e16eb9582beea35c2a003ff458e4e66.nq.gz
    ├── 10c1fe01f0578eed39c3ba9dd7f820431e834bf3.nq.gz
    ├── 110fca45a33f269ea15e610035d343f58e8852c3.nq.gz
    ├── 11a3f40eef654ebef5aac0f3824c209260a1c1cb.nq.gz
    ├── 11ca311152d3a128c91b933b8572a6773aec113d.nq.gz
    ├── 1212e64684359a233c7358858bb9cd58279a8d64.nq.gz
    ├── 1224949ae5ec60e7d0b783a4e3b78fcfef04aa46.nq.gz
    ├── 123fd3cce6c5e7887ce6bb4e5bf70690e0d96e52.nq.gz
    ├── 124daaa4a09474573dad42ca8aa40010188c5192.nq.gz
    ├── 1280be8f7914684688b49ca8666b166778107628.nq.gz
    ├── 12dbab2254ed82796bac90dce0cd602b214d48e6.nq.gz
    ├── 1347c463f498dfc8d757e4a9f5b20b62fe164bfe.nq.gz
    ├── 13a287728ea188a1f21beda7d47bb6e465fc0203.nq.gz
    ├── 13c248693eab520f2b77a7c52779543327855a2a.nq.gz
    ├── 1425f7baf70409fccfe09aaf0bed94876fb2930d.nq.gz
    ├── 14348281f38b1d8973e29e23f06e492f617fb4ad.nq.gz
    ├── 1451c7b19f878e31d544fd89b599773c563fe282.nq.gz
    ├── 14ddfb41bc5acca29d0fdd54d768a9c7bd896859.nq.gz
    ├── 1558e825acbb79350646156b33f974ec6ee95c0d.nq.gz
    ├── 15d1e7367ce993f705a6cfc34f886dca5777efcd.nq.gz
    ├── 15fc55d80944e94e26f2a493690e571364c14d06.nq.gz
    ├── 163def40a68bd8dab224c9f78e47354aaa1fdd0e.nq.gz
    ├── 16670f1b27e8f7a2c6c96910ffcae8738f4ef502.nq.gz
    ├── 1717b1a8dee6093649f847c7095a9170dfdde0f2.nq.gz
    ├── 171de6e2e0e70612721deed9c46334f133fd8a6d.nq.gz
    ├── 17601ffda7b69c0be7be2f0fa4e9963c3afb786b.nq.gz
    ├── 1785a387ef4f220a71f87260135a599a95099b3c.nq.gz
    ├── 17c697e971413016b5a8f22998a5a0c5a053e439.nq.gz
    ├── 18066a9d2ee0f6d99c75127e529533494f9a2555.nq.gz
    ├── 18072c05efe3867ee2c7f4a815947fe6713baaaf.nq.gz
    ├── 185e333474ddebe84b563aba604aa0b4b5441be4.nq.gz
    ├── 186797b8fd7aca0c6d977aeeaf868029a69c1b11.nq.gz
    ├── 1877b07fa65b7c1457e4ee8886a24cf6633da39a.nq.gz
    ├── 18856a3b215405f1c0121c6f62d459815a6efea5.nq.gz
    ├── 18e65eaec242cef4b8ab9eda6a116686b6493350.nq.gz
    ├── 190f9d0007f4cbac09e3cbed00ed23d489bb47c1.nq.gz
    ├── 19716cd74e69c866d2b78b9869be041ea2a3b807.nq.gz
    ├── 1a3d636cbaef2d7b8b282a8b9d73b5912cc2e772.nq.gz
    ├── 1a777230d0ee964c97e5f63251c0394611fae930.nq.gz
    ├── 1ac02bce72cd700c1ad3bd42bbcf4b1f3177524b.nq.gz
    ├── 1ad32e672965afca7ec70a14a8a709592a5e4321.nq.gz
    ├── 1b3d9b17d1313ee003fb7d18004c701133a9fd23.nq.gz
    ├── 1b86d22dbc522d58a86ef6403a64e71e74591298.nq.gz
    ├── 1c3a7a28af06389008451604dc23e90e382c39ac.nq.gz
    ├── 1cdaf69cf202113f2b89263247b175382c0fd135.nq.gz
    ├── 1ce71fc59e300ece942a3171d96d9c239cb108a4.nq.gz
    ├── 1d3da265d8cf753218eae4aefaf4e6caebfb7de4.nq.gz
    ├── 1da17f94e39eaf53408ee6502a8028b80b3a6dca.nq.gz
    ├── 1db13eccabefc2b0ea062fa11ff7d8d70a798b94.nq.gz
    ├── 1dc0860df919d4ce20b531c45a46e1d95b1043f5.nq.gz
    ├── 1dceed45a16d07ec93ed295bd5c05be21f14ce68.nq.gz
    ├── 1dfc3d374ab69abb902da02f9ea8ad9ca190ecf9.nq.gz
    ├── 1ebf70d4ff8323eca3e66455b490e703d0301ce3.nq.gz
    ├── 2079b6448dd618bd02290619cc0a39aa7d567bcc.nq.gz
    ├── 212bd969035b45b8c03710d4284fd1b418e830e0.nq.gz
    ├── 218c3ef8a088ab426dc0edbbe6567bfa68ff069c.nq.gz
    ├── 218fbeb6e0d212076990b08606e8e2948dfbc9e0.nq.gz
    ├── 21f7f33e0f18369bcbe0b2817d0266c5f6fb1a61.nq.gz
    ├── 21ff815e1bd59abc30a2556a50252f17ab6f1589.nq.gz
    ├── 22136e633413178aa164ee1c9bc447f9e368e01b.nq.gz
    ├── 2217cfe9f0e6a3d6c97f769f6a9654223670cb50.nq.gz
    ├── 224fd5fa24a650528c69154c8176519957477582.nq.gz
    ├── 227b4fa22cc837413ce4876d2fa5dbe0d3b4aa00.nq.gz
    ├── 22e16fd536c2b807320b6d9d642a4ba3f1238750.nq.gz
    ├── 233f5485208d3ec0e937295ea12e0a42c1582d33.nq.gz
    ├── 2371bc3a4329dc2d5268de14a181ab806c0f4696.nq.gz
    ├── 2393fa506a73fb48ad44bdc6c18e02e69b519724.nq.gz
    ├── 2450957f4c80d05b40b8c9165c5334888bab44fb.nq.gz
    ├── 246fd10c9bad0586adf1159af358a51c57db7b91.nq.gz
    ├── 2473bda3ba399ef391f07e4502e12b48d8d8b4ab.nq.gz
    ├── 24cc3e22371576fe102be9154aa6f4c44262f882.nq.gz
    ├── 251a4ca28ae774076d43efdf904293582df142e8.nq.gz
    ├── 254183460f4830538d9607071698d5bee85fdec7.nq.gz
    ├── 2549060e73ca1bacd2e3781769139c745be4c320.nq.gz
    ├── 25a0c735bc0e251ebfa1939eb6ed104e5e6cc87c.nq.gz
    ├── 25dbb00a521848e5ec251442b5df03a18759bd61.nq.gz
    ├── 263799ddaa2a8994c4c8a6e75feb7968517dbb44.nq.gz
    ├── 2647de531794f87a176b9639243419d61319b453.nq.gz
    ├── 265313a82e2462ba21c442c22ce39fb96b563538.nq.gz
    ├── 265cb3b3e441446ad24a59629b44e38d5230ecef.nq.gz
    ├── 266aae0f84708d5a975a52974a8666ef2ad12ba3.nq.gz
    ├── 269cd8a04cffcdd1327712565422dc1ab453e03e.nq.gz
    ├── 26c54df15dca1d163b59a216e38fb245a77e3680.nq.gz
    ├── 26f164ba6c307d539a776e17b49703deab6aab61.nq.gz
    ├── 270d48831ceb6ecfeac357ae05b9e1fad0091545.nq.gz
    ├── 27589b3489734a8e2bdb8ad8d1ca421be20837e9.nq.gz
    ├── 27a67c72d2e60a36d185869fc9dbdc1cfdb67232.nq.gz
    ├── 27b5e7d093e6e05228a9becd646eaeca6fbcf957.nq.gz
    ├── 281cc606cfe6249e0566efa199a1a73898e0b349.nq.gz
    ├── 2861b44258269ef4bf35ef5164ceb568ff88dbde.nq.gz
    ├── 2926796a719ac78051cdc185c51f218d3c6356ed.nq.gz
    ├── 29d0efc59288f2121183fe675f60170221a6b2f8.nq.gz
    ├── 29d244a658049132131e2d1d8f6fe497fe003e49.nq.gz
    ├── 2a09434a8b6702fb5154177b03e1fd55612dc625.nq.gz
    ├── 2a418a33f0bbdaf688654687b9eb220f2505314b.nq.gz
    ├── 2a566a5b87316faf2e2e24e2787ab47a1406c200.nq.gz
    ├── 2a77261f9ed2aed0f0501d519e7fd1234cbdf734.nq.gz
    ├── 2b0252645c6aca0148510c2d380487470532364a.nq.gz
    ├── 2b1dd5593e32fbc6e781428e2979544c51c046e7.nq.gz
    ├── 2b4c289e25d52cd6d43b653b9e1e161507dbc4ef.nq.gz
    ├── 2b73018db7a77bc11ea7014b3c4467f649442449.nq.gz
    ├── 2bbaf5ae5199433b74fd9eb0f8d61f0c1b12b433.nq.gz
    ├── 2c0c82b993394f24bcceed2b992c961df2aff08c.nq.gz
    ├── 2c9adea43da7fa84fbe00431fd84e0925ddf612d.nq.gz
    ├── 2cd7bc41a6a23ed5e2e7ccd669e802e21b6a70f0.nq.gz
    ├── 2cf7e361eca8e3907dc3fd03673db13889edf0ef.nq.gz
    ├── 2d436b6974ab8b24fe3a0c1414a2914d83b81446.nq.gz
    ├── 2d624117d0122bf1ef1d999b285521e88d842c23.nq.gz
    ├── 2d7b9cfeddfdd3ba5dc675e8830274aa5b1dac7d.nq.gz
    ├── 2dbdd38b85bc4a3ada3c23b3c804b607a7ad6e57.nq.gz
    ├── 2de98475595745a175334efd85c7912d83f00325.nq.gz
    ├── 2e29c55df53944881387b0d3dd90d4235d1fc86e.nq.gz
    ├── 2e4b095ca917ea0bbf5f8caa3c3887272b85738e.nq.gz
    ├── 2e8e27f90a5fef355981073c5e0ef2d9e7edad5b.nq.gz
    ├── 2ecac487fdf3e76931f98b47f4de554f8fd37318.nq.gz
    ├── 2ecd5255475ed9967255106a9ea19599bb389a4b.nq.gz
    ├── 2f183a4629f5975965bcc45f46f6f76139bc0a15.nq.gz
    ├── 2f85bff8dcb330144ef58b0927cb2fb5b466fc51.nq.gz
    ├── 2fc34b7cf57bfec14b328bf4415f2ad0944e27a1.nq.gz
    ├── 307b91ed141671818acc0d2fa9f6f518196a9c42.nq.gz
    ├── 30e2eff601ad77fcf0e5cb9376a3fd54773b2d72.nq.gz
    ├── 3124bec8ba7844b8253379b32cb3f17c55b65487.nq.gz
    ├── 312fe55e14df9c44820a8563ecb6bdf11f843b35.nq.gz
    ├── 315ec2a50ab062749b823a21008a4a22ff856a60.nq.gz
    ├── 31ac35bdd57c0d52183127d03f30cdcfc41c4767.nq.gz
    ├── 31da94207f6f52644e4704c953347917d13dad8d.nq.gz
    ├── 3230bb34293998f652f9227cc803b59eeea5b648.nq.gz
    ├── 323ad5e2915855e729e7f9ce551259d74695b65a.nq.gz
    ├── 32b57857679240ef2720ccd35f9c67cb62c9dbaa.nq.gz
    ├── 32bcac5dee044d9cc110774aee2fe7bed52a5880.nq.gz
    ├── 32ddaff149ca8e5026de6fc6f6fa6176634d072d.nq.gz
    ├── 32feff3d05b489ed5c3b252d423de3d2f3569338.nq.gz
    ├── 3333695d8a01d34e266bbbd744139159d9dd84f0.nq.gz
    ├── 3380636f0132cd91c4fca7e74d5931575a71843e.nq.gz
    ├── 33847fd56bee9f7fd5ce62e08f35364db84200f2.nq.gz
    ├── 33a3708d5d8d36a4861f23b5d4bb1ce8eb588a99.nq.gz
    ├── 33f1b8e4fae6ef6c3aea80a785bb5af63685f1c1.nq.gz
    ├── 34a1577d4fedea39e62eff6edf6d771df0e2ebd2.nq.gz
    ├── 351f558d239d729d3cd19125b68590768e05c093.nq.gz
    ├── 3590e670979fae498434e373e9f64186b74154ab.nq.gz
    ├── 36ba6cba4ccc5e10c6da7d324e3ea1c65cdb121b.nq.gz
    ├── 36f44ebea96bea6cad1bd8ced2ffd5eb2ec10ff9.nq.gz
    ├── 36fa6c5a508d360c67e47000fd397d0ab5585257.nq.gz
    └── 3720f9ac502235e7086627c13d2ab6b5c3d01c0f.nq.gz

10 directories, 200 files
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

[slackapi/bolt-python](https://github.com/slackapi/bolt-python)

---
*Parsed on 2026-11-22 by [repolex](https://repolex.ai)*
