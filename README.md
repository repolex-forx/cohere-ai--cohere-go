# Repolex Knowledge Graph of cohere-ai/cohere-go

RDF knowledge graph data for [cohere-ai/cohere-go](https://github.com/cohere-ai/cohere-go), parsed by [repolex](https://repolex.ai).

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
rlex download cohere-ai/cohere-go
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 63f3b3809b9772ad1421b0fc445a01016af3b879
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 63f3b3809b9772ad1421b0fc445a01016af3b879
│           └── chunk-001.nq.gz
├── blob
│   ├── 0239c6c899c34685c9aa3af437c1e04280c62897.nq.gz
│   ├── 02dcba53989d1c9ab374e317bceaf140f7d95b62.nq.gz
│   ├── 02fd1fb7d3f1c5bdb74abc8b7c82b1a561d8e14f.nq.gz
│   ├── 038cf7292b1b353470b91ca0314f6046b5d15b4f.nq.gz
│   ├── 039dcd82989d17b4d98539dd8f654a17451aa7ed.nq.gz
│   ├── 0690da1d9fdef1a4e4e0e54495d1b1046c7f2be1.nq.gz
│   ├── 06d62d2410b2f76bf66d089a947037f42825bf43.nq.gz
│   ├── 08d1b3702049bed92724e289ecb04fb259f8cbf4.nq.gz
│   ├── 0aca05e4c07f0d9cc3f7c7013f979bb3ecabcd65.nq.gz
│   ├── 0f43bd0d3fb4dd53714a48548260bb63101b5d0d.nq.gz
│   ├── 0f54dfee18d3cbbde4264e55fecaa0cd3ddc789a.nq.gz
│   ├── 13201f712b44eade249dfadd9e3e7e78239d93c2.nq.gz
│   ├── 134520d63aad310b06da6ddcd81044563d72d12b.nq.gz
│   ├── 190ab9865be09a359a1a19f5dafe2f44cd16bb96.nq.gz
│   ├── 1b39bb76152a431909d123fcbc5ed161553ea621.nq.gz
│   ├── 1c9764cf505d6cc7366a73fb34c93adbeb64f62f.nq.gz
│   ├── 1ef320f225893c0df2ba9602feb08de0bace7c49.nq.gz
│   ├── 1f134b710e13170b22740127f0de67a1a84e1118.nq.gz
│   ├── 2244362991ed869c4770bb7aa5be81df51c13a16.nq.gz
│   ├── 24448964a9d348f8381796d7a10fc2d83b9342cb.nq.gz
│   ├── 252758b2efd3692664579031e9f359a09bdc9c75.nq.gz
│   ├── 312801851e0e552e2333540106fea46d3e35d407.nq.gz
│   ├── 32bfd591b3f491036989ca8749a2e73af683c7b5.nq.gz
│   ├── 3351c9f3fada6c65a9d2dbfb6fa9c4a0aa563483.nq.gz
│   ├── 3571cd61c2b2489c2cd58b7d5e1a5715fd1135b4.nq.gz
│   ├── 3be2f34babbf48f230302c76fc2447a91c07854d.nq.gz
│   ├── 3f9219fb3334779ba394134497b572f7ad4a8cf7.nq.gz
│   ├── 483ab7dc0f76770471a86a6418f532f0235d3c9e.nq.gz
│   ├── 4bdf34fc2b7c8e4b1b417ebc18b030d41bf1b204.nq.gz
│   ├── 540c3fd89eebb599490720d0caa85f5c57291376.nq.gz
│   ├── 57f901a35ed8285376819d12ffa26b050f879211.nq.gz
│   ├── 58a857d1a88e429917a59515e3ffa8f9e526ae02.nq.gz
│   ├── 5b463e2973504655e239f4c87ab65eb9b4eccade.nq.gz
│   ├── 5ba036d3ec302375580304cea0231998f26d30ed.nq.gz
│   ├── 5c2c0b152edfe77b92e7136855449add2e017298.nq.gz
│   ├── 5fbcdc2ca51ba1e36c7b7972fd48df1ea382c430.nq.gz
│   ├── 6168388541b4ee8eca6567525d236aeb1ecea531.nq.gz
│   ├── 61c36d51b864b44e25be8396fe0ce418f42718c0.nq.gz
│   ├── 67131a6f508f3049e93ee1db251761eeeb79df62.nq.gz
│   ├── 68ab21ab34bf9c8bbe8b120913878653da0cf891.nq.gz
│   ├── 6c6ceab2a01d3db487da2d26eb39f41aeace4d4a.nq.gz
│   ├── 6c875eea5eaa7860da1dcd5aa2e5d29d349ff27d.nq.gz
│   ├── 6f027f9aa221c9daa17b5a8e8626cf81a73179d3.nq.gz
│   ├── 71696338901f815280f834d7dce6966e3c20a7b2.nq.gz
│   ├── 737abb97c837dfbdc02f0229e2e795b01c4ca14c.nq.gz
│   ├── 73d62b9a407b48caf110e8498534779bb0c8e883.nq.gz
│   ├── 74928d6a47412470035107d1633d0a2ca410833b.nq.gz
│   ├── 786d98c10c65650de32268bdd920775fde353601.nq.gz
│   ├── 7cdbe47149033e3b19d76c3aed2f2fac5e302a00.nq.gz
│   ├── 7f08c19d0274a5890bd29bca4f383c61effbf7a7.nq.gz
│   ├── 829a0a8ca2b6ae2d547b9005449c9987999ee626.nq.gz
│   ├── 8413f3f7be96e5919d31fee26f059cd0275cc190.nq.gz
│   ├── 858fb82bf77d23fba83d0baa2163794a74c12b42.nq.gz
│   ├── 85b9441cc02208415b88c8017a9e70b0743324d2.nq.gz
│   ├── 879fd80c128cabe1ed6ab8b23cbe796299f30ccb.nq.gz
│   ├── 8dcf5214d1f1a62a2dcbab6903a937a894ba7841.nq.gz
│   ├── 8e22b499280e7e875fcd103d58694d9fe048973a.nq.gz
│   ├── 909957854cc0b74ec683eee8aaa433a7dd16e783.nq.gz
│   ├── 90c3abc71f31216bf894b798a1f97ae7d3ba2337.nq.gz
│   ├── 913d0ba26b9c19658f03c3b44e5dae0d271e3674.nq.gz
│   ├── 9280f5e5cc0c0635fa4a91f01d3c3a7f6b2ea48a.nq.gz
│   ├── 92c4356929400034934de6751e37bf32f80f756a.nq.gz
│   ├── 94435e954d3ba70726ad81df7117757a9ea695b2.nq.gz
│   ├── 978be7fd58aa892c02efa2286fe22f7b6aae9907.nq.gz
│   ├── 98fd5585e03363ee612084a1b9ebf63d51998ba5.nq.gz
│   ├── 9b567f7a55636919a384745d1289d1257c5d207e.nq.gz
│   ├── 9c36ebe0c77275d2655c6d0775e8816c5b93c13c.nq.gz
│   ├── 9de4ef5d781f22f10f45dbb0b61c3d8a2d43cb73.nq.gz
│   ├── 9e37018afde99e5a6689d6b61dc51fef7a481e8f.nq.gz
│   ├── 9f358f1b2f0d363b1aa45904e370317eb19c478c.nq.gz
│   ├── a79de1a5adac5acf127d751d93cd124c2c3a72a2.nq.gz
│   ├── aa2510ee5121a2d4b8646cec661e1e72b1c72a50.nq.gz
│   ├── ad59bcf5cfd2e47f9140ec4fafd5cbe1e9e842b0.nq.gz
│   ├── af95e209d5d9f4bfbd6bd43574493d96b42e797a.nq.gz
│   ├── bdad3d987c6268dd990b67cd954dc8efc469d443.nq.gz
│   ├── c24f7aaab2b459aa05d6c0bd6a8f18e09df1e465.nq.gz
│   ├── c3b274a2030281babb0d461a3af6da024fb58bea.nq.gz
│   ├── ccf4cf2132a50bb4dc98a71b8d3626e99cd5897a.nq.gz
│   ├── cdaf16ab2c8581189c24978d581382bf371b3e94.nq.gz
│   ├── d1f349873032b9c247ae6d10ba167015152dd648.nq.gz
│   ├── d371d97082049f48a102bb76ea77bf7dc143e3cb.nq.gz
│   ├── d38590098c4e00eb860a4f1457b7afcad965d2f1.nq.gz
│   ├── d3b5dac0e4d1a6c86b0bd3f4e628d6ceb10b2e68.nq.gz
│   ├── d468162beee9ad6fcfd7e19872bce5bad0ce0746.nq.gz
│   ├── d4a439e7c026f347712e02c2fca7935b04ae2880.nq.gz
│   ├── d62dea71a1d0cf5b4589df27311bca3f9b4e4e3c.nq.gz
│   ├── d8d995503d6f85513e84bc6a2a6d1e1958599f31.nq.gz
│   ├── e15801366ac4eddb1ae803efa8bf064e378f5f4e.nq.gz
│   ├── e465a0c3b19e6fd76b00885142080b39e280633d.nq.gz
│   ├── e7f4a1a4a4bd1ed09366c9a7c9b21ed6bc0dc281.nq.gz
│   ├── ecb1d6041fe117e819930943138f705080ef376c.nq.gz
│   ├── f355069a2df91071207f08c5367353bed1d1a771.nq.gz
│   ├── f44beec447d6ad69ab80149172ea9dcdcf883161.nq.gz
│   ├── f9a8177e734fe53279ee835b5744a7302a46fc8e.nq.gz
│   ├── fabb06a62ccd814ac3f3565168a53d6284a93db5.nq.gz
│   └── fe632eb5b36833d1645daf712d262cf74d939534.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 63f3b3809b9772ad1421b0fc445a01016af3b879.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 104 files
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

[cohere-ai/cohere-go](https://github.com/cohere-ai/cohere-go)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
