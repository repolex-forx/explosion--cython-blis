# Repolex Knowledge Graph of explosion/cython-blis

RDF knowledge graph data for [explosion/cython-blis](https://github.com/explosion/cython-blis), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/cython-blis
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 44dd59102136586e758297a86fc78369c37c80b0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 44dd59102136586e758297a86fc78369c37c80b0
│           └── chunk-001.nq.gz
└── blob
    ├── 0059670f3faf6e1d3ad33908246e2e146daf875e.nq.gz
    ├── 00b604de6e8e73b2816a64d71e413edc7a7afed8.nq.gz
    ├── 01b908dda123c36c91bdd2a8c73e9c60757f809d.nq.gz
    ├── 025523b2c922442ee2f9dab188ec0cad9f4d6d6b.nq.gz
    ├── 029ded9bc1e449f9528c1e58ce8f3076e7e82f20.nq.gz
    ├── 030c0e2191e3e8ad9e0e2bd0c8e76ade90159de7.nq.gz
    ├── 056006281435f3bb5900b36a05777cf9017f1666.nq.gz
    ├── 056daf2bb144221a436946278eac31c90ac8d20a.nq.gz
    ├── 057eb0a1d866c1a5826a98ffd5000729de51b1f1.nq.gz
    ├── 05e1c684ac0aaaf9222b19dbc7070897d72fe726.nq.gz
    ├── 06dfdfcfcca4515d3fc4f7bd0222f919eaafd062.nq.gz
    ├── 06f3bb18b11092e90d72f229086140ef89db1f12.nq.gz
    ├── 06fbe7289a5fce85f259b5f4a42ea108a0ec9af5.nq.gz
    ├── 0740b7b269e0ea499fcf7923d517227a0948bf50.nq.gz
    ├── 07649409799be7f6dbf0e849c3cb1fc7b01453de.nq.gz
    ├── 07c52d82deb6d880dca754321e01e824572b7168.nq.gz
    ├── 0837352ae978ed3a9026197966cf3935396e1708.nq.gz
    ├── 08c2dae531787552f2f75158baf5337841b4149e.nq.gz
    ├── 092e5ab4ef45798f561bfe1a77709c3b16eb8e02.nq.gz
    ├── 096091e76519a3e7dbaad209e81ab2fa8cd5ef7f.nq.gz
    ├── 09a2df81f4783ded7de5e5b19e2110dd0cdd7294.nq.gz
    ├── 09b3af9ceeb53b1a42b28bf566ba0e6aeb518993.nq.gz
    ├── 0b41a067347a7be646b8b4a52e10d0cacea2de7a.nq.gz
    ├── 0be035cf87f9a04869069e9ada1e0b42bf2b2a7a.nq.gz
    ├── 0bf3ad85474a387f5b9c68047f9ebc8676658bd2.nq.gz
    ├── 0d5c98175bbfd322e85571e7528d88732681b848.nq.gz
    ├── 0df1ef29ec036e4fad19826e1078c6e908de14f5.nq.gz
    ├── 0df230d8fd5f2b344d340447233f104e65d61226.nq.gz
    ├── 0e1b09226c086805d65747072ac96343d7f13a45.nq.gz
    ├── 0ef9ee85a5d35762a1c4f1902436c3fb63ede0c2.nq.gz
    ├── 0efdb86c2db2e6002e8a40a5aba187c561bc5a9d.nq.gz
    ├── 0f2fe06b73b4c9bf98c9db672b97f8cf0b69c416.nq.gz
    ├── 107aae74225b97dd92fef9ad3e515a5d110b79be.nq.gz
    ├── 12223d3e336184294531526ae768188c7cebede6.nq.gz
    ├── 124421665a4c41fee85cc05c20dbb0956acbcd37.nq.gz
    ├── 128b1f92e107b2cccd806d868773695c77b9ad3f.nq.gz
    ├── 12b16444f4f52fa6a795a5f5fa72c1d474ed4624.nq.gz
    ├── 12f27ad873f14cf4c3af659fb8dee6d20235f76c.nq.gz
    ├── 12f927056c0c5f3e8bd788f9b23591d417f485a1.nq.gz
    ├── 1344749e063903e39b32344077e7e65f5998d3fd.nq.gz
    ├── 1362b40355485b4eda615533bfd53e3fd63827bd.nq.gz
    ├── 136f3153232f5f8624ac110c9edc4fd9702398e0.nq.gz
    ├── 1402a53c91bbfe6265fc5e41eb2eb718e7fa73f8.nq.gz
    ├── 1456f8eff33cc2f2eb6ab51a60a8efcc73f7e47a.nq.gz
    ├── 14ae3e1bf3301bb6e9791902960bc3913583d208.nq.gz
    ├── 152915df4c055c05bfb3f1d9748518cdf4cced8f.nq.gz
    ├── 15e9dae6f566b3367b504bad28cf4f1219a3fb61.nq.gz
    ├── 1643bbc3926820693ea5ec399f28ab6d8abc2921.nq.gz
    ├── 164f8e44be899535f0b530f8c2a4adfe3f6abd04.nq.gz
    ├── 16f929d611eeafefa3f3f66c00230d1b419e5a77.nq.gz
    ├── 179fd607d4df19ab27bfb0e4deb17f20cd4ac561.nq.gz
    ├── 198f08827a1c91b7508c81cb4e60e784d2dae4ad.nq.gz
    ├── 19edea32b658bfb2203ee7aea2d148d2a180917f.nq.gz
    ├── 1a1eec3f38265dabaa066e3f1d0ee0a462d775cf.nq.gz
    ├── 1a541f7b1c8cc5dfd34ba240cb1c2d6cb04c8abf.nq.gz
    ├── 1d1097a8220bbaaa60a782a4570785a9b6650fb2.nq.gz
    ├── 1dcb038397077c9d48fc740a34bc302774f72a90.nq.gz
    ├── 1f13715dc40124fbcc73eaea9c08a40e5528b9b6.nq.gz
    ├── 1f242bc2553743bc294592a3fdc247bd52506ea8.nq.gz
    ├── 1f2c9f240aa6107ff50d97d744fe34c6375a3175.nq.gz
    ├── 1f734651757ba8ee323a251795f6bbe94f9eb6b0.nq.gz
    ├── 1ffa5bf8b6b8a5d32c44709da3f940b6943e769c.nq.gz
    ├── 2018428443a4ed3b6f9b583bf18c146b876a3cdf.nq.gz
    ├── 201af2e09190b7ad8e4402079056ed683cd3a0d3.nq.gz
    ├── 21074338da1ad259a5b18838df0862af9b86868e.nq.gz
    ├── 213c960d895d3deef4e464952117b4fdc0d5f107.nq.gz
    ├── 216eaedcbe282347403d57e67a565edb85c82531.nq.gz
    ├── 21b44db870bd2aaa20b5d5ddbcd1e8bd08344b27.nq.gz
    ├── 2275edf80b0b54ba8da431738be93d98583fd7eb.nq.gz
    ├── 228c1b4bbce8eff22940ce185795dc6b2edf2348.nq.gz
    ├── 229d6b474eeb0c9f2a0a41f24e68434a856f82a1.nq.gz
    ├── 244f2d045eff02b93272e48002afcc0e720ec21d.nq.gz
    ├── 24d575c814e1c79d1bff2f13aeda49b7f415e894.nq.gz
    ├── 24db2a4a3a5baede3f590b70503fc917a17b2cf8.nq.gz
    ├── 262679aeb688e7ec59b23c6b7d073dc35e6eb4a7.nq.gz
    ├── 262b0490fd46dfa0a41b3b481511883a0672e871.nq.gz
    ├── 26806220ae5abe4e3bd83c91f8664b988ad3f4d7.nq.gz
    ├── 278c2281825c4356995452ce8ea53e3eb0006ce1.nq.gz
    ├── 294a385c78da5d23b24e9297b24fe47249961833.nq.gz
    ├── 29722c1b523b4a78455595877ce947a17a955fe5.nq.gz
    ├── 2b0c977b9ea0fb90df665f62a80fddd086696a09.nq.gz
    ├── 2b3c4bb4abbba467eb068d39827c94ac0ae23ab3.nq.gz
    ├── 2b756963e40f7f2d660fb2af8d8d252f76bd2ccc.nq.gz
    ├── 2bbe5480a63235bae71e0dcbaf931529ce683102.nq.gz
    ├── 2bf85bbbe41f94872f44da125578c7f51dad9fab.nq.gz
    ├── 2c24ad0fa86bae8b124c1a1cc9b9f036fb600007.nq.gz
    ├── 2dfab38b25cd2355578bce36283abe3b36a3f7e0.nq.gz
    ├── 2f0590a6243e83d51c6922679ba6b45d0ef69f7a.nq.gz
    ├── 2f505d50db7a62a390f0a7728dee28f7dc62bc83.nq.gz
    ├── 2fff4b7c872de1e54fc74834d5c7f88815afa30a.nq.gz
    ├── 310b75b95b1c2c23fa46c89b00e654cc26de241c.nq.gz
    ├── 3126237376fdfabcde6d9a0c421d59a752eec41c.nq.gz
    ├── 317d3e76d14e41020a0d31e9d4a4b6966b322bd5.nq.gz
    ├── 325a54a19618780606d14f8f287a9e33b68adb27.nq.gz
    ├── 32a7ec1a7e69ba4738ddc60fa921b247cffd1923.nq.gz
    ├── 32c9587499d6eed5ee002c6831bed75c35ee1e68.nq.gz
    ├── 33262b0bba24e10e2433cb506e3a1ea93bbd757f.nq.gz
    ├── 332ff5af2cfcae0013021e638d3e8fb1ff7d6361.nq.gz
    ├── 33584deb86cdd3d9fe0c74fbb4ad74cab600468d.nq.gz
    ├── 340ecd4dbf03b6b36dbbbfd248ad8257d53adb3d.nq.gz
    ├── 340f2c3e086a8ec30bf154dc05af9e467a26dbd0.nq.gz
    ├── 3428be9b4fd850c81f96509a23155df73cac8301.nq.gz
    ├── 36cdd52dc31241a2c33094548f93340462fa9b5d.nq.gz
    ├── 370b3c9a7c333e1cae32c906cefdd78e46b39119.nq.gz
    ├── 373e1a7b721bfc4077dfdabb42c702fd5ed24e6c.nq.gz
    ├── 37763d718fd5ba82b361039b49d87880303b2c90.nq.gz
    ├── 379972cb3606960b09517128b8c3b7a2fe1f6b78.nq.gz
    ├── 382409436fe3e0f2509e31a1e534fa76ab723fd8.nq.gz
    ├── 38d79fb3bd35b69af9238ad6453ebf61701770a9.nq.gz
    ├── 38fabc0973a35385088a98d9b3ffc66f0ff48062.nq.gz
    ├── 39c2a06b126e498ee7e260d05e2432406baf3b3d.nq.gz
    ├── 3ad286a36053d264ea2efb890af4e466ac07dbbc.nq.gz
    ├── 3b03b43e5de9152eff9550db7701b01682649f03.nq.gz
    ├── 3b067335b8181ebb671dec9e40bc25440d25ab63.nq.gz
    ├── 3cbcf6d7082bf8591a7679de65270adb9973e94d.nq.gz
    ├── 3ccd28c5c243f49ee1e8caf1c3de63917662ca6d.nq.gz
    ├── 3d57dd0eb909d687d3dfb74659151c0783a79e98.nq.gz
    ├── 3d62be8c55ea2bced6d5bbbe9f7615c98d02e509.nq.gz
    ├── 3d69556ffff62403e226bedc66609b76da33290b.nq.gz
    ├── 3df849921d29f0211826947b3265a828301f229d.nq.gz
    ├── 3e136f9dc40e02db99955c6172cb8a5afb01fbff.nq.gz
    ├── 3f0b72cd8c67893bc7eab4f7a0ae8579a7f6739f.nq.gz
    ├── 403aaaaeef64a0e20ec258e98d1148cf372df623.nq.gz
    ├── 41070a0350a4b36737f7550c014cfff24b3e94e9.nq.gz
    ├── 411408932069cf806837b6cfcf4774bd0f750753.nq.gz
    ├── 415d5faa9f57d0eac34797f50b4694e620cdecb2.nq.gz
    ├── 4249dcbd6bcb66e8f09754cd29022248aecf4648.nq.gz
    ├── 42b25d5757860b4060bf1df1b6936c6e0f3a8e36.nq.gz
    ├── 43532b7533b1b80806b5752723f90c97ce76602f.nq.gz
    ├── 43f8881cfcdc21099fbc355dbdb1d1abb4994233.nq.gz
    ├── 4403d7ea80b7e4bff9649b8336d3e040536effa2.nq.gz
    ├── 4423c41a27e5c0b8e6ceb5ceb73cf31d048ca372.nq.gz
    ├── 4449175b9ae5a62cc042f493f5abe4064584355b.nq.gz
    ├── 44c6d090d174af76c39e69beb7c422ef3359b1bf.nq.gz
    ├── 4516912dee614f5b4f822fcd3cbf5704f42c48db.nq.gz
    ├── 4525591b428f1ff0ed6d43b886aacbd4e3688c80.nq.gz
    ├── 47129b7719810dde1e70a0fa86d17d44942199ab.nq.gz
    ├── 47d47276aa03abe2326ffb48371c608fa9f7cb95.nq.gz
    ├── 48ef2791fdc81e0d8b7232c2b51c6c4cc8be91c0.nq.gz
    ├── 49ff6a873985369d5b17524dd06978beb9c019ba.nq.gz
    ├── 4a60ed2f2b9d98dd9e8a8d68ddba36bd1baab125.nq.gz
    ├── 4b45236e23e17d164eafb8c62321160c92f1749b.nq.gz
    ├── 4b8634c16621cbfe44658c66ae70490dfc39d094.nq.gz
    ├── 4baacd1ea7f1d8f5b4eeeb03b1f4dd308fd35db6.nq.gz
    ├── 4c340604d6b3bbd11f5d4bad96f212cb95ecb1fb.nq.gz
    ├── 4cb90a17d86eeacccdcc185787e62568f70734cb.nq.gz
    ├── 4d257f7eabd5b309995a7cb503a666a1be74e21d.nq.gz
    ├── 4dc8c5aa941a69201996042d438e44f0491f3a49.nq.gz
    ├── 4df681cf44b5f6444e9684b2285524197ce7295d.nq.gz
    ├── 4f3f94a7e37fb9c87cbb23ed5ef431e1df48d2f6.nq.gz
    ├── 4f84583169000dbcb6a285417b0f70d98eed49cd.nq.gz
    ├── 4f9f20608e89674bad31a1da3c6a07e4efee00a9.nq.gz
    ├── 500a150201bb6dba75bf10f6691591d5880f7d71.nq.gz
    ├── 50c9c98220b294d50bca767bf9b048acd69910d8.nq.gz
    ├── 515e5e7903c6c0c189910bc33b24d179d23b00db.nq.gz
    ├── 52861c076afce1e75c2cfcad2b943ef689eee637.nq.gz
    ├── 52a1f9817f4fa7f68650a722c378bd6e061bcf44.nq.gz
    ├── 536a321f06c2272fe4b54a56b849603ad18923cc.nq.gz
    ├── 53a22c3556dc1ef79d972b95f523c21b3b61f0cb.nq.gz
    ├── 53cad668e27084bd6f3ed84dd0bc00038fa8cdd2.nq.gz
    ├── 53cb0b6f88e9a7609ebe0d99fb4f83c0ecea919d.nq.gz
    ├── 53f997cf795005be39aae8e566debdcc50810825.nq.gz
    ├── 542b6a31e1c63c73bcc4ee48dd3dec24b03fa5d3.nq.gz
    ├── 54ab0f6ce9db553c03817f7927d13a1558b98f77.nq.gz
    ├── 54ce1a5b49597b5eaa3ea6d0507001d2d300792e.nq.gz
    ├── 56d936e1bc203ff9fc896907c307b5e075630b64.nq.gz
    ├── 573382ea256e39e301802bfc203a3100d791c441.nq.gz
    ├── 590105d6275769cd9ae0c56b9442d55fc49c6304.nq.gz
    ├── 5946aa3277e1a66fbbdd7cfb93517a0e34a14637.nq.gz
    ├── 598c7bfe5eb91c84858bda9155b00dc659196ac2.nq.gz
    ├── 5a36a656d61b52123d540b61a6fa1d70d768ac3c.nq.gz
    ├── 5b080fa766b5f3e73250e55f64a5559267bd1526.nq.gz
    ├── 5b2a5d6d34cb173e581072bb7fd926681eadd3dc.nq.gz
    ├── 5b3e26421b0c3838e4776201cf28f7ad57ed07d7.nq.gz
    ├── 5bc713aaef69a8e6c500257a892ec0006a4180bb.nq.gz
    ├── 5c355aac8d6118a7666ebda92c2284bfe4691555.nq.gz
    ├── 5c41d94657be6f068caf76fa28a24f7a7a910922.nq.gz
    ├── 5c7a7bcd016d1b55d69f4c652b81f7fdb9edc385.nq.gz
    ├── 5dc1101b6f0d89cc8526e810f6025762cb83d2ca.nq.gz
    ├── 5e467be2e3e5735461b3b1676945c1672897db7a.nq.gz
    ├── 5e56a9fecef6431ce37e5efb42fc099a0c1862fa.nq.gz
    ├── 5e84f5c3637a8cb22ff430704ed866ec24001c30.nq.gz
    ├── 5ee38843f4bce4d230670560c8cad4431a5c7fa3.nq.gz
    ├── 5f10d8e61671b80f9c5a30108f30da0c5e257f07.nq.gz
    ├── 5fdfdb91efad742cf4a6333f030b86f9e13af6d5.nq.gz
    ├── 5ffb1aedf23a0dd4f66b1cae49e3f73b2c2c761f.nq.gz
    ├── 6195c6573cf5f83abcc961c267b167bb644641ea.nq.gz
    ├── 6198d85b27f592befb5bfdbcc46063c8e744ea45.nq.gz
    ├── 6339ef08aca0873a7998d52b6ebec390a9bf1487.nq.gz
    ├── 63e9710da1fcaac4afa14b0c6e398ce2a7c76a1a.nq.gz
    ├── 650acf0d73a5f40cd99af6b60df0968c34e2b84f.nq.gz
    ├── 656032688dcfb0dbc3b6b826deeb430b928128b2.nq.gz
    ├── 658cee4c6c60433b117d285eabbbd3788163ae4a.nq.gz
    ├── 661167c9ca94d11acd4bb1b6b5cb71656d1efd12.nq.gz
    ├── 6699b458f96eabdb3d8c00ebcefb2d302b194e69.nq.gz
    ├── 66e12ff4fbf9b16711325f9f9f810630ba22b430.nq.gz
    ├── 6752dde295871c6f5117f49806ab15f357f563d8.nq.gz
    └── 6805960f255d6dd3f2704fe19030466b9d8b7ec6.nq.gz

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

[explosion/cython-blis](https://github.com/explosion/cython-blis)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
