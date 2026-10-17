# Repolex Knowledge Graph of albumentations-team/albumentations

RDF knowledge graph data for [albumentations-team/albumentations](https://github.com/albumentations-team/albumentations), parsed by [repolex](https://repolex.ai).

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
rlex download albumentations-team/albumentations
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 66212d77a44927a29d6a0e81621d3c27afbd929c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 66212d77a44927a29d6a0e81621d3c27afbd929c
│           └── chunk-001.nq.gz
├── blob
│   ├── 00bc1a8680282032e314191d44e6143fad618df5.nq.gz
│   ├── 019bb971e6dc314affdbae0bc3584a954551bc59.nq.gz
│   ├── 03c51cd29d40fbc0145ae9bf6574525635e5ed56.nq.gz
│   ├── 03df878e97ed72e460069cc67ff19cc22edf0fbc.nq.gz
│   ├── 07d12598e3b501399dbcda85dbf3207df694e62d.nq.gz
│   ├── 09289685e538fd047a31e5ff5d00c9eb91484bae.nq.gz
│   ├── 0b52cf0dedeac32c7554f10ba60ab066bc8f945a.nq.gz
│   ├── 0b7184847d6e86784db68aa70e7e17c92ac85feb.nq.gz
│   ├── 0be7b9fdea63f362883aaa6d240ecfd0347bf593.nq.gz
│   ├── 0de5925e192fe2cb7aa58fa4d36e0e3eefb072d5.nq.gz
│   ├── 14e3c517868218121b06737d9bd6b3da1271bb93.nq.gz
│   ├── 168244e6314c41c1450a39e550b3c8ec04319e13.nq.gz
│   ├── 19075014d1e40a5b2045fbc9a62325c04ec8b7c1.nq.gz
│   ├── 1909e8f55f49cc3043a8fd703a22c55878510339.nq.gz
│   ├── 1c12d76dd555f77e081d06f2703222acfffa9ff6.nq.gz
│   ├── 1c5d9e890cdc97196c161cb857b5fc6b501099e7.nq.gz
│   ├── 1cc9fd6c352e20146ac5ad50d1caedfa99331091.nq.gz
│   ├── 1cceccf4e1979fc3352dfc42cdc006141d53fae5.nq.gz
│   ├── 1d75e2d3e1a07f8af3bb73a039f49ca10a7a846b.nq.gz
│   ├── 2118ba6b78a4d2a4fcd92cbc88fc2d821a7acd70.nq.gz
│   ├── 249368355c1e2ba71edbf734724d24a75f2ad98e.nq.gz
│   ├── 24a491271ee5384309f9eef7bc0668f93f6aa643.nq.gz
│   ├── 24b4b50d6a75232f30670663af728e59f01b0115.nq.gz
│   ├── 266eff11ea858c2558984b3022e4e2cd858a3f61.nq.gz
│   ├── 280a546740f0ac17d2b0056eb6896d7bf643ca63.nq.gz
│   ├── 28b31e35604e2f9db3c2efa4243d73e440b5f101.nq.gz
│   ├── 2910e9b8633bc04520cab0b42929df01af5c3801.nq.gz
│   ├── 296c30a49f8591b865ca2220e1372b085218b5d2.nq.gz
│   ├── 2a8874e52695edb52ab4785594e9e1eedf325697.nq.gz
│   ├── 3467b5cb39b3113ea8818dac6af1af85befc6474.nq.gz
│   ├── 36121983eea2c4c49b9a44400ae3f62f6c98b0ef.nq.gz
│   ├── 36513daf83524559a485178690d0c0e7962eb014.nq.gz
│   ├── 38640c7fe397234b2c3ea31897b11b3de3ebc7c4.nq.gz
│   ├── 3be7e3b6bb46f9a4687c8af6b48678c44c9336cc.nq.gz
│   ├── 3c7c55b575c6b6c6eae756b3e7f079209f4de084.nq.gz
│   ├── 3d5fe4b1f6e236141a8ea53ae55304e38bb5eb9f.nq.gz
│   ├── 40f20f04231922594824cde27abf8732fbe48474.nq.gz
│   ├── 420421128b22d404b7adedb65c69c306c88086b1.nq.gz
│   ├── 43f357d610ad8d565ef58e1cfdfe221c9e6ad36d.nq.gz
│   ├── 44ee9b9cbe5debf7f0c4a2d0444d83901be8b060.nq.gz
│   ├── 44f1d49a3096d28de4824aaa43bdb2418336cdba.nq.gz
│   ├── 456ed0e678f02b8ed12c6acbc36755d299cca6d3.nq.gz
│   ├── 4739379629644e82baaaa16a8b3a22b6feddfa0a.nq.gz
│   ├── 511cce42823792a15f7cac57b423a86a5aaa47ef.nq.gz
│   ├── 5291770ab19a8e7c663c9d5e175daa1c179cb4bd.nq.gz
│   ├── 5808fdfdf1373a3cb38c8c79b3f42e826c58efa1.nq.gz
│   ├── 59f7508b714bd0aa67414797d87ae76d11f15143.nq.gz
│   ├── 59fef174aeadca7b7c59c012aa258a8ccdde87a8.nq.gz
│   ├── 5c26a52a9f19d5a4ada2f114bcc9c1991337edbf.nq.gz
│   ├── 5ee8f345c411490c11cb14dae8d845556474758d.nq.gz
│   ├── 5f6fc9c488c31b6e31f105de2adfa748ce1c2f08.nq.gz
│   ├── 5fe3de2578b2917b5881863f6eede027999c9f3d.nq.gz
│   ├── 60feb1c4ffe1b709fd6d86295c093dbbb889876c.nq.gz
│   ├── 684e929594ba06066a304279c2b0c2a8c7d245b9.nq.gz
│   ├── 68d030eb2add429deead43c5e2cd0921a975bae6.nq.gz
│   ├── 6b5c965ece659bd4583459dfb7604f60de0bcb0e.nq.gz
│   ├── 6c94945470b76418329366b469c9ef03da73a65d.nq.gz
│   ├── 6e959409822e234fc9aa80c87ba8596e97d1f2db.nq.gz
│   ├── 7144d8c379771a1f35fb66ba9f3e9eca8992a4e7.nq.gz
│   ├── 715f018e5c14631340b69aac9b7b6d4b75493c95.nq.gz
│   ├── 748aef0991d359cf98eb34511ca9c5adacb01d42.nq.gz
│   ├── 77f0447b42120a250377498aa200d5d1049f9df0.nq.gz
│   ├── 7986cdd642998fb0638a81c9ea22615faf8bad0b.nq.gz
│   ├── 79b40f659f00602b79d8ae7ec70c35f75859b57c.nq.gz
│   ├── 7bd0fd962578a4f730805e0ab685a390ff3fabf3.nq.gz
│   ├── 7c0c059ab9586799f32acbf929ed7200c3b13dbe.nq.gz
│   ├── 7f51520640db69bbdb07ee047c7db77be53ce27c.nq.gz
│   ├── 7fce68e1f8c635c577aa0abbaafc40ec69eb2352.nq.gz
│   ├── 82b6a5929a509e0525bcdd75174b95af8ee0d22e.nq.gz
│   ├── 831a3ba7ed53be53810757a1764c07431333b5fc.nq.gz
│   ├── 8710826e4fb6fa0eede063e674b272a5cc698693.nq.gz
│   ├── 88c756e8b54577a5f5904429021771357b769c27.nq.gz
│   ├── 895004fc3c94c6af2f36f22ac3d27f2019dc9a60.nq.gz
│   ├── 8a6ddd76b171213ac0b1e184f8837583ea22bb51.nq.gz
│   ├── 8ce444cfe5b1f84aadcd83451e3fe2bcdf2663a5.nq.gz
│   ├── 8ddfee111cff5c9e9597b644e757006f0a5781cd.nq.gz
│   ├── 8efc0580fbd12cf365a9d6743019a66000fe6996.nq.gz
│   ├── 97039349cc54c07f776d3f8c12e2277d6e114390.nq.gz
│   ├── 9a6263cd3f17bf699d1d2d3c75d39f76eaa2a758.nq.gz
│   ├── 9bb5dfb359bbd5c082035efa2ca0c96d7d9b07ef.nq.gz
│   ├── 9bb6f78e92f0e004b84b192dfcc32dc8e0af4b7c.nq.gz
│   ├── 9c03db81d30c4617d60074429a0c821dc04ef8cc.nq.gz
│   ├── 9d0de26c411e3e31257f03cbe9450feb889d2676.nq.gz
│   ├── 9d17b1cb34b9e5c60b2ab627bb3b4d2af72f2f84.nq.gz
│   ├── 9d1fae44253ebf69dbb27ad43be857042d0e1868.nq.gz
│   ├── 9e52086a2432ee1b0c6b43fb2bfcdc6094102fb1.nq.gz
│   ├── a0318eb40d34d2cf2534af7e3148a465d52aee36.nq.gz
│   ├── a0c7924d441c8f56dd97fcaad2058784b320b749.nq.gz
│   ├── a11005c7caf12fa6949a529e44eaf98077781989.nq.gz
│   ├── a3046f12c19277807a8fff8a59b113916ab4b1a8.nq.gz
│   ├── a5748bc09c70e1d20b3c9ea91ed898bf27ca80ba.nq.gz
│   ├── a62f60565ab6ca63ee94fecb19a99305d21d2f3a.nq.gz
│   ├── a9bb25709582a7479fc3e4be865ae1fe675f0e21.nq.gz
│   ├── aac5839928a7ac53f6ec6c2fee9c2b2ed125de03.nq.gz
│   ├── b0dad66288035e04387336b7cf556f6246c38acc.nq.gz
│   ├── b17920c2cb8dbeb7417efdac7f7d06ebdf2df742.nq.gz
│   ├── b2218ee7356bb10b2dffddbb5a4974c67b56ac93.nq.gz
│   ├── b6115e6e49ec995f7cb7908df56bc66632a265dc.nq.gz
│   ├── b92ec81aed2fde02e0d8f3d6ebf5db38ab12f59a.nq.gz
│   ├── ba139179c71db5413fbf358ab8af23c8903833a7.nq.gz
│   ├── bb987257f4068851b71d255400b4ebb397d9652c.nq.gz
│   ├── bba49254355145fb8b61d370922006e50e42a3ba.nq.gz
│   ├── c0ed18f0ab9bc70ce12a879e4640732e33c96a7a.nq.gz
│   ├── c4733fb8f1fb31df8140a99906af77829a14e758.nq.gz
│   ├── c8bd9cd4bc1d68a14692e1b1a598bc653af21f76.nq.gz
│   ├── c8c580c154ab9f5aceacc0ef55f59a33ac24e00f.nq.gz
│   ├── cb7fa516a58be8434e0fbd3c6b883e512f8b586f.nq.gz
│   ├── ccbc02f14354284074d68d6c995e8e56fc08982c.nq.gz
│   ├── cdb8dd5459d149eef7294d2a5e27967395afceea.nq.gz
│   ├── cfb73729f82758ad6f1b0c84920906faa95aaf39.nq.gz
│   ├── d362ea5e2030abcb173995c3f87b0d68086322f4.nq.gz
│   ├── d3924c2e035619b5fd7e78db3d4b054bc733d528.nq.gz
│   ├── d68a9c0e6fa3b3bb05e2e8a03301f87c99365bd3.nq.gz
│   ├── d99f71b36c23cd1a73050cf5b8e0b3e48ab1d0b0.nq.gz
│   ├── da7938de98aa254ff2c1d5bcaf0aae7ea71bb89f.nq.gz
│   ├── db6f098cd6548b2fa02801ae78861feeb189f5b4.nq.gz
│   ├── db8a66d40ee9cea56b2d366fff4ce0e08c6bec01.nq.gz
│   ├── dc4263722a228caaf26ee0e844eccb9931388f26.nq.gz
│   ├── dc4cac75539bd5426f0adfc959bae8486f5c22c4.nq.gz
│   ├── dd23f260bb33fb9a32ef7b6f6b8709509844cdf6.nq.gz
│   ├── df0df78c95ade76a078df06820ff21937005086e.nq.gz
│   ├── df2e131a496ca9226fac871c5a70d4e6891a8091.nq.gz
│   ├── dffdbc89e1c33e0459c25bcb51e663a657851ccc.nq.gz
│   ├── e33c74ec7da5b8b495f7069db78a660d2e1a201e.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── f0227bb8e0543d08eba4d2cf92db39f2d304a333.nq.gz
│   ├── f4c937fd70af6e5051686f2b5e3ba0bdaf25d7fe.nq.gz
│   ├── f8e142144fc23108cca5e445d6daa0abd36d5ee8.nq.gz
│   ├── fdeba88f75f8d04ead40f06b6cce07d8c0da4241.nq.gz
│   ├── fed9178ae7a09209ed407636a384024fb742e853.nq.gz
│   └── ff6ee8168df7239410bf23a099e195718bec0b6b.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 66212d77a44927a29d6a0e81621d3c27afbd929c.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 139 files
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

[albumentations-team/albumentations](https://github.com/albumentations-team/albumentations)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
