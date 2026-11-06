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
│   │   └── efc36b1f381854268276a9cb384c22cfe1f63072
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── efc36b1f381854268276a9cb384c22cfe1f63072
│           └── chunk-001.nq.gz
└── blob
    ├── 00200b6dab270a3ded870e3d53d4190e36badadb.nq.gz
    ├── 013c0f7be82f1b2abd0dac367fce231031d58290.nq.gz
    ├── 01716f6130ed1792931a1933366b2357c6d7ef01.nq.gz
    ├── 01c684e472fc028746411aee59927f3eb1a8bc5a.nq.gz
    ├── 01ca417ac67603cbcb9ef32e9e1781838f0dbe4f.nq.gz
    ├── 02009162f2a290e0c7e9c6c6ef69a92d41e1625d.nq.gz
    ├── 0283bb3e85ab7fcd2c76454b48c8c8819c4779be.nq.gz
    ├── 03d2a394a1bcad761f057abed123c9b9591cc3d5.nq.gz
    ├── 04203c8a5e49f21fe9e8b8cad50fdf142428ad85.nq.gz
    ├── 05cb048190b2fc9d81da5b3a5bca81b47dd94906.nq.gz
    ├── 06a2956dbb0a896d8792b944c61be35f006738ca.nq.gz
    ├── 075c7658da1270c7ed0dfc5454d374848b07bb65.nq.gz
    ├── 08af167661e0ffec32c7305c34e624146e7e0a83.nq.gz
    ├── 0901588a87054770cbbcf5a3d10a10fa320b6f19.nq.gz
    ├── 090d5679e37faba3f71b39b8803891d89ca186e7.nq.gz
    ├── 097e2d17e11d7826c2bb55fcd099cf46725459ee.nq.gz
    ├── 09e3ea433883fe9c3d16d41aaef18a724b4d4d82.nq.gz
    ├── 0a5a43f7b3abf5eec949533c5b01348a06ed39ba.nq.gz
    ├── 0a5c3db076e8f4644cb8f1afedd6c2fdd156712d.nq.gz
    ├── 0a69a671df12f99d7f9b15f01199060250599fe5.nq.gz
    ├── 0afbcd1bcb8458a88e31aba6efa9f9d0538ca5f8.nq.gz
    ├── 0b10523a3dc666d1c417ab4f4e474f63c7522eb5.nq.gz
    ├── 0b29a3e5aa273fde7ad9cae2d40eb0e9d8ce5f4b.nq.gz
    ├── 0c079eede94063bba8a74d4853725728509fec2a.nq.gz
    ├── 0c53f96c4077015462dbbf2c266874acbeb1b4a2.nq.gz
    ├── 0cb3e60d165a53ff1d1b1e672129b4374957c566.nq.gz
    ├── 0cdaa0fac02ae9079a50afd8accc0b5068d20ceb.nq.gz
    ├── 0dea272ac7bedcb78cad9f4264867a836aa709c2.nq.gz
    ├── 0e59ed5a55ba0f99a41695aad7c9b52d4259f543.nq.gz
    ├── 0e5be334927de4d97e58b80860e89bcfbad754cd.nq.gz
    ├── 1006df42260f7b4c4974498537be0631598bfccf.nq.gz
    ├── 10c1fe01f0578eed39c3ba9dd7f820431e834bf3.nq.gz
    ├── 110fca45a33f269ea15e610035d343f58e8852c3.nq.gz
    ├── 11a3f40eef654ebef5aac0f3824c209260a1c1cb.nq.gz
    ├── 11ca311152d3a128c91b933b8572a6773aec113d.nq.gz
    ├── 1224949ae5ec60e7d0b783a4e3b78fcfef04aa46.nq.gz
    ├── 1280be8f7914684688b49ca8666b166778107628.nq.gz
    ├── 1347c463f498dfc8d757e4a9f5b20b62fe164bfe.nq.gz
    ├── 13c248693eab520f2b77a7c52779543327855a2a.nq.gz
    ├── 1425f7baf70409fccfe09aaf0bed94876fb2930d.nq.gz
    ├── 14348281f38b1d8973e29e23f06e492f617fb4ad.nq.gz
    ├── 15fc55d80944e94e26f2a493690e571364c14d06.nq.gz
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
    ├── 190f9d0007f4cbac09e3cbed00ed23d489bb47c1.nq.gz
    ├── 1a3d636cbaef2d7b8b282a8b9d73b5912cc2e772.nq.gz
    ├── 1a777230d0ee964c97e5f63251c0394611fae930.nq.gz
    ├── 1b86d22dbc522d58a86ef6403a64e71e74591298.nq.gz
    ├── 1cdaf69cf202113f2b89263247b175382c0fd135.nq.gz
    ├── 1d3da265d8cf753218eae4aefaf4e6caebfb7de4.nq.gz
    ├── 1da17f94e39eaf53408ee6502a8028b80b3a6dca.nq.gz
    ├── 218c3ef8a088ab426dc0edbbe6567bfa68ff069c.nq.gz
    ├── 218fbeb6e0d212076990b08606e8e2948dfbc9e0.nq.gz
    ├── 21f7f33e0f18369bcbe0b2817d0266c5f6fb1a61.nq.gz
    ├── 227b4fa22cc837413ce4876d2fa5dbe0d3b4aa00.nq.gz
    ├── 22e16fd536c2b807320b6d9d642a4ba3f1238750.nq.gz
    ├── 2371bc3a4329dc2d5268de14a181ab806c0f4696.nq.gz
    ├── 2393fa506a73fb48ad44bdc6c18e02e69b519724.nq.gz
    ├── 2473bda3ba399ef391f07e4502e12b48d8d8b4ab.nq.gz
    ├── 24cc3e22371576fe102be9154aa6f4c44262f882.nq.gz
    ├── 251a4ca28ae774076d43efdf904293582df142e8.nq.gz
    ├── 25a0c735bc0e251ebfa1939eb6ed104e5e6cc87c.nq.gz
    ├── 25dbb00a521848e5ec251442b5df03a18759bd61.nq.gz
    ├── 263799ddaa2a8994c4c8a6e75feb7968517dbb44.nq.gz
    ├── 2647de531794f87a176b9639243419d61319b453.nq.gz
    ├── 265313a82e2462ba21c442c22ce39fb96b563538.nq.gz
    ├── 265cb3b3e441446ad24a59629b44e38d5230ecef.nq.gz
    ├── 266aae0f84708d5a975a52974a8666ef2ad12ba3.nq.gz
    ├── 269cd8a04cffcdd1327712565422dc1ab453e03e.nq.gz
    ├── 270d48831ceb6ecfeac357ae05b9e1fad0091545.nq.gz
    ├── 27a67c72d2e60a36d185869fc9dbdc1cfdb67232.nq.gz
    ├── 281cc606cfe6249e0566efa199a1a73898e0b349.nq.gz
    ├── 2926796a719ac78051cdc185c51f218d3c6356ed.nq.gz
    ├── 29d0efc59288f2121183fe675f60170221a6b2f8.nq.gz
    ├── 2a566a5b87316faf2e2e24e2787ab47a1406c200.nq.gz
    ├── 2b73018db7a77bc11ea7014b3c4467f649442449.nq.gz
    ├── 2c0c82b993394f24bcceed2b992c961df2aff08c.nq.gz
    ├── 2cd7bc41a6a23ed5e2e7ccd669e802e21b6a70f0.nq.gz
    ├── 2d436b6974ab8b24fe3a0c1414a2914d83b81446.nq.gz
    ├── 2d7b9cfeddfdd3ba5dc675e8830274aa5b1dac7d.nq.gz
    ├── 2dbdd38b85bc4a3ada3c23b3c804b607a7ad6e57.nq.gz
    ├── 2de98475595745a175334efd85c7912d83f00325.nq.gz
    ├── 2e4b095ca917ea0bbf5f8caa3c3887272b85738e.nq.gz
    ├── 2e8e27f90a5fef355981073c5e0ef2d9e7edad5b.nq.gz
    ├── 2f85bff8dcb330144ef58b0927cb2fb5b466fc51.nq.gz
    ├── 2fc34b7cf57bfec14b328bf4415f2ad0944e27a1.nq.gz
    ├── 307b91ed141671818acc0d2fa9f6f518196a9c42.nq.gz
    ├── 30e2eff601ad77fcf0e5cb9376a3fd54773b2d72.nq.gz
    ├── 3124bec8ba7844b8253379b32cb3f17c55b65487.nq.gz
    ├── 312fe55e14df9c44820a8563ecb6bdf11f843b35.nq.gz
    ├── 31ac35bdd57c0d52183127d03f30cdcfc41c4767.nq.gz
    ├── 31da94207f6f52644e4704c953347917d13dad8d.nq.gz
    ├── 3230bb34293998f652f9227cc803b59eeea5b648.nq.gz
    ├── 323ad5e2915855e729e7f9ce551259d74695b65a.nq.gz
    ├── 32bcac5dee044d9cc110774aee2fe7bed52a5880.nq.gz
    ├── 32feff3d05b489ed5c3b252d423de3d2f3569338.nq.gz
    ├── 3333695d8a01d34e266bbbd744139159d9dd84f0.nq.gz
    ├── 3380636f0132cd91c4fca7e74d5931575a71843e.nq.gz
    ├── 33a3708d5d8d36a4861f23b5d4bb1ce8eb588a99.nq.gz
    ├── 33f1b8e4fae6ef6c3aea80a785bb5af63685f1c1.nq.gz
    ├── 34a1577d4fedea39e62eff6edf6d771df0e2ebd2.nq.gz
    ├── 3590e670979fae498434e373e9f64186b74154ab.nq.gz
    ├── 36ba6cba4ccc5e10c6da7d324e3ea1c65cdb121b.nq.gz
    ├── 36f44ebea96bea6cad1bd8ced2ffd5eb2ec10ff9.nq.gz
    ├── 36fa6c5a508d360c67e47000fd397d0ab5585257.nq.gz
    ├── 3720f9ac502235e7086627c13d2ab6b5c3d01c0f.nq.gz
    ├── 378ca1bfa1ec606d0e7df4099894531a77228014.nq.gz
    ├── 3805e26edc6b01395b5599494f95001c5c75ac3b.nq.gz
    ├── 397724039518cfa6a4f3046b17fadb8b15e575f4.nq.gz
    ├── 39a2a58ee9a5d1b56c070c7cec6fbfd3554ddc4b.nq.gz
    ├── 3a2d4c08fe228cbe557e23241cb87f5ad359f1c0.nq.gz
    ├── 3a2f7f6a12d5e38ca2f8016098d0add044b2320a.nq.gz
    ├── 3a304316c75fecd5bd43bb91f7fa42b90ca4e3ab.nq.gz
    ├── 3aaff96f9754d5129da295cbbfd809ed47dc70e6.nq.gz
    ├── 3afa4653957bc2b738d649d405b89cca410745dc.nq.gz
    ├── 3b2aefbea9d44a63e0b8fc2e5c6240c7534c467a.nq.gz
    ├── 3b7d326c589ac0a77deb711423f28279e6a52818.nq.gz
    ├── 3bd275ce94dc7a5d6c2dd36ba6b2f5c97a54748a.nq.gz
    ├── 3c66f3278830c4fbcd12ac219da8ba47e6aa699d.nq.gz
    ├── 3da739fbee0b210c6e45096517fb72ae39f1ebaa.nq.gz
    ├── 3ee5ebf258ab4531147e1554195a7c611150b48d.nq.gz
    ├── 3f46a6b67cb489d614c41902f864c08fc6dccf26.nq.gz
    ├── 41023c15e5c245d6a7caa30c3c0a389b470e19e7.nq.gz
    ├── 4180dff597de85161fe881ab31562dbf53f1d8a6.nq.gz
    ├── 41dc2649f62e58769e30af2144ffb254bac718c6.nq.gz
    ├── 425ae4ea798e9b7ff0bd243b5fee56bc678bdedc.nq.gz
    ├── 427d626bcd5174a6476c04457c16aab2225db1f6.nq.gz
    ├── 42fd09e99bbaca4f66d98ad1e93ea55551ee4d37.nq.gz
    ├── 434133e7bdc6934eb97888c479d4e007336554a3.nq.gz
    ├── 443a334beada08144b4b5c78834c664a223605ea.nq.gz
    ├── 4487394abfb6a144c48e0986e4207bfb09282da1.nq.gz
    ├── 454ee52d00042883493fdf3f4b0a4672faa4dfdf.nq.gz
    ├── 459c7cbbefb1d98f83cf117ff9990eceb4de5350.nq.gz
    ├── 46ac55ffb8788a0698393d4f0f9dbfc9d159e405.nq.gz
    ├── 4820f010e58f6bb530ca2f052a77801feb9417d7.nq.gz
    ├── 48f9d4095868387d8edd3b843d39fa0003cff00b.nq.gz
    ├── 4938b4b5b4da0b864383d5994ea9a58fe858be23.nq.gz
    ├── 497e47aa2f6e4232ea894fe9a38fd7ce9af6f0c3.nq.gz
    ├── 4980e0830045c07d64800f91d5da0cfd42c31499.nq.gz
    ├── 49b390a2a92a6e08bb11b31732c575a85b38dbd2.nq.gz
    ├── 4a2f34d36f5edf96fbc3435fd839704f1d797417.nq.gz
    ├── 4a57443339a478d5fb0163a20562278db5d6cde9.nq.gz
    ├── 4b01d1e580f9071a016a1e3e1c622a53ff69acf9.nq.gz
    ├── 4b4eb90a87acdaaed121381206b84c09f7809571.nq.gz
    ├── 4b700c5656c4d64454451eafa00a8c2615de4a65.nq.gz
    ├── 4cbfed9ce1d948fee922984a0d57b4851045d78a.nq.gz
    ├── 4cde94ac93eb3b335a052596fd3a4669d8d77a4d.nq.gz
    ├── 4ce9b205bda05d710ca5e47dbbeb23f208a3eb04.nq.gz
    ├── 4cfd0589da38d3f15dda8a0641a11adfb0018e6d.nq.gz
    ├── 4d0a13dfd280e15235ded9168c52072c4b871dca.nq.gz
    ├── 4eb5af8472cad43d691820f1f38fbb70a2e150c7.nq.gz
    ├── 4efa37a4b698bc1a3e2f77ad5df8a2679f1fa000.nq.gz
    ├── 4f3a5f35703dc3781548ef1a06fa65ca10c1b298.nq.gz
    ├── 4fd708206e50d9d213233a03d6bba263039693c5.nq.gz
    ├── 5156f6e134bbd0d6d143990858661cff33182c3a.nq.gz
    ├── 530a5a703c56cf964dbdcc3b1670dbae2660d796.nq.gz
    ├── 538861c05c0e38319f94738ddb41da0e5141ba11.nq.gz
    ├── 539e0fcccd65d2dde72e9fbf8596cae69f643add.nq.gz
    ├── 53af43bf3c0c269d32246763a5c1ad028f38e1a7.nq.gz
    ├── 54e2741c6f2c6eb00815b26d9f311a7553af42a5.nq.gz
    ├── 5531cc8971b2a58b60103168e2fbbbf056d61e61.nq.gz
    ├── 554dce34a9bcbe65eb8c6712890398baa9f652c9.nq.gz
    ├── 55ca3d1106c97c10c140a984a78777bd9c53b300.nq.gz
    ├── 57b346bd377a470ba2a349435421537c7f11199c.nq.gz
    ├── 57cab9bcd72414b3c66956b95fa50116d9c9993e.nq.gz
    ├── 5806262a622a7985db459202d31ab72d801aff32.nq.gz
    ├── 584893511b9e2b5bb46fd37edf02eab345fbca3c.nq.gz
    ├── 58969f137447f5a9b7f94f60cd0581ba0fc419f2.nq.gz
    ├── 592431f0fd88f94a248a37f8a047b92d1a832629.nq.gz
    ├── 599431550887f17b004ab689f969d99174e9b1d9.nq.gz
    ├── 5a680f13787c637b61e3a6b08d44e9cf917a881b.nq.gz
    ├── 5acd288f422d8965455172942cbddf6560159a19.nq.gz
    ├── 5b48f6b8a9d9edfd63fd92b759449a80a5359db1.nq.gz
    ├── 5b806a4bcdeef4d50db2c0f644c5f0be99abe956.nq.gz
    ├── 5c3ac57521b8174e835fb287ed7a71dce3316a96.nq.gz
    ├── 5c7c7a6de0fd807cabdba093e2914e0e7351734a.nq.gz
    ├── 5c9711c242fbb611d546136eb120efebbc7bd723.nq.gz
    ├── 5d157e42a72c63b8b5d14493c9bb3f478e87660d.nq.gz
    ├── 5e5d9ad9c61ac845bc463e469288a1c4571dc3c1.nq.gz
    ├── 5ebc5f5add0c51e165a97e7320ecc4cbeed17516.nq.gz
    ├── 5f79b64ab4441aa763df09738726c058f788be9a.nq.gz
    ├── 60380ee00da9145cf3eb5d84db1d9a770792806a.nq.gz
    ├── 6299d72865db4eea35f550ba1b64ba1fb2c4cd59.nq.gz
    ├── 63a1d9f04f40b7e1096fcc99ab60f476967a7e0b.nq.gz
    ├── 645725add3882970e02e3222bd1b71b4566ca01b.nq.gz
    ├── 64cdf1561feec4dc6aff687e049016f868061b99.nq.gz
    ├── 6511243fa6e562bc8c59761a2fbffcff876dd2c7.nq.gz
    └── 65342afb1c78a021bcbb5ad84640f7eebd1a028b.nq.gz

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

[slackapi/bolt-python](https://github.com/slackapi/bolt-python)

---
*Parsed on 2026-11-06 by [repolex](https://repolex.ai)*
