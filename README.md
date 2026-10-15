# Repolex Knowledge Graph of twisted/txaws

RDF knowledge graph data for [twisted/txaws](https://github.com/twisted/txaws), parsed by [repolex](https://repolex.ai).

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
rlex download twisted/txaws
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 5c3317376cd47e536625027e38c3b37840175ce0
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 5c3317376cd47e536625027e38c3b37840175ce0
│           └── chunk-001.nq.gz
└── blob
    ├── 0045466c8a45e909b5c940f1444661af1278c2dc.nq.gz
    ├── 00e318fa97c3f261ed472bc1035a3f78bde86b86.nq.gz
    ├── 021833bdd8975f133f520b25a2677716a66de442.nq.gz
    ├── 0253f19456b1b565e78ac795242bbd49b5e048a2.nq.gz
    ├── 08a0364c82f165af8cc37dfce4b4ba52bc694ec7.nq.gz
    ├── 0a3350ab5fe8c5289227e359e1a4a4abc98898d0.nq.gz
    ├── 0a44cad16b465c100a80c8cca1e76c637c32279f.nq.gz
    ├── 0a9b87dc49102e66f3c5cdeca76c47968c7e7d1a.nq.gz
    ├── 0b2cfc910a78f97d6006053183878233185bfab2.nq.gz
    ├── 0b94a4e9f22a490e9ae0ae230f473a9c85c7b07f.nq.gz
    ├── 0f7a9bfae3680836a2746b5bf7a33a6fa2b93c34.nq.gz
    ├── 0f85dbff4a0db97e3b9be8d6a82265f50b039135.nq.gz
    ├── 124a7096a13016c8d0b315f2228d0a212382f245.nq.gz
    ├── 148443291580c7b0e4d47da367ca8383d7a92cb4.nq.gz
    ├── 14ad2328bfcd351ecb61c3af7fff587423a96d8a.nq.gz
    ├── 16f1b8e372e9ef57b292ef73fbfd11859ae622ba.nq.gz
    ├── 1896ed08de4c1f971ba5da23f5c62cfe8d08eb8d.nq.gz
    ├── 1cbb3ccaf641362e4bda8dc75bab3a34a42f3773.nq.gz
    ├── 1d03da35e938a4cc5bd5384c23f245d107d8588c.nq.gz
    ├── 1d5a462ee2a56a8b1f067e4d535b666a657982b7.nq.gz
    ├── 203fe69aac8cfad42bc6e0e75d31f48ac51413ed.nq.gz
    ├── 20823424d41704638ca4098e518b4ec408fdabdc.nq.gz
    ├── 210e1457a1e1673515cec8e1e049ac7a493eb31d.nq.gz
    ├── 23a2b41ced9f2460dc47afb3ed46e8c9511ed8de.nq.gz
    ├── 24a97d209b9cb4587054192dd7970d8fb7b0c1c1.nq.gz
    ├── 257422ef6791d5ec407446b18ada6ba7cb3f45f2.nq.gz
    ├── 291ed0756bf24578c78bef56273b33e517faa98a.nq.gz
    ├── 2943ec89d207a4c7e0001537b07fb38afa7196c4.nq.gz
    ├── 299ce94a368b50ef6571388cfaaf68607f0271e3.nq.gz
    ├── 2bdaf7479bae12882938873ed56a65e9ebb312cb.nq.gz
    ├── 2d244dc7949674accc86c3573376506dd1250589.nq.gz
    ├── 2dc6b2bb517bedbf20e1cf4d7e916167fff0211d.nq.gz
    ├── 2f73b22aa1f0c6bd54c060c9e387d46a310d4f42.nq.gz
    ├── 2fd74c7d0c8438366d832628a7585b78216d590b.nq.gz
    ├── 2ffb301fdaff033b44f4cefae255010455f3263d.nq.gz
    ├── 307c1051d5f2ef4f4255df78f647ff209a48cbfc.nq.gz
    ├── 330f26d4cb5691ab79a5f0e929e9c6cd0f458fd6.nq.gz
    ├── 332bbffceff73c2bf7ed270b5da74e661c232453.nq.gz
    ├── 333097542cede183b51711ecdd7a09d48dc1de9c.nq.gz
    ├── 33ee403f0bdafa9dc6fff826474e41b0745b158b.nq.gz
    ├── 3497d731b3d397e5ac15df5784a9ee5ff9b9cdb2.nq.gz
    ├── 35e8933ba036602e63403dd63c6e0d13d3ece1db.nq.gz
    ├── 36e41153a0b6233d07f23020bf8704acfead3428.nq.gz
    ├── 37b2f0419099086beffb32d2bc6ada995538ba7d.nq.gz
    ├── 3976e2ca92856193eccaddf766ae529fcac93f17.nq.gz
    ├── 39c61cba9c6b4b503bd35ccb8707397ba06a0ad6.nq.gz
    ├── 3ba945069b8f7a2e533c80b83728266caa921f56.nq.gz
    ├── 3c9107171a1b4502570a73379e708b22bda6553b.nq.gz
    ├── 3dc4179013f314eaef6fdb7ebff4f0bb35f9da4f.nq.gz
    ├── 3e83c524b0536ee3bace6314d7f75dc002e85b41.nq.gz
    ├── 3f9987af7f307af052392ae9b62262415b8a9f37.nq.gz
    ├── 40062c79f874a999fa49d5331805670693fea4df.nq.gz
    ├── 401a9cd93c4c9fbd184ea2edcccae58b24b7c9b7.nq.gz
    ├── 43cc5096e4862715c896fa58ad96942c99413eb6.nq.gz
    ├── 44280cd7bb689c3b586b749a5bd40bb91474c177.nq.gz
    ├── 44fb392e622340fff8021e0f928c7837f691489c.nq.gz
    ├── 45b3d94066407ce20ced6a266afb18cb2071f658.nq.gz
    ├── 47225033f6187d7bf4719f6a73ef8431646906b1.nq.gz
    ├── 4840ff2721d06ac457a3c3c902215e139e388f4a.nq.gz
    ├── 4874ac0b1f45c4be096ac6384234c0ee8a8ee39a.nq.gz
    ├── 48a135ecedb5dbb1b7883b0ad6c57a4e83f279aa.nq.gz
    ├── 49328d18d44635578bdb3d93539868ca0ba2f417.nq.gz
    ├── 498e2e113673482d035f6f1945b3b91e1a0e56bc.nq.gz
    ├── 4a7243bf9d11ee1898f5ff1e7d3370f9f28cc265.nq.gz
    ├── 4d9de5e5e4ca14b7cd1859552080368343ab0d7b.nq.gz
    ├── 4dd630bb26433a09f5e8231853038807c0fc16e2.nq.gz
    ├── 4f59e7d20cd71f6a43e83f8110681456dcefc394.nq.gz
    ├── 515c61c6335a88c4b02fe962c80d7a31ebe8fbda.nq.gz
    ├── 51c69f6239eb4839a81a4e5636d9f286550b4270.nq.gz
    ├── 51ee71b749eb94dd9abc184ea3bbf3e4b4c4a504.nq.gz
    ├── 5249be3bf83e1b098040cd677da9c9633193ac7b.nq.gz
    ├── 531b89b45b172003b8815ab13e4c51a6e4b92680.nq.gz
    ├── 551c0271d4a5ebf8aff478f5286eb12701a41182.nq.gz
    ├── 56955d9a0c2c608c22ccfec7bb0a6c157e514e6a.nq.gz
    ├── 575a79bc4f0db570d16acf94e73938d826b27658.nq.gz
    ├── 5c3a9434ec316b593104a700037047ae1704a58e.nq.gz
    ├── 5ce537e674f945cc19b9b944499dad6138608727.nq.gz
    ├── 5d4b9f619d574eb5375aa94c9bd5f59d51943997.nq.gz
    ├── 5e8f5a432d34abfc2df95536068b9143a1c0aeae.nq.gz
    ├── 5edc8f456bca14d3a07f022ad16698915dd74238.nq.gz
    ├── 5fe1df7e781b5c3e9d402e5162ed3dba4c66ba75.nq.gz
    ├── 6265aba566a3923b91ee84e8cbb8a2bd6b0c3e9a.nq.gz
    ├── 62e50d106f2cffb91912d86d5e5c3e88cd6b2514.nq.gz
    ├── 6482d85c918f0416411693bd99f5fa67f3709dd6.nq.gz
    ├── 64aa046dbbfb03c8c47bd57b19ea9fad491a7522.nq.gz
    ├── 65ab663719ebf95d66f34576988932fb398b6a68.nq.gz
    ├── 65b5c7ce4e4d6c1539b6fb7c6bc2430c76216e98.nq.gz
    ├── 66a1a70a433a8e8958dd3110130001f0aed21cd1.nq.gz
    ├── 6a223d6617114d4739472ad40c60a2cf44a855f7.nq.gz
    ├── 711a8d4d69fb38543413e039809e2fe2feb72664.nq.gz
    ├── 721a39ff88293e27a452592dfd48258164358436.nq.gz
    ├── 738b3fbd863c7f1cf6361c7d5deff885ebe68590.nq.gz
    ├── 7429923e6b23bbe501c3f340a45004b0bc2a8fc1.nq.gz
    ├── 757a5fa8d92bc7ea60a93f63394fef0dd22fbfaf.nq.gz
    ├── 762809de53c0ec086546cd129afe7638c87d5a8d.nq.gz
    ├── 77dbe6af7479bf027c735b4cd230e425b002c0bd.nq.gz
    ├── 78db3bd8ca60b4cd270688b64f9a43d1f01fa27b.nq.gz
    ├── 79e16a95370026e88054b38246d5b79b8be53048.nq.gz
    ├── 7ad8b19b6e076e113648d036c1db56ede7b9e8b7.nq.gz
    ├── 7baf4c82f3d5cc7db3fb266802b60b1e015ac924.nq.gz
    ├── 7c9420eea1c197e5ff19122ca8e7b92b93ea83e1.nq.gz
    ├── 7caa6acc235d6e9b377dff345af376a7a890539d.nq.gz
    ├── 8001b3d6b51ce4b08b7cb181b8b4c757e5cc77b4.nq.gz
    ├── 807662c7f4db0c742cadd6e7eccb1779367d8c12.nq.gz
    ├── 80966096531ec8cb41b50082d04961a38a571464.nq.gz
    ├── 80ab577abf4c516481c410cc174c3c720d4e70c8.nq.gz
    ├── 80ee1343883d63f0fb07aed4d42debcbdb50a9ca.nq.gz
    ├── 80fbd430f76dfebd7309f381d67870e1852ed376.nq.gz
    ├── 817eebac577e7ca53f0c164aad063d8b371ef3c5.nq.gz
    ├── 82af1505e2ed23707752ffbead454a0a3614a4ca.nq.gz
    ├── 832d8a50d29838451b582c1dc8c2865920c484d7.nq.gz
    ├── 87ac95c5feed55c6821b9405678903ad95df427e.nq.gz
    ├── 87c0e181576f22413bcac69cce13755d70da968d.nq.gz
    ├── 88beb82a3808277969a1946ae085b24c3f000d07.nq.gz
    ├── 89e572e60969c3f869aead6b670bf21987ff25f5.nq.gz
    ├── 8a56f15f7472db57eac753e0958163efbcd9bff1.nq.gz
    ├── 8ae02cd6001af25cdcbfc2f6c601494d072bccc8.nq.gz
    ├── 8af54df27eca59e77da83c5c5d2cb8fc45ace72b.nq.gz
    ├── 8ec0d6cf0a996ac374badc071ce2134731d5e5a2.nq.gz
    ├── 8ef71845299e0ffd7b68b0f0a46811071ebe83f1.nq.gz
    ├── 901f36c3593bc333d2adc1fb9e94d49994c655a2.nq.gz
    ├── 9042f77988142a27abc0b85eb51ffdd51fee7984.nq.gz
    ├── 9157bc74de342129400eb9f2a4961250539c0c5e.nq.gz
    ├── 915c57f214717722f6fbf7b59ac7327fe68c8780.nq.gz
    ├── 91667ad59747c4e3424b7d10558c5716b98e32e4.nq.gz
    ├── 9202ade970e86be0ab2ff1c1a56910da930e8203.nq.gz
    ├── 93354b100ef7385d28d901bfa3a107e36024f5c7.nq.gz
    ├── 9376796d2c7d1dccf8270cade3a7440e158e4ed1.nq.gz
    ├── 94eadb6d2bc82d49ba20f2e0d71e0b77b025d675.nq.gz
    ├── 95d1fc2584073b68468f4db432c9c426c3dd1c15.nq.gz
    ├── 970d0a050eac39883357c58926eddc01d6a28843.nq.gz
    ├── 971d0a2da040f9e607f7a1b47dba2858a049af06.nq.gz
    ├── 97f9e9c61440735c693fffd936a6c7bf66a06ab2.nq.gz
    ├── 98224c9bde6806b3c92222d0bb6a5dba5913f7bc.nq.gz
    ├── 99c3210c9988c9abe961a9a4b0db322a798c4a34.nq.gz
    ├── 9a5f7e4944fda805a65b8a8fbc395ae0ba4ad78a.nq.gz
    ├── 9b6179fc989ad027ec3290189667fc14b2439cc4.nq.gz
    ├── 9bac9311ba7282b9bc329a26f9187b97e4de86ab.nq.gz
    ├── 9be58ad3c2ae01aa18984e2def0bdb05b7a3f6fc.nq.gz
    ├── 9c56fec13fa351c9ad69c1cfc5aff47b56ee51c9.nq.gz
    ├── 9d6d7ca20acba52f73f1e208a78f828ffef0c9f5.nq.gz
    ├── 9e7f40a4fe78f4ec274b758c308bdb8e09e3ba2c.nq.gz
    ├── a05248e174435aac2f9dff808082685e9cfe169d.nq.gz
    ├── a0b15cc70432d9ae5563d977670d17c153c82337.nq.gz
    ├── a372f4b2494c773897a9ba05e13dfb8064f82885.nq.gz
    ├── a4307ce425898f4ce58e5cd0f248c77e42542576.nq.gz
    ├── a44ca5be80c4c14760e0a2dac0b9966ece44674b.nq.gz
    ├── a59087c9a4ee49c1082e805a7fcf8f84e655b969.nq.gz
    ├── a5ada0d940a9c8e59c5fca2db64fd12f128f7e47.nq.gz
    ├── a62589ff7ea9c4bb0fb4d85769418f7b9ceda1c5.nq.gz
    ├── a633f0c052c7a81d2e3760c6c1261a7e4692b142.nq.gz
    ├── a63670394947b33fbc1dcc46d12e7be342903ccc.nq.gz
    ├── a6c4704203d71423f4653ce41513a511e0217c99.nq.gz
    ├── a835c9e491be62c7ba5e988d7836d30a4983d0c0.nq.gz
    ├── a9cdcd79e8bcd2ef8375fd55422c22fd31bd00f9.nq.gz
    ├── aa3162d8e93c694bbb04e8f26e0fb9930a8d2605.nq.gz
    ├── ada7f87760b63f907cfe10aab13f166c250a7dee.nq.gz
    ├── ade3ec7537b4e5381ed8e1117f13a09a5a10f27e.nq.gz
    ├── ae24381236415f1739edc376d2fcbc005533ba05.nq.gz
    ├── ae5664c81e6dd009924b7f23f76f61dbe447d518.nq.gz
    ├── af493437ad27525c4b166b437ac4ce4faf7dc012.nq.gz
    ├── af824c889945453cbe08e621d66b0063e20c8a5f.nq.gz
    ├── af906dedc08dcc71ded6d1d8f415d4d57f0633c0.nq.gz
    ├── afde47a9ac6d410781d568eb4abb51d33a5bb2a2.nq.gz
    ├── b187649cb3171e99285b62583a4d1805d764083c.nq.gz
    ├── b4aa17e2a58418f584c296dbf71e801a70505e56.nq.gz
    ├── b4b78a1668e616c3f1b6449da44d3e5bbcee9c6e.nq.gz
    ├── b76ca1e2d48a12cb90934aeca85a581bf7e835dd.nq.gz
    ├── b7aaa13bbdbb041458fbae070026eb9ef5da7e26.nq.gz
    ├── b983ed10358c572eacef3592a97f11879980f96a.nq.gz
    ├── ba1ef402353799c40e500b75e4531c883bbe527e.nq.gz
    ├── bbe26cf98f28ea147a7b1c3b8594e388db203618.nq.gz
    ├── bc39ccfc5b963ef1b60dc9ce97476b81c5d68277.nq.gz
    ├── bfa7dfa504634f1fd9a0a14b7b204b09d4fb6959.nq.gz
    ├── bfcacba707cc58d934339f4dde0ea626b83a6a0e.nq.gz
    ├── c0409ab2a3d498e2b6107a0a0db288cef8b784e1.nq.gz
    ├── c2fcb2726cbbd8d323365e0bd697dd4dc3a45e3e.nq.gz
    ├── c49608a1486fdafaaba7970ad723ab507fad8382.nq.gz
    ├── c4ed216c13cfbbf2f201cb9fbfa033eee6d5eb7a.nq.gz
    ├── c6cdceda17d3808c55291c0a34365e38e6d93f0f.nq.gz
    ├── c781fe665e6423aab2f5cdea7b9ca431ea511a38.nq.gz
    ├── c84a80d56aee65c2e4a92d42ee4feee6737568c7.nq.gz
    ├── c8d9a9da869a059b0acce8ef151b55c50a5dc6b1.nq.gz
    ├── ca7cc661d1e72ebe4e1e54986e12eee9d5e23f69.nq.gz
    ├── ca87802fe6e75f1a58619efd680c5e0cdb2f9765.nq.gz
    ├── cad86bb234faca633e060ee0907e15ef3e331e03.nq.gz
    ├── cb0f5b73edeae985f492faed5f9bc896479ac7bc.nq.gz
    ├── cbdebe2cca662a6bbe0b369e8bcfdec9d13db563.nq.gz
    ├── cc2757e167d2197abfe9a31aac1a71487e436f1b.nq.gz
    ├── cc2f8fafe556a5603c2f31959b95200e14fc7d3a.nq.gz
    ├── cc3428236fe91c7ba4d55a59a13841f56674e999.nq.gz
    ├── cce24af919c4b5ad3e0e52d00e5bca8a06f1e1a8.nq.gz
    ├── cde31b4381598fda7c8d08f575691e98f655bc87.nq.gz
    ├── cf3130fc618c8c43492d670ccb00de1dfcc601c3.nq.gz
    ├── cf4513ac44fa089b4e1abd6a6b362e40e60c2361.nq.gz
    ├── cfd4e8b74cc5195ea6d51d56c6360b9a6d464e87.nq.gz
    ├── d1b87176bb298aab51f3d890a68dca8d68592ac5.nq.gz
    └── d2833b32f999040840fc9af81960dc6ac9207789.nq.gz

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

[twisted/txaws](https://github.com/twisted/txaws)

---
*Parsed on 2026-10-15 by [repolex](https://repolex.ai)*
