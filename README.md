# Repolex Knowledge Graph of deepset-ai/fastapi-openai-compat

RDF knowledge graph data for [deepset-ai/fastapi-openai-compat](https://github.com/deepset-ai/fastapi-openai-compat), parsed by [repolex](https://repolex.ai).

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
rlex download deepset-ai/fastapi-openai-compat
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── e8069f3f17e1593abe19dc7cc611dcc416f5505d
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── e8069f3f17e1593abe19dc7cc611dcc416f5505d
│           └── chunk-001.nq.gz
├── blob
│   ├── 02d786ced1b91c396340cf8f18ece1a1933bc919.nq.gz
│   ├── 04d1a2848aa58915ae85211a4524438b6e53ba19.nq.gz
│   ├── 052f3eea3893f0851f66a50c3ad82b36c28fc207.nq.gz
│   ├── 07d78e26f6b38c2a9498fc6ffd39f85404b01ea1.nq.gz
│   ├── 085e25f35074f9b1edc2fe4ddf9578aba2de3cce.nq.gz
│   ├── 0b2e206b8b0d3b51f350ee5488bd673820ec1ec8.nq.gz
│   ├── 0de3c05cab78eb4fda00e08cdf89cf5d576f32db.nq.gz
│   ├── 181a395427d2299ce1e397b91018a894f0d84ae8.nq.gz
│   ├── 224d29b431fbb19e5f2a0a6d50a1a4d11fd68b91.nq.gz
│   ├── 25b0ad1071d0f25a5ddaa37d2067ac2c488616ca.nq.gz
│   ├── 261eeb9e9f8b2b4b0d119366dda99c6fd7d35c64.nq.gz
│   ├── 2826b01186f4eae447b2a8e09324150ad22cd6df.nq.gz
│   ├── 2e76e0c75d73d3b8841d334ed06cd294fa46dac0.nq.gz
│   ├── 4065e0be624bdb0f2b9c7c4cb88317f7f5a87f4a.nq.gz
│   ├── 421cceced6def55d9cc5316479c59cd5e57f2fa8.nq.gz
│   ├── 45057af973118f4d5395777238d81f4ae9802e33.nq.gz
│   ├── 47aa55798bf05c05f70fe8d54e6b99f389285c92.nq.gz
│   ├── 4c2421713bb61e0e7c08370b3fe4c6872b5d595c.nq.gz
│   ├── 4d7f0b182d4ae12ba86e9bc1e7b57f15883a22e6.nq.gz
│   ├── 4f386d6f9cac7b1925f46fca4c7c40749e0d1c63.nq.gz
│   ├── 50db8204e6a592632999c3cd9af48816f247dcc1.nq.gz
│   ├── 60deb7cce8bb0b48d6c6587c3336c142a5055977.nq.gz
│   ├── 6a396044bad278bd3bc54347e61c5e35a1439bf2.nq.gz
│   ├── 73875f11bcbe2080bfbf898038c81660d3b9fe1a.nq.gz
│   ├── 766d11ecde57e38539ab8b93250b65f751a78a55.nq.gz
│   ├── 7bdf744ce5b9026dc9236b2111123db943132ebf.nq.gz
│   ├── 847168540815eae771499106912bf4851628555a.nq.gz
│   ├── 8818299911e84339d8c3cf0a4ee4097f5d66e2f7.nq.gz
│   ├── 889c5b7caabfabf381a1353cc746daf2a697ac13.nq.gz
│   ├── 8d566b9c13d88d1ba9974c71575cb06dad332829.nq.gz
│   ├── 8f4f759d57ff7872a4beee334337cf2297d378cf.nq.gz
│   ├── 93d5b0da9350e6fae296f3abcda49fb62423ba19.nq.gz
│   ├── 9591af2248b797ec448352f7eb469c885ee3eec8.nq.gz
│   ├── a036507fc4cb96487b08787f2f96f80a1dd49d0c.nq.gz
│   ├── a2255cb3dae6d3ff5f9ec3d1a0e6ebbd854bb8fd.nq.gz
│   ├── a6291910f45e606bfa5fca8f75bdf5f428dd621a.nq.gz
│   ├── aa591a8ab618fe121ddc763d854b6276f3161830.nq.gz
│   ├── b81aaab03a7c4b3f624b3ee08a36b8b935e3fb2c.nq.gz
│   ├── c0e27a4dd8f8d41b29719067f57f17b0582c3122.nq.gz
│   ├── c1cef9f47d01c27206dfc2d4e1b9144edeb5b1c9.nq.gz
│   ├── cd789daa234bf2c8b214339a293f5668cdd5bfe2.nq.gz
│   ├── da10e0de14ba07793e4f7569751c721eb185727d.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── efdd10c014846ca41d0eb9bc8dadb01d71c57854.nq.gz
│   ├── efe1d2e9483325c4faaa9f7a82a398ab39ab43f2.nq.gz
│   ├── f020d498ec5d058daaab27c32bfdd57402764b68.nq.gz
│   ├── f148550d175e42d45fd74cdde3c2a177559c91a6.nq.gz
│   ├── f5b59ce3e50028a30530fc4d5fa5861fa813f2c5.nq.gz
│   ├── f90ba0e67b7bebc562bf388488de2d2a655ee134.nq.gz
│   └── fc10bd7e5ea1439b766482d8c04fb4eab9ee9675.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── e8069f3f17e1593abe19dc7cc611dcc416f5505d.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

12 directories, 57 files
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

[deepset-ai/fastapi-openai-compat](https://github.com/deepset-ai/fastapi-openai-compat)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
