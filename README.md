# Repolex Knowledge Graph of pypa/bandersnatch

RDF knowledge graph data for [pypa/bandersnatch](https://github.com/pypa/bandersnatch), parsed by [repolex](https://repolex.ai).

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
rlex download pypa/bandersnatch
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6e27445dd55682505cb64454895a29c8d1e9a592
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6e27445dd55682505cb64454895a29c8d1e9a592
│           └── chunk-001.nq.gz
├── blob
│   ├── 04e5e68fe1675e59de8a2ba2faf32f2eeafc302b.nq.gz
│   ├── 0921b77cf8114440ad65c9fa627c9b5914b04fcb.nq.gz
│   ├── 09d8d3ca20b0b711d69b3f2d9953d944f0de81b3.nq.gz
│   ├── 0a385b0bd6185ccb97850376443e1ec45b4b0a62.nq.gz
│   ├── 0ceaaad6f7472d3950aaf43f7ace8ceddfa9f155.nq.gz
│   ├── 0d72533cd03e49a29e80e0ccfdf93f24b3f7ef26.nq.gz
│   ├── 0db5c707bb37833cd487d35b968c83c2bff3c07b.nq.gz
│   ├── 0df4c553aff159d4bec952a48a3bec9cf040d92e.nq.gz
│   ├── 0fd3f0dbc7d56041579662adc0f76cf9ea80b6b2.nq.gz
│   ├── 103e7136605f44ede6332dbc2e6a6ba9ecd68dfb.nq.gz
│   ├── 10b474c995dc868f9ce5f03f9da647e7919cf2a6.nq.gz
│   ├── 1415a729909af344a4495904a5904ea6ca5275d4.nq.gz
│   ├── 1c9ef1f2d83e16136db469c78ffd2c7ba6a37634.nq.gz
│   ├── 230bfa944b432971477cb730fb05f103b3b6945b.nq.gz
│   ├── 26d529b509efa94346f72f4dd6597817426a914c.nq.gz
│   ├── 27a9c9adcc4cb0115f8e6fe9881dd195a676e92d.nq.gz
│   ├── 298e231a59c26b6a33f24b0d17d95e0216d1e94b.nq.gz
│   ├── 2afbf0f56547bd7201931d78750fd908f448ebf9.nq.gz
│   ├── 2f0385e513aee99ffbfee5b22a9fa773ea6bbf68.nq.gz
│   ├── 2f9f8b23c6a7240f8eec47c4af1e0d7fd0d44bc5.nq.gz
│   ├── 31fce87784a4c6971eb181bb685933c7f579edf9.nq.gz
│   ├── 36007c7f2455c3c5cbaf0455d48b265f21933505.nq.gz
│   ├── 36f7fe77d71ee14ca8f7dc19f56f1aaa8cebf953.nq.gz
│   ├── 38c117af9d4797d33a0de08f715af81260ec83b8.nq.gz
│   ├── 3da529414778becb489470d490218fdc7ab6d080.nq.gz
│   ├── 42f53859211c5c252173b7ad583cf26718d753f8.nq.gz
│   ├── 48d3f582b20f619bae0f2757a383740c44e9c8d7.nq.gz
│   ├── 4acf1bb8743ce8f23bfb8d166ba0dcf2a7969cb6.nq.gz
│   ├── 4cfc304357d33eed08565f1203f17d0742b801eb.nq.gz
│   ├── 4f45ce5457e44edaea613150189ee9904d04aa07.nq.gz
│   ├── 4fe2628adc41a99cd505d7fad79cf0e6bb9a84e0.nq.gz
│   ├── 507c14ef65adbcb7daa9669ecc1ac3e8b9503398.nq.gz
│   ├── 52b065f413fc2f2728ba137c5419664f803150c6.nq.gz
│   ├── 5301b15e44a23bcef5dce17436af8aec6fedc151.nq.gz
│   ├── 5406b9539446564e50ff20deacce642f842e0cc3.nq.gz
│   ├── 54ad2e3406a75103108c7781da602ca2f7fa31eb.nq.gz
│   ├── 55357acdd69f872f21e1bf8d7bed220e5973f285.nq.gz
│   ├── 55777f21a27102945de83cf0f5693ae54b7142f8.nq.gz
│   ├── 57afa8414211c7634054438c7da4ea018ce02e72.nq.gz
│   ├── 581d560147213f6f291ae9c0987a41bf33140e74.nq.gz
│   ├── 59f34e8e1608463485e6c9a39322a7db73963319.nq.gz
│   ├── 5f83f50a10fdadac8f46a9b50a6373fdb91be4ff.nq.gz
│   ├── 5f9fb24033da6fe35662c3dc789b762d1e05ea13.nq.gz
│   ├── 6577cc7365c4d8f8fdcf31f0f19861863fa314c4.nq.gz
│   ├── 6c72d8a76a2fd8c31e85a2faed29c5d996da2e32.nq.gz
│   ├── 6cce44f25318cfc243abf52ccf920ab0d2c9a9a2.nq.gz
│   ├── 6e098fc0859014f2d59b1fed6cb4f1362caeef6a.nq.gz
│   ├── 709442072c6e7a995739cd94b1ac5616f359aa2c.nq.gz
│   ├── 70fe2e51f1c6a683a473be9fb57ce092e6d32614.nq.gz
│   ├── 76733491f10e79a7b9d28ec7292c2fe05e6f4f1f.nq.gz
│   ├── 77ecabb62e3559710ddcef1c3c468100196a537b.nq.gz
│   ├── 796c6e827f1ee253d19aedee499d4bc1aa9299f1.nq.gz
│   ├── 7a6e485012210271bb09647c11868ce25fc3221b.nq.gz
│   ├── 7c747805df8bea479555f9ee6502d77d73d4a690.nq.gz
│   ├── 80c1694ab19fb04b31ef005549df2e646b1c5223.nq.gz
│   ├── 81ccb65b4e9373771f2cd23621d39786047a22e9.nq.gz
│   ├── 83f9de0b12e8547a004f16f6e418e6b8f40053fd.nq.gz
│   ├── 84b53e281234bf2fe32bb41f61c1208eb0d4352e.nq.gz
│   ├── 854d87bd755c747278c6fef8995ed61343991d1c.nq.gz
│   ├── 8686a201cf9ed9dc8c4a817f4dc5267f513557b3.nq.gz
│   ├── 89a89138215b779e8dab148c139f2741e9a4ce24.nq.gz
│   ├── 89dd11afe00de39faebe0a09c2dbba45111c9245.nq.gz
│   ├── 8a7511437f71bbff22e2e4b7c787129d690a7e51.nq.gz
│   ├── 9017fb72eea9ff53edb389ac2c05cf7bc6b76116.nq.gz
│   ├── 917e42ec170f2b029d131b23235469a9bb921d9d.nq.gz
│   ├── 91f7266897e2c423a1df143c665f4197b89006d5.nq.gz
│   ├── 977e73dcb0d828070cafcdf6ddf448bc1118eafc.nq.gz
│   ├── 97bbb6ce8d10786c52c69d3e0f0627d630738ddc.nq.gz
│   ├── 984e46ca4175e6ffe4d955681808c67a0f7f0744.nq.gz
│   ├── 985d3752747305690701a040388acd1d8423eeae.nq.gz
│   ├── 9a6a61fe3b7bde8f30ac6679f7a208c462c24446.nq.gz
│   ├── 9e7f63c832907f261c78f488685dd79f41bbd9dc.nq.gz
│   ├── 9eccfa746929b36771ae1db228e39bbbb96a9076.nq.gz
│   ├── a18db3f9582ec1c9cd95d7506b408e539449919b.nq.gz
│   ├── a1b6bef4eb4d9d82f42dfce59eb5cdf1bf9a3b15.nq.gz
│   ├── a21dcb6f163b8c4a6e9007628e241a6a92c10a67.nq.gz
│   ├── a5e91a811407ae3cb70b7648d42b24814e7759f8.nq.gz
│   ├── a6072cd9621c9ee444b37a0e4db75b2cb6353f13.nq.gz
│   ├── aa4e9a0e18abed4321dc69195354d2c12427b67b.nq.gz
│   ├── ac953ceea0a9ee7292c439d953f90249f85e57b6.nq.gz
│   ├── aca0e0eed285cfebf189a90e3a50317e928f8ef9.nq.gz
│   ├── ad3946ffb551570dc11d450d04731c4604aac56f.nq.gz
│   ├── afca273c556e8938e2a8192ca6390c38d50acc2f.nq.gz
│   ├── b2ebf47a723b464adcca7feed519ba5b1971689f.nq.gz
│   ├── b822ad5e03387e6a1a4c6d9ec0d1cec5e5ba5813.nq.gz
│   ├── b892bbc771e3a2b9fb2e0452b5b1e0498f2800b6.nq.gz
│   ├── b9760d936d1a22a1690b122b8544d9cfcca7e919.nq.gz
│   ├── bb414202d4c8f3b3e6ae08876d18816a3b16b8cd.nq.gz
│   ├── bbd7f34cb00a971dc7f35471d99a7566a1d8e1a6.nq.gz
│   ├── be09c2457c4a4ac58b05c7fb9be9129141ef9333.nq.gz
│   ├── c04e9c381902d65c26a762d6dccb8a0d9647223d.nq.gz
│   ├── c1627c869b8ddab11fb081f5ce199f3f5702dc58.nq.gz
│   ├── c1a9cdf07ff0c0f58f37f2006862c7e9ea968a8d.nq.gz
│   ├── c40a2fd6b27b21be651cb708d72d0fce83e1737a.nq.gz
│   ├── c4330c7884a8a4dd23eb5af7af33826898bfe2d2.nq.gz
│   ├── cd61e84285c6c841e302d03032f55698f0cd5c74.nq.gz
│   ├── cd7be51ec753841704e42c5223679a79e26ccca1.nq.gz
│   ├── ce0a6c14a2cdbb215cc55c1eb1ae090d0fc8a966.nq.gz
│   ├── d02ffbd9421e393b5a1581cd5aa548db6bfc058d.nq.gz
│   ├── d1394d429eaf608b8b879dacc073cf26676d3238.nq.gz
│   ├── d1b4856eebfbf72df4eaece3e372172ef7d376bd.nq.gz
│   ├── dc3a9dcb0fb57acfa7fe556cdc913a9497f423bd.nq.gz
│   ├── ded82c3e3912758f2c705c58435d6edd44cff4c0.nq.gz
│   ├── deff9c21230ee621193e9d4f6a39b4f607c81cb4.nq.gz
│   ├── df7375af9c8e2d2e5af858e061e374ebf18fd779.nq.gz
│   ├── e01c6d3a7b23c3ebd9e7bf87bd51949f75dd494b.nq.gz
│   ├── e5d62d5209594114fc8de7a8cb259ee8249cb74c.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── ee8f7bdc3b2442d9a06cec916bcc7fd8dcf95a89.nq.gz
│   ├── ef7794f32be00c8e61dc42d6f1ead2dd7c783e0d.nq.gz
│   ├── f53be2df1a7e87be58c1a6008c643c8e0a7c4908.nq.gz
│   ├── f6fe7c46da4999c7c628f1d7be7cd300838ab675.nq.gz
│   ├── fc7d83dfd9822b27c516fbfa01c75650f3b66601.nq.gz
│   └── fcf68581747415ba4c785b183265753c377e5120.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 6e27445dd55682505cb64454895a29c8d1e9a592.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 122 files
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

[pypa/bandersnatch](https://github.com/pypa/bandersnatch)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
