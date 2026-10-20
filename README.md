# Repolex Knowledge Graph of klen/asgi-tools

RDF knowledge graph data for [klen/asgi-tools](https://github.com/klen/asgi-tools), parsed by [repolex](https://repolex.ai).

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
rlex download klen/asgi-tools
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 1a1a85dfb94678ee6f0ccee9e574fe3b3458ef39
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 1a1a85dfb94678ee6f0ccee9e574fe3b3458ef39
│           └── chunk-001.nq.gz
├── blob
│   ├── 031418da4826f464bca8f259612365ea99688f3f.nq.gz
│   ├── 05eac517f3ae34638fe48d9e4f86b8dab5f84633.nq.gz
│   ├── 076dca4debe23ef180d9506c8e741318c32be9e5.nq.gz
│   ├── 0c81daef83de66cd18eeb9c104e08427695efb76.nq.gz
│   ├── 0f6b37e3c273397473a9c905c412e5824c29a44a.nq.gz
│   ├── 10331505a3b311dad002b8325f20059c50e8b061.nq.gz
│   ├── 1199784f79690e4b59122bacfecade6505bef513.nq.gz
│   ├── 13e4f04109baaf4ca2ccdc9d1a0b9052dd1cf274.nq.gz
│   ├── 13fe6fb0a00544184afab3403707e01cd965d186.nq.gz
│   ├── 1576da90392a11500b0e0480a252d755b27e0029.nq.gz
│   ├── 17133c91464f4016a1a7f35b629aaf78fd732905.nq.gz
│   ├── 17dffea6af1df557be3bd34a910496f8e31833da.nq.gz
│   ├── 1eca9505df9c0b7247808ece31a877ce00680b39.nq.gz
│   ├── 1f15a78d63ae4679200f4e8d9b03bf9993a5a85b.nq.gz
│   ├── 202d977eb4fb333958410fc84e0b5e638a112892.nq.gz
│   ├── 20c850c6a393ec7d20a769f5602ead5f785d716d.nq.gz
│   ├── 235493e757affb4391c7c290e6ab5c4e6c93a55a.nq.gz
│   ├── 2a8e005d5188eb1cac32fbbbb69c19c5eee29192.nq.gz
│   ├── 2c6bbfb2480d273233e115abe7eecd929af5fda8.nq.gz
│   ├── 2fcd01ab2a348572d28ce85c87be7ab3582763dd.nq.gz
│   ├── 311105160f1f4f2519ba8265cdf87f8ceadcb80a.nq.gz
│   ├── 3179a9def8f97a24afebbf94502cc23f8077daaf.nq.gz
│   ├── 328dd6a4ddcadb365ea13160b5a051851430834b.nq.gz
│   ├── 347f4ed997c033f90995fbfc374f2b5f1cd7fa8b.nq.gz
│   ├── 3bf70e2ca7579d0a55033bbb272b810e146f86bc.nq.gz
│   ├── 404e32b0744cb25b1c9bb0392ea4a98e57a345b2.nq.gz
│   ├── 4408727c5cfa6de2645461cbe3a31287d24507ee.nq.gz
│   ├── 45166d4bdadd26e293befe78381e5c26868f4f5c.nq.gz
│   ├── 452e691402a3fba2cc2ae7d8160bdaf9a040b4dc.nq.gz
│   ├── 4636d005ba0ec39a1c00bf21fc05bac466789ada.nq.gz
│   ├── 47c8d6e0352cd9a256322c427814fc674627b9b2.nq.gz
│   ├── 4868ad517cf4cc29cd3141d0a25abe42e8bcd207.nq.gz
│   ├── 4f24b23c0b48eb05e46f7238001a07881310a5ef.nq.gz
│   ├── 4f918468371e898e949aeeba02cfe0e5203b0785.nq.gz
│   ├── 4faf0b9f5fb631f6dc5194ed3250157a0edec2e1.nq.gz
│   ├── 507ba2ce09b373d62fd62e3c6a186f2440a12f57.nq.gz
│   ├── 574ed4c24806008b8a973833e1518188cd3f496c.nq.gz
│   ├── 5a118409520813b083045416201e0feabb3043ae.nq.gz
│   ├── 5a61d836610e017e2114d37e78c7c3329f02fae8.nq.gz
│   ├── 5d59788309257daec3bbd4e3809c5df9fc52cdc5.nq.gz
│   ├── 5e205fa47fdef3ac8b2e12f90accf61c83fb1c8f.nq.gz
│   ├── 5fc1ec07a7ae63ae6c53e6880a0a9ba9eac73ed5.nq.gz
│   ├── 617f3036aceaf6c0151fdea833fad23907429b8c.nq.gz
│   ├── 64bb0d9b9699a9dab8cb5577a58874642cc03613.nq.gz
│   ├── 67ad8e148c7b45bae3d4b9a001b06c4ffcbb7842.nq.gz
│   ├── 7346e0321c217b852ed171fb442c4234e1292eef.nq.gz
│   ├── 7439234cef307611bc20ac5e7de02aa3601eea6a.nq.gz
│   ├── 7690f0860208a7376a8164e304b6b4b943f0b18f.nq.gz
│   ├── 77652002e97016a781790838e769a9dcb1ccb753.nq.gz
│   ├── 783429283fd35152c82465cc240488fa1e86f425.nq.gz
│   ├── 7b9f4aabece48be8163009994d28da5727db3231.nq.gz
│   ├── 7d97e51b45f0d0125257513833088cfa1d44506a.nq.gz
│   ├── 843906ac86c570ece223018e32a3475e3af6bd96.nq.gz
│   ├── 8720be85a639437f170836b1a2b5646d5e3d8198.nq.gz
│   ├── 8b3dfdd0ed016288f3b4ad3ad6298a5b886d5ce8.nq.gz
│   ├── 921637f918c15c11c1ad41c2dc6e09803d0e7542.nq.gz
│   ├── 922152e96a04a242e6fc40f124261d74890617d8.nq.gz
│   ├── 92652e020173f59b8ab151de7865966e730178f3.nq.gz
│   ├── 953a770013358046e5bbb7f56749a87f27d4e900.nq.gz
│   ├── 967fb3395a79fccb824f6df52ff4356683039d0d.nq.gz
│   ├── 98b3a77ba45da59fa85d6279ce19c23ea35fcbf6.nq.gz
│   ├── 9cdf8b1553a0c5e6c06a3a2df68a886ee60dd461.nq.gz
│   ├── 9d5f62a65db8ad9d08e14f97ac6c65eb18d518cb.nq.gz
│   ├── 9e0a6853d36babd37d8182996a21523d4154087e.nq.gz
│   ├── a0eacbdb97a354f3ec6b03b642879a83fd1df93c.nq.gz
│   ├── a6efa7dde3d6ef99a0ce4d70c20b0c3e26ad7c74.nq.gz
│   ├── a8573bc64c5bcfd74979d9986053e44b8dda6b0c.nq.gz
│   ├── aa3573fd7d885f4244daa1193aa32d41cbbd286e.nq.gz
│   ├── ab309302d3aded74f32e28de7cd280ad7c07dba0.nq.gz
│   ├── ab4977b2c0a3658bbd982228d46fd4da0d921cce.nq.gz
│   ├── b5555b9a0cfba74610afabd8c93074e34a3295b1.nq.gz
│   ├── b648d23b2f8cb0885afa5d353b01d3e9034f3f2e.nq.gz
│   ├── b76b38e68d1443e62148cfd6e2dac1f8113e16a9.nq.gz
│   ├── bc79b431a70cee785155a2bc33f641fb99665393.nq.gz
│   ├── bce7412f791038b4d45b96d0cfc25927408fb174.nq.gz
│   ├── be4a7dadf63780fc79f64da3a43f1e4644ddc77e.nq.gz
│   ├── c0a3b216a5a512682f6cce25837b28128ded6e76.nq.gz
│   ├── c0bf343336b58618805b595f0cd1a0b53b84893c.nq.gz
│   ├── c1e5ddfe57557c8aa23d2218ff6e480790a7fd08.nq.gz
│   ├── c3b087ce651327f8ee80f28075e13ca665a47ab0.nq.gz
│   ├── c4488099481499d8832996888259587997e198ec.nq.gz
│   ├── c702e8c8ea1deb50a6c8dbedea9d704610b90253.nq.gz
│   ├── c9b55f246d288519da053aae3371c03953f7a71d.nq.gz
│   ├── cae987e66a9149b5b6158c60c9e0e0f8a1b8893a.nq.gz
│   ├── cb2c2d6a8969deaac82eacb234ab864091533d79.nq.gz
│   ├── cb7de46cd3cc2ffcb134acbb4ab9451e067f716f.nq.gz
│   ├── cc024520baf997574f907883da29f09ee6a73ada.nq.gz
│   ├── cebd750116b85dc26b60d7bdd711d05d77f1672b.nq.gz
│   ├── cef5cf740c0738ce612026d73c8afaf7c080ede6.nq.gz
│   ├── cff919883a1253e672b8041ddfde36f0d29c4bfc.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d64cf369608fbc342477e589db11c733d2a6a53d.nq.gz
│   ├── d9a161fa6a342e91e1d796ca7ba35c18858a75a9.nq.gz
│   ├── dbd61c785f98f7f96d892d2b844a60f14193b161.nq.gz
│   ├── dc7c0185e5d8289be2c7afd2b870eeda870bf18f.nq.gz
│   ├── de14ae119c9993ae9552ac4b6177276250a57ee7.nq.gz
│   ├── ded4698406030cae9633e2e0a37f00116a79cd20.nq.gz
│   ├── e46bfa2f602c707fd6c80c79413e1a028df37f94.nq.gz
│   ├── e4c166ab05d584c3d84a8fd63c2925407268595d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6b0677dbc65486b08bb241a784f4b59835057c5.nq.gz
│   ├── e75f3f1984b2b42bc6eb767771af676d28db5514.nq.gz
│   ├── e9a5a6cd5824f311094e0342b921394f54cc08f9.nq.gz
│   ├── edf26ebef2b734e7c968d4aeeac502580c23321e.nq.gz
│   ├── efb1b327cd5ece79a226e99c6477c4e5310be349.nq.gz
│   ├── f3dc8346b90aeb3b4e881cba92c7d5a176e9d50a.nq.gz
│   ├── f8ba5dbeb6a244c60a2e67850213bdde5f4a767a.nq.gz
│   ├── fc380cc6cdc7988c507a5c60e552ec4fa4360b72.nq.gz
│   ├── fc55dda64cbed12eb023a9a74ca04131908e4957.nq.gz
│   ├── fe0cfea859dfc90882ab4e9f0932593b20a8bd53.nq.gz
│   └── ffa4eb78cc87c88bb9b82e97cacfd078a81e1c75.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 1a1a85dfb94678ee6f0ccee9e574fe3b3458ef39.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 119 files
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

[klen/asgi-tools](https://github.com/klen/asgi-tools)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
