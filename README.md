# Repolex Knowledge Graph of huggingface/tau

RDF knowledge graph data for [huggingface/tau](https://github.com/huggingface/tau), parsed by [repolex](https://repolex.ai).

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
rlex download huggingface/tau
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 47610d3ed71deb70b07443a8641588ffc9c8ffc6
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 47610d3ed71deb70b07443a8641588ffc9c8ffc6
│           └── chunk-001.nq.gz
└── blob
    ├── 00f0e94f1a13f1f095d154aa2c1d5aae591127eb.nq.gz
    ├── 01243bf50dd315ef4126af7e1d66b32b0c111d3e.nq.gz
    ├── 026fb9454e4858fd71a09af9cdeeb507f8ea5497.nq.gz
    ├── 02bafee3ab1caeaa505e701c725bdff4d0827d1c.nq.gz
    ├── 038af0c31625761e8fc3b85679a955f6d9e9a01b.nq.gz
    ├── 04962047ffd3e69b9ccaf1b2c00871f98dd76615.nq.gz
    ├── 057531c58301a452f5ed7c21fec139c17f4436bf.nq.gz
    ├── 0607df456f279ec1efc8377a1f9e1218867e96e0.nq.gz
    ├── 0634cbc1d39318fe2e87f774c65f7c16b4b39d88.nq.gz
    ├── 06de641676f02aea1c8b9e7a881802691d0fd2fb.nq.gz
    ├── 06f45ad8ecf4e790a4efabb673fe168ab57edc8a.nq.gz
    ├── 0799dfac57a08acd9dbd846e34193c2f5b7262ba.nq.gz
    ├── 082036e934d7638583d3aa929bea045f29a93a56.nq.gz
    ├── 09b137bdb89523ca863c4dcbe66621f3839123ab.nq.gz
    ├── 0a3c239d29c704a133c4877615c2499a755b1798.nq.gz
    ├── 0cfae80c8549ceb246fdee1540b815e4e2369eef.nq.gz
    ├── 0d3a462d46fe925f90839418a55f6eddaf203f27.nq.gz
    ├── 0de9d059034f46b0d50e85668cce5e3104133d85.nq.gz
    ├── 0deab0fd7d4db0bb9d6598d5f845f6d2da90b301.nq.gz
    ├── 0e55a43c643cb88c9c7c571b13fa2848971d711b.nq.gz
    ├── 0eca56b183cb6cc99d048bc67f6e6401434944fa.nq.gz
    ├── 100c4144602862780b649cd2593afb5532798984.nq.gz
    ├── 1029182abb8f738a7b33218e39e39900b80c5d21.nq.gz
    ├── 1106555f5768bf98a820fd37cc88628094e2fe8e.nq.gz
    ├── 11e5729d5c724a1c456674c3a2e3465c9b5ec3f5.nq.gz
    ├── 11f556e49f7999ed0ca452dacb5f46768e3dd2b6.nq.gz
    ├── 121bc0111c3cc2fc521d995d521b08ef089295e6.nq.gz
    ├── 1330d3199c29271d1fc425412b9bcf2d5006fbe6.nq.gz
    ├── 13510ce2cdd2936aabe89e5edbbf1c23b5a29b70.nq.gz
    ├── 14a9ddbb2f4e94861ba0b4afd9f45c1c29d3ae18.nq.gz
    ├── 15487681ddb6b74f2e8c7f2852740a8530bc4cb9.nq.gz
    ├── 15843bfb400e5672fd89faa0e586cfd05be4eb1c.nq.gz
    ├── 159166149be70658e91361c5a1cff397e526066c.nq.gz
    ├── 15f7bdd7916ac5fca2274ad5d1239bafe0f0f5a2.nq.gz
    ├── 161277b38595edc6a69192c31e701c467f5033c0.nq.gz
    ├── 16526d3f4076007c78c7cdcb4c581e70b472705f.nq.gz
    ├── 17cce4999c5f6fba45120274f28df8ac72ebfcec.nq.gz
    ├── 180ffd3c796beea7e3c2852daf5e9e3edb19a9b2.nq.gz
    ├── 18de9d179cc7cfdd5684e8f42f186a0ba5f13d32.nq.gz
    ├── 191b57805185fbf64c98e01e28f7ab6d9f389c3b.nq.gz
    ├── 196dcc13d15f6c0d5ddf071e9ab128c7a51d646e.nq.gz
    ├── 1bbab43e54db92ea6a17e954aba4807b69ecc539.nq.gz
    ├── 1bdbe2cc42b5878dd463f17c4a7b35d189d32d55.nq.gz
    ├── 1bfdfeab5ec88d77b1f4d15f33e6e322711c041f.nq.gz
    ├── 1c39da50f421b9663401a9907b71f478fe9b6296.nq.gz
    ├── 1cf7f6c02beace852afae8d8949d82fd79a54acc.nq.gz
    ├── 1d0556a91aaba6a8a56c5ad6ec8b2c6aac3a3b5d.nq.gz
    ├── 1d247e7bef02ae026ba65c29a0db96f1f649fc49.nq.gz
    ├── 1e9f05289c86f5cb7c598018ab615f4e7f5a5d13.nq.gz
    ├── 1eb69895eae36ff48fda47d8665cced3d60e10d7.nq.gz
    ├── 2030827663c392c8d95792e59e19174fe30dd8f7.nq.gz
    ├── 210f05e839a0f331b8952de6825aed40edb5ffe1.nq.gz
    ├── 218e788e6a6f9d512db99077864eb5b9ceaf37f5.nq.gz
    ├── 21bb7772d194f0d6da5d3b3d0754ac7789394e41.nq.gz
    ├── 22253a5b15e5c9b4b446d59ef3a6e472e13fb163.nq.gz
    ├── 2232fb31b8690b8d06e7d22232a42fbb70467319.nq.gz
    ├── 22e905c126ce532d850085fe1eba73b7dc899f98.nq.gz
    ├── 23ecb44a03dc73657bfd275aa821e940696c9bb2.nq.gz
    ├── 24332433f581659e181edad9f718e636ed653ff4.nq.gz
    ├── 249ba5d98eef1e064536d384d8df170dc8fc48bd.nq.gz
    ├── 24e12ec2ffc2a05d810dce4a3c9b35c1c504eb3c.nq.gz
    ├── 251475d45a32ce432ccc93a9477a7f3d881dfbef.nq.gz
    ├── 256a848ea5728a62c6133901b825a65da86048c6.nq.gz
    ├── 257fbc7fd22332457cc3c0128da97be9e979e821.nq.gz
    ├── 25be7207f7817b05a34fa90cb035487f3390d642.nq.gz
    ├── 25e15e9e2062ac90e15df161d497af897532928e.nq.gz
    ├── 26bec6c58b9b154c719c5ead1d38b56f16b274a0.nq.gz
    ├── 2739100214232e1a5f4b0242ee744ca5c2d50f16.nq.gz
    ├── 27b658c5e27c1f3dcde13aadb3e09426a0f25d53.nq.gz
    ├── 27f8b9e3689e36abe83e08bdd36722a720e247e3.nq.gz
    ├── 2890ae1abdfbb8db462f68e4812f5b2f313f74b1.nq.gz
    ├── 29863119d4653b1696bee12512534e1ddd85756b.nq.gz
    ├── 29bd5231577afb5e31a8fdce04e635d37b305d03.nq.gz
    ├── 2a3ef24e4118b0e1869cffa748f9ebdf25b49a4a.nq.gz
    ├── 2a5c674e3f1b036d7577b0d9f08f7cf97bbf79ee.nq.gz
    ├── 2a69e15fc4a3c273427d986a49ff72105dfa0d88.nq.gz
    ├── 2ab237c2adf8495ab3d0543b0391bca9e685e4ab.nq.gz
    ├── 2b2fa2e7381ca0849280a917636d5ea13d22600c.nq.gz
    ├── 2c486435b7ec11783d6c21cddcd1fdec879ac72e.nq.gz
    ├── 2cad9c4e9053dbb13e4f679de26477bea28e673c.nq.gz
    ├── 2df283225e63b9a9c870e7bf826738af1b119fb1.nq.gz
    ├── 307238df6dc85478145ff458af2e1726e18ca541.nq.gz
    ├── 310ec5e9f694be3cdbc6a4b4bc5ed3f244fb4511.nq.gz
    ├── 31224968d83de4683baff4574bd282f0da94f499.nq.gz
    ├── 316304eb949b70ddfd19ca52c79d7789a7aaab95.nq.gz
    ├── 31c91609aab6e15827f650ae47f26416814632ed.nq.gz
    ├── 3216dd4701881f15a3c7aaa66452689692461f52.nq.gz
    ├── 326f86d07069dfcaf23df29089559484e1876601.nq.gz
    ├── 32b6aed6fbeee0eaf66c81f5d3615f73efb94960.nq.gz
    ├── 32d873b2935b5f6ae023bc76b3181ae59cb3e7b9.nq.gz
    ├── 33199d250eb6b016ed4b911723f8b3c0e76b707d.nq.gz
    ├── 34b4bd972aaf8f647c7e5ff3b4c4bab0bb33ef7a.nq.gz
    ├── 352cbf996b29e837c6b3f3c372199596e69bf44e.nq.gz
    ├── 355e7b6a1bf14fe99a29221d6631f507f0db4612.nq.gz
    ├── 35803515a144ed08e4750a5e78c085109cc723f8.nq.gz
    ├── 3638413517968500571d64b7202b363b3bee92ef.nq.gz
    ├── 36a3879278f95f47862bcbb42b8936ee4d082bc4.nq.gz
    ├── 3851f949423c2a21afea74c88a67f0ee826f6f70.nq.gz
    ├── 39ed4a83a0d0ad31d83225066f571715a4233e39.nq.gz
    ├── 3aaf2bd8885cea5584fd1c54730d0875a646ebc1.nq.gz
    ├── 3c162606219cbc0163f029f3e3ac66ef0cdd8fc8.nq.gz
    ├── 3cef7036dabd809ea44c2d07673e8261768d260e.nq.gz
    ├── 3d4968c2aa406d6a2e1d57ba094b9066c07c87e9.nq.gz
    ├── 3d511b805a607321b099ddddec7e0d3416fe0396.nq.gz
    ├── 3f1d6442cb306edc3b7451fce4bbe6536877693e.nq.gz
    ├── 3f36a75fd8be6fa7fd62de3ac641b98de9aa3bf7.nq.gz
    ├── 3f399b3bcfddb091e23c2cef05f2ec1e85e694a7.nq.gz
    ├── 42ab95c58912edb85a2b041f62425fb998adf830.nq.gz
    ├── 43c5d3c0c97a9150b19d10bc68f4c9042c5034cd.nq.gz
    ├── 440737b1d5ab6c376ff208a5c94e41bea6bb314a.nq.gz
    ├── 444c0afe22d2513ab3e5bb1a051cb49e207b4ed8.nq.gz
    ├── 446a973443e267fa10a8b0dbb757f971d52e7c8f.nq.gz
    ├── 457f54a278d444981d702b69cc0a9a0a5481e51a.nq.gz
    ├── 4609df46694aa46795132c474682f1c80c6b66a4.nq.gz
    ├── 49c0036c94e6427a87af9ad6a3c52a7cdcde7b98.nq.gz
    ├── 4b586c13728ffdc922149804f2b44e7d5f32f7c7.nq.gz
    ├── 4c45341e8bc7af7b3bf0507380ddb5fd6574afc6.nq.gz
    ├── 4cddc5398bed685bb2d09f5b6ccd4df19c379676.nq.gz
    ├── 4ce0dcefb3675dfe566e4d9140701115cedbba11.nq.gz
    ├── 4e4e4b1226789228deb7ed5b434a49c7ffc51949.nq.gz
    ├── 4e75f7929bf8cdfebfc8360711259397e66c86b8.nq.gz
    ├── 4ead48aa63e3c50e9ddb7dbb02e2920503b1a658.nq.gz
    ├── 4f7dc7aff410896c447ffc315c9e9eeb73d669cc.nq.gz
    ├── 4fb8a22e671437c37361c96a9610744f2a413189.nq.gz
    ├── 4fe3b8b10ab03f76c53981e0bf77dd7382e8459e.nq.gz
    ├── 504d8dcc9cab507aea24fea07e24f782b5bc041a.nq.gz
    ├── 5079c107b827d87d85b5c1231cd55ac98a319d4c.nq.gz
    ├── 5090bbaaeaa50eb9f8a84a0bed9d285c8de087cd.nq.gz
    ├── 50af7320da7768ab79e23403ec6bf24501fd7415.nq.gz
    ├── 51240e5afd01971edc5122c1d964792b354ecd0c.nq.gz
    ├── 51a035ee33f60f8d2824ff3c751a15827a6a11ec.nq.gz
    ├── 51ce5abf8e67913a31fe3d0b59b69289d977e76e.nq.gz
    ├── 522d374fe2bc81ef92ad012580934179e636f07e.nq.gz
    ├── 5283b29a01ec976b5d0f56fe8d4bc69919ddfd74.nq.gz
    ├── 53034cf830ea2ba283da2f62c0dbaba7d9304fdb.nq.gz
    ├── 53b34c4b014f9bf5dc1466655b508fc079f3f452.nq.gz
    ├── 5441777a8c8f7987a6f21697e3ff0e0541abd1ec.nq.gz
    ├── 553fcacd0aa658ba5119bc4c4d434dd6e329768e.nq.gz
    ├── 560403bb21ebe85bffcb194f384741145d2323f9.nq.gz
    ├── 56c033a0ce9d5757599574faca184f848d8594d7.nq.gz
    ├── 57248861c2daa7ad066a9ca7ac55b236f6895875.nq.gz
    ├── 57606017e9d1a665934db29a7d92397e8065ad18.nq.gz
    ├── 57b05676121ed74eb1780b03ace1cf90affba8cb.nq.gz
    ├── 59ba6abbfe01d8d0c940180f38d125f9ce724749.nq.gz
    ├── 5a2a0328c6b3a8c40a98e47c79f1339774a6dacd.nq.gz
    ├── 5a33126559885f7e82f53ac7b351ee09b9831b92.nq.gz
    ├── 5a4f03de9d58a03cdc57739ea01f4af85109bc66.nq.gz
    ├── 5a71ee42e632c9a2b2999172c64b13d8ca088371.nq.gz
    ├── 5a85f750820c0e764c1e47b3a27932fa6eec769d.nq.gz
    ├── 5a94b590a66b99d440ea2d48c797441aa3042921.nq.gz
    ├── 5c21eb6c43ea546588421c145a35f148e4cb5688.nq.gz
    ├── 5c44851dbc7d2ebfd16d1f588840dbe097b6bd10.nq.gz
    ├── 5d64ebd400fe21788647d48dcf14f07b0258f8d6.nq.gz
    ├── 5dc315ec31baa7f143a83ee17056d158e08bd27c.nq.gz
    ├── 5e59d6d37aeb46d0bfd519b6b59cdcb5fdb03181.nq.gz
    ├── 5e8214d7e33e897ab2a6b8d6132bcfbffb77e6f4.nq.gz
    ├── 5ebc0efa17455fb69b47ffac8c2d3a4411a2958b.nq.gz
    ├── 5f2642248a215acf95f35da97931fa01a035816c.nq.gz
    ├── 6026c7bb027ae690d1e63d52b8b2973fc29d417c.nq.gz
    ├── 61b4489b1f200472d1e96be50f3373b39eceeba5.nq.gz
    ├── 61c419e90011fead72e9513671cb6b48cd8b2bb1.nq.gz
    ├── 6280ed564ca9bdedb349d5ba534affcfc9b22a49.nq.gz
    ├── 62d1b08b379704e4631822226916c683324d8b4f.nq.gz
    ├── 62dd97858b800a522ca6034ff977b97834d54317.nq.gz
    ├── 63c82e76bb6a4f05b9ea67ad29880ec1687e1cdc.nq.gz
    ├── 642a87803fb7c15b01f9dc056d984402bda94aeb.nq.gz
    ├── 65e16853d6073359032ad4c9fc50500f5b6a29e6.nq.gz
    ├── 66f451afd8311f3ca3f3ac7eaab7877a579b79a6.nq.gz
    ├── 6714c454615ee0fd0ac2f23548f663c9466e4a6b.nq.gz
    ├── 699f8c00763383109ddb73192a6428d071935e67.nq.gz
    ├── 6a30016585eff4259608c798bb49af0ed00c7096.nq.gz
    ├── 6b5fc05d7e3b27c984c0f234e6d566f0fb3e1ef5.nq.gz
    ├── 6c7da0b0086494ddc3afb5c019971a76e4efb3ab.nq.gz
    ├── 6c8d4286777327274873aba287512ac0be17b475.nq.gz
    ├── 6ca92c4da362edd1b224248bc4a61e72d99145d9.nq.gz
    ├── 6cad6549627b57e60827a3dcd031179b3dec8aa0.nq.gz
    ├── 6d6080b3ddfe440d086332a2590a9234dc5a51b3.nq.gz
    ├── 6eed8dc1b96f2feab8451be1d3d4f62a758d6319.nq.gz
    ├── 6efb14d2592d2327a2d3d15ff0c0cec51faad1e7.nq.gz
    ├── 6f3d3f7fe0747c8f45779b62a1e2d90f58af3861.nq.gz
    ├── 6fab89472519bc92c24a8fcacb240fc0ecbdf0e6.nq.gz
    ├── 70c8fca4681a423be328903d3ebcc6bbeaa1a138.nq.gz
    ├── 71409836799a3687fced1fef85b903bd216b9485.nq.gz
    ├── 73088ead4b7a2fc6dcffccb3d3a7c72c4b7498af.nq.gz
    ├── 731866f5346222fd22fb31ae128208473a4d131f.nq.gz
    ├── 731a9c1a848b86c3cf4455542edab2209ef3d38b.nq.gz
    ├── 73d7a39c8cfccf44526a8d58db34a9bd51d3fcf8.nq.gz
    ├── 73ddbcbca68821bdcbc09ecb69d03a4b5db8c63a.nq.gz
    ├── 740b88d401aee228966088bf4f88fdad2bab5229.nq.gz
    ├── 7439024f14cfb29933a468bd588f16d2cce7555f.nq.gz
    ├── 74ada399fe92fcc4e834cacdf2fed8bfc9c6f07a.nq.gz
    ├── 760a1949d7ec1fae76b99103c22def997344e57b.nq.gz
    ├── 761c3f80ad0a172165a3d7147e59bdaf081c9717.nq.gz
    ├── 76f545d40101ec8d8185150685e8b5de6a53917b.nq.gz
    ├── 7791cd76312e03798191ba9d1819eca489377e13.nq.gz
    ├── 788c9e77f14c2165f37a8513701462b884376b6b.nq.gz
    ├── 791f979870c93686469dec7100d990a6f2aa4695.nq.gz
    └── 79382714834ab67eee96c16087556da230ad479e.nq.gz

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

[huggingface/tau](https://github.com/huggingface/tau)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
