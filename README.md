# Repolex Knowledge Graph of microsoft/RulesEngine

RDF knowledge graph data for [microsoft/RulesEngine](https://github.com/microsoft/RulesEngine), parsed by [repolex](https://repolex.ai).

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
rlex download microsoft/RulesEngine
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── b35f2be09bc1fd6eb0bfb78e928dae48b4d2737b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── b35f2be09bc1fd6eb0bfb78e928dae48b4d2737b
│           └── chunk-001.nq.gz
├── blob
│   ├── 0005978a632a47cb6c00612b743618f3fafb7a96.nq.gz
│   ├── 014ba7ebce9025ba43cfc63d5c952222ccbbb94a.nq.gz
│   ├── 03d7cac34038a9a956c19638c5ded236dc95aa33.nq.gz
│   ├── 043e8d4e1d6e1f7559899bec199348b78e3b94dc.nq.gz
│   ├── 04cb808296bd07a0752b813d48e0993003b74376.nq.gz
│   ├── 04ceebf1fe9c39d9ef72510b5f2d3b3cb61f20e1.nq.gz
│   ├── 051e938f226e53497f354640a9192fd4d5f0de24.nq.gz
│   ├── 094c0609531057836c08bb4ea35e5001a4f9f54b.nq.gz
│   ├── 0af10c58e43cc7fe489041c4021bc40979af9e60.nq.gz
│   ├── 0e3029adc6c9474c5f3ef78694cd2b0dd8393533.nq.gz
│   ├── 10341c93a5a5e47a0f6a5cebc30a6533b5a88d71.nq.gz
│   ├── 10367fd3f555d2e2921e1827dddfbfab3f169ebb.nq.gz
│   ├── 10d64aec5f84774d167afa067f579d17d669f36e.nq.gz
│   ├── 147c6c7be8c4f4dcaf2578ed669ebea095f13d11.nq.gz
│   ├── 1850ef7123a1df3b14095c5db364c1834f534ba7.nq.gz
│   ├── 1899f9db785f763cf24221d85f9879f10d6e1699.nq.gz
│   ├── 1bda149020b90555868e91885d3773bbc53cd1c4.nq.gz
│   ├── 1c8bf62fb85a76efbfd7e50454067796d1c3a9d0.nq.gz
│   ├── 1d4e0ada77c24119ae70aea5fc1ebbd74924e763.nq.gz
│   ├── 20462bce1b7f121f031dd8fbdc5d4a3465f67608.nq.gz
│   ├── 2089fdbdc7af0833adec431c1883d0abdb9c1759.nq.gz
│   ├── 20aaee2a2693696b96a27fd23fc8b75e6a203fbf.nq.gz
│   ├── 2312216353f0db594abdbcff632c411833b40154.nq.gz
│   ├── 24132d3be770caf6947f1e2b0c2756bd8d3fd245.nq.gz
│   ├── 27ced41be79ca17a767fc849faad4fc5c938e22e.nq.gz
│   ├── 2b18655a4b5c65e0daefbba17babcad052d382d5.nq.gz
│   ├── 2ccd61bd882874ebd0928bfdaa221b3bdd4be64c.nq.gz
│   ├── 2db732a3ec1fe9fce9f7fad5e04d46c667205f4a.nq.gz
│   ├── 2ee4891e25c5830ad25a1dc49630a38d3f1726bb.nq.gz
│   ├── 2fd976719caa818cbb501925a1262032dae0c342.nq.gz
│   ├── 3213dd4a9bea0b2b795a86d859b03fa86b9418e5.nq.gz
│   ├── 3342c46c6fd76ea7c441315fe3326982f2f4c84e.nq.gz
│   ├── 35a1e59c062ab4bd3838f75a6be5aa86dbbb1865.nq.gz
│   ├── 374838044fe19c09a28e44fa321d3ae1e124bd2f.nq.gz
│   ├── 3812e32d5f226054645a48d97e7f07de247c12dd.nq.gz
│   ├── 3d0a262c659b6047e2d2645da4728f574aedb711.nq.gz
│   ├── 3dd210447a830550810328909e30a063009ed9aa.nq.gz
│   ├── 3e0fffcdedf38731cf2d833ca66d8b79929b023d.nq.gz
│   ├── 3e88f1c51f90e8e8e8dc6f270f6f096bfeadd7c1.nq.gz
│   ├── 3e98ca6292567f3855515629b9b62e0290aec80b.nq.gz
│   ├── 3ee98c30ec819a4e423c2c641aa0c1538c1212de.nq.gz
│   ├── 40e8f17bc2f9bac02b65893c0ec35199069473d2.nq.gz
│   ├── 41c8b114b78e4c1e423d4840ed0e99446162e30e.nq.gz
│   ├── 43b8bbc6e6e9388e0e831e057c624282b265fda2.nq.gz
│   ├── 4609457e1d55500453691c3750372285cf41692d.nq.gz
│   ├── 486d8eb42ab9a86f3ab75b7dd48520881cc855a9.nq.gz
│   ├── 4f196696f69196272c4dcc90df3145efb9f5ae25.nq.gz
│   ├── 5337ba6497838603d2392535b5322bee16320dd4.nq.gz
│   ├── 602cb98d3c831e7170ce825bfbe324329256923e.nq.gz
│   ├── 61a0bf13dc6f4e49a58e0f8d44ff627a060a6e04.nq.gz
│   ├── 62b62fc32a4db2667b2494e315bd92c80a99cee9.nq.gz
│   ├── 65f87117ab455e3ec2c508072e6c8f20b2f4cc3a.nq.gz
│   ├── 67f1a30d651ce696283f6453de431adfc5ba0ef1.nq.gz
│   ├── 684849787abba62228d9da33a4d918b57318dbbf.nq.gz
│   ├── 688e84a200538d56bf4e01124e843152e7800170.nq.gz
│   ├── 691603c333dd8502d6e38ae6c6950a2814c88781.nq.gz
│   ├── 7102930b9a22d9d248ab5d880998c18ae04c9998.nq.gz
│   ├── 72c774fa5e5ac9e89933f68647fb158aab591be2.nq.gz
│   ├── 74abe2b5d02ec5c79abda0645f141fbd9a6570a9.nq.gz
│   ├── 751c66e3693c7c35717f18cd89c4cd4c3412557a.nq.gz
│   ├── 76d3c5f97b4f43b2200e3e2eaafb21a021750263.nq.gz
│   ├── 7723a71e81d9d5f30f51dd872f763d8115571058.nq.gz
│   ├── 78ca5cee0574d25ec4fbc8f46d12f958f78c3268.nq.gz
│   ├── 7b298310a096904d3e6099ed41b434d6d0ad4ff4.nq.gz
│   ├── 7dff47d88636aaf8abbfa0cb099f0bb110fbef16.nq.gz
│   ├── 8029fbf5ea9e3d80b8e00ab8194750f8f9b19fc5.nq.gz
│   ├── 82ae7363f783576afca3b17e3cc7d2faee5f9f10.nq.gz
│   ├── 854ea792aaa90da29a3977d7addf0ac9c76f6640.nq.gz
│   ├── 883ede87bb220dec8fd7dc564ecaf22969b3269c.nq.gz
│   ├── 88897fe175191d25bd4e9e3f80441b528d1fe08a.nq.gz
│   ├── 8a14cad32ec93a7fc86ea7051a744b4b31c3dcf5.nq.gz
│   ├── 8b988f5bf3d5c295e6b0abd17333d3faaba23d18.nq.gz
│   ├── 8d6648f48fc3a44dea99f6eb18bbb7ac254930ed.nq.gz
│   ├── 8f3327955959433a1915a7429cfaa94ec75dd25f.nq.gz
│   ├── 90677730b2f38c5c251d56db5ebceceed2545872.nq.gz
│   ├── 955bb7ddd768db316c3d7d67b1269a494140eacd.nq.gz
│   ├── 973222b24dff6de07e91a777f22c1a7159e00390.nq.gz
│   ├── 9a784dd5998f7b76039d0930a113ea8ae55d9cf8.nq.gz
│   ├── 9b0709db54d28f32a7897588efbe17608039683c.nq.gz
│   ├── 9bd0f53ade40e5a53969fa63d1d649cc75f3be21.nq.gz
│   ├── 9d341c878c31bb7940f13d41705dfe3ea752dbed.nq.gz
│   ├── 9db6203ec6498dcf690e4d4f7b0afe2da1a220d8.nq.gz
│   ├── 9e25bd70ee6c7963bef0274654d2271cc1956240.nq.gz
│   ├── 9e841e7a26e4eb057b24511e7b92d42b257a80e5.nq.gz
│   ├── a00f438ecc49f30af72326dd879ab8f692c71110.nq.gz
│   ├── a2c15d99bfe3078bd49d07c7bd41ccf52451a0f6.nq.gz
│   ├── a3586f67e7656b76b4c9f75762c80ce7883c0f9a.nq.gz
│   ├── a41b554119279c3172b98517c68e6072b66dd35d.nq.gz
│   ├── a9d216dcfc6de7c8f6b8512b33f54f8085433c8a.nq.gz
│   ├── aac2cd4b512abb5ff236cf3c56ac7e1e27c30cc4.nq.gz
│   ├── ad20e61c238e6ea6d7cdefa82389f33802a9b4b4.nq.gz
│   ├── af7ea1c9512f9256bf1caed5ac49ab08d7eb2526.nq.gz
│   ├── af906e594b417ede10b0ec2ffedd830871d5c56e.nq.gz
│   ├── b070975a2fdb7ee88f7c4c308c3ed9c0908e1674.nq.gz
│   ├── b30e3cf01afe703c00bd38daccc3be1a194d826b.nq.gz
│   ├── b4306ac2fec4765ca428e5293ded11f36557dc6d.nq.gz
│   ├── b500c72fea91be1ed72e214de881c99b415afdd4.nq.gz
│   ├── b682c5360c33c8b12ef01ac5a6048e3bf7faadf0.nq.gz
│   ├── b8a2ee51187898b8480d3eabb63b9aab9eeb5718.nq.gz
│   ├── bb06d1336fa013242e278df9fbc883a5a4f5fcc0.nq.gz
│   ├── bb37d79af522887c8da8b27c89760f5762f970e3.nq.gz
│   ├── be24265367b280dabdb58bed7ec72838daf1db8c.nq.gz
│   ├── c38bf4caa700662869fcb9fe2059e38f4208e7fd.nq.gz
│   ├── c4192631f25b34d77a7f159aa0da0e3ae99c4ef4.nq.gz
│   ├── cb0e99b89d149c800495fd9f4e0c7c8a81985bd7.nq.gz
│   ├── ce7be86d742b704f70e7a358a3edebd4dde8089b.nq.gz
│   ├── d3b8897df23cc0ea9d326f9d576c9ab56a926a23.nq.gz
│   ├── d8a9c256409d0250e73cb55e29448dd58f5cd684.nq.gz
│   ├── d8ca863a649e8ff0420ec37db0f76cefe066b39d.nq.gz
│   ├── d8dca9f778cf452f25bc3777fddeeaf34f3668b7.nq.gz
│   ├── d9b05acb4158abe94446ac2751f79c72eaefd01f.nq.gz
│   ├── de7ed2bbdeef60a61c74090e461f3fd16fd1bc92.nq.gz
│   ├── e0bba8c3886518332b724235b213db37a4441b9c.nq.gz
│   ├── e0c4934a5fcb14bbb2adf0751fffa05fea102af7.nq.gz
│   ├── e476eabb8a19743762814c91ee5b2dd6b7ae4df7.nq.gz
│   ├── e687ad241da6deb54c222487b165ef35cb801494.nq.gz
│   ├── e9fb8f764855d9349edd96f2067fc036a5060b3e.nq.gz
│   ├── eb026a8ab29ee7b22df02f2664e9a0d58df3d5c8.nq.gz
│   ├── edd4add0f371779633ccaf3d61bb8516f19ec9bc.nq.gz
│   ├── ef9081e85a61f4350fba4ec0e83c8be30f6359c4.nq.gz
│   ├── f1ee52ff75bab374674b1b41c9237138027db4d4.nq.gz
│   ├── f3eca82280f5750ce76bd908dc99ae92ebbf7b8a.nq.gz
│   ├── f46fafa4c6eca22bc737bd250bffd3ae03fd6452.nq.gz
│   ├── f5d49017901d080fe2279ea6eb89873d671b8ee3.nq.gz
│   ├── f60a6de6da27a3886ecd53e8679066a5cddfa8d4.nq.gz
│   ├── f7b89984f0fb5dd204028bc525e19eefc0859f4f.nq.gz
│   ├── f9ba8cf65f3e3104dd061c178066ec8247811f33.nq.gz
│   ├── fbad6130290b5728823af87ac336cb9d64dad133.nq.gz
│   ├── fc9e552b9d0d50cfb24c9b835b5a9dc5f0938eac.nq.gz
│   └── ff1b616d61500be07ddc699cd03a4954a1290043.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── b35f2be09bc1fd6eb0bfb78e928dae48b4d2737b.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 138 files
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

[microsoft/RulesEngine](https://github.com/microsoft/RulesEngine)

---
*Parsed on 2026-11-10 by [repolex](https://repolex.ai)*
