# Repolex Knowledge Graph of samuelcolvin/python-sdk

RDF knowledge graph data for [samuelcolvin/python-sdk](https://github.com/samuelcolvin/python-sdk), parsed by [repolex](https://repolex.ai).

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
rlex download samuelcolvin/python-sdk
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── ebb81d3b2b675cf48225047c0f85e6d6296dc970
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── ebb81d3b2b675cf48225047c0f85e6d6296dc970
│           └── chunk-001.nq.gz
├── blob
│   ├── 0552f2770e53917be244c4dbc39f06ec4bcd5702.nq.gz
│   ├── 05c32c6053c1edd9a2faaf1b6ebf565c6650fa28.nq.gz
│   ├── 06020b4b0e2e822d64c3d58fad2b68a08f718c7f.nq.gz
│   ├── 08b3e65e12569144004934db639be012e449aaef.nq.gz
│   ├── 09bc600d01c58764b65fc41efee52ef830483f1a.nq.gz
│   ├── 0d3c372ce78af6c7b1162421dd02dccc6a2098d7.nq.gz
│   ├── 0df3d2fd3cfc700f99be0224d9735acd26ac163a.nq.gz
│   ├── 0ec1d926affe8b310c8a375368ced8ad3af3cd76.nq.gz
│   ├── 0f3039b554966ca11b8251e1c25bfe35992267c2.nq.gz
│   ├── 1143195e599acde0ba391195a13df41d82f4b026.nq.gz
│   ├── 1512e11ded48e893631e9cf590f5e61236052f23.nq.gz
│   ├── 17889d09ca3ef798c271893ddb54adc0465ca140.nq.gz
│   ├── 18d9a4c5bd236c0e3d7f60eb6bb240fb42907403.nq.gz
│   ├── 1970eca7d320afb498ee60e20eb7986d0d523525.nq.gz
│   ├── 19ea5ede2abce21734ee5feab030a06d793e7cc7.nq.gz
│   ├── 1e219fc11e75052fd4779d242ef243052e5f4792.nq.gz
│   ├── 1e8696858ccfa83e9c197db651234d66dfc64021.nq.gz
│   ├── 1ef968d409f25856a7c096592d67c1c956f036c7.nq.gz
│   ├── 27f02abf7bd03e1def22d7cac19b2f12bd3426e5.nq.gz
│   ├── 29470ed19cbea986985aab8ce7cbd4ed1230f3c6.nq.gz
│   ├── 2aa6c49cb3bd9df304f3105ea587c6c390120b75.nq.gz
│   ├── 2bc386c9670d083567375ad6129c595c74152580.nq.gz
│   ├── 2be9f129c430bc0e770ba67d80f96ee439ab0458.nq.gz
│   ├── 2da93634cba32eb9f49ec1fe4e5505ac7c788ba4.nq.gz
│   ├── 2eaa347585a3422049a8c3beeb660f096f8ad328.nq.gz
│   ├── 30bca72293ee14cc7ea8ea6546e6475481a606f1.nq.gz
│   ├── 36cbca32c9f4d32175a2f05cc0651b31edd45c0d.nq.gz
│   ├── 38384dea88e816b5e86eff37f8f0e3989bd18916.nq.gz
│   ├── 384e7676007cd67f39d2532e7e20e7ca7ee37497.nq.gz
│   ├── 389e89624e0d5013983eec90568b5dc7df8e315c.nq.gz
│   ├── 3c17cd5592f83e95338faff2bb30585004729d20.nq.gz
│   ├── 3d09b250560c0401ac77782f786a9e4f92c4925a.nq.gz
│   ├── 3d48435454b105021b4f777c11b6b07d8d2ffea3.nq.gz
│   ├── 3eace52eafc7e2bdcd71abe7af291102b6cd18dd.nq.gz
│   ├── 3ef56d8063423b5851dc63ff3d12339065a91600.nq.gz
│   ├── 40afaf801a44758997625ef9031dd2d23597fdc7.nq.gz
│   ├── 41d3cc62279715d4ee7447d6637e9cfb7ede7b63.nq.gz
│   ├── 4423e53159a13f0681a0cba4f7b8992d8154e411.nq.gz
│   ├── 469eef85703f030cfe61c92d658c949c6cf2fe86.nq.gz
│   ├── 48e796e1985d2c915b54da6b168fcc68fb141f8a.nq.gz
│   ├── 4adfc47bfa064bc972f71706d04e9dc6eee91ecd.nq.gz
│   ├── 4fd4befe8012f4f56a889002ccbbd85653918597.nq.gz
│   ├── 51bf3521ddfba814a79741fa90060f0c49795932.nq.gz
│   ├── 54006f93f2d4f4a0fc0ecab0b7fdcbc20e595efc.nq.gz
│   ├── 58a2db1dfae93c950115954e5942d5e89df24378.nq.gz
│   ├── 5bfc72bf68142f99f90485328b87a1b390e63ed8.nq.gz
│   ├── 5d375ccc8be2568c0e1f1c4b81a8ea048386221c.nq.gz
│   ├── 5ed4dd55f5262113a3469dbd4824a101ab6b91db.nq.gz
│   ├── 63759ca4ccaf1a2efe3271cb3f17858f631ce3da.nq.gz
│   ├── 6461648eb11755a495da4b5628306165f4dd354d.nq.gz
│   ├── 6555a1c2d8e0a2f9588b89308a8dda2bf9acfd55.nq.gz
│   ├── 65cf061ec5311e9ae2db2585fd2b3220a9c70ca8.nq.gz
│   ├── 66bf206ec1be59f01a9354b8b78b433aa4ca2a37.nq.gz
│   ├── 66df389916d96b19e2e2c943f6d257a81e3b90a8.nq.gz
│   ├── 683e4f3f52e5fef9bd25ffa0c6c7c175812a5f78.nq.gz
│   ├── 694b49f2fadb2cae7403cddc8b0f6b1749854deb.nq.gz
│   ├── 6f38043cddf3d5b5c1468b1c5874e96bae4c772b.nq.gz
│   ├── 762ff28a49ca2b638bcccabf87315a3ca8f3065c.nq.gz
│   ├── 763726964c234f9532a88edbc06ade78cc94c6b1.nq.gz
│   ├── 7bcc9bafb0987e1b7be5aae50aeaca22e96ecfa2.nq.gz
│   ├── 7bdbcdce6bd497d5096a3c4877b6d7eb95d23822.nq.gz
│   ├── 7ccbdef369ecf8c098cb047d2dbc022f32f78a0e.nq.gz
│   ├── 7ceb103e5b616d3dcedf02b913dd9f9c172fd40a.nq.gz
│   ├── 7dd6fefc1ecb3a7def504a936f134a95d194ed73.nq.gz
│   ├── 7f9131a1e0130226182b8168d21bb838af971187.nq.gz
│   ├── 8053c6cc5ea99e6a7d7e50c49fe2060bf9a65140.nq.gz
│   ├── 805b0f3cccd6307c267379a76cdebd89acbc5a32.nq.gz
│   ├── 84b052078adfd54786ab6037454ebaaca7f39a1f.nq.gz
│   ├── 8609c209ee40b89981e64dca01d59ea4970f2854.nq.gz
│   ├── 87129ba91282cca17b0b6a85cf2b3aabafc8eb93.nq.gz
│   ├── 8b137891791fe96927ad78e64b0aad7bded08bdc.nq.gz
│   ├── 8b345fa2e5b6bc99facb44d15ab5edeaeb690880.nq.gz
│   ├── 8c09400cce6c2f2b486ba990647950720e6b954c.nq.gz
│   ├── 8ce704ff1958108412d9d9ddec113710f53bd160.nq.gz
│   ├── 8fd71b263b348bae5b79f5f9f4461c26c2db6e85.nq.gz
│   ├── 8ffbe1ec47276b398a6f62dd1358263e5c806686.nq.gz
│   ├── 91819a7de9027f8e971f5ef9526694b6bd6ac0d6.nq.gz
│   ├── 9188dd945eb0981cf8773ad9c7fcec276d4612bf.nq.gz
│   ├── 929e5f5041e90917573a036c57e11fbc2dc201a6.nq.gz
│   ├── 95747ffd199505a84d2dd569963cec65f33746cf.nq.gz
│   ├── 97a1c09a9fea4f2cd821223d7ae4ed8c97072ee4.nq.gz
│   ├── 98f8e1fd5617e4e3997224e3c3b3c0639c50e6ba.nq.gz
│   ├── 9a8bba8d4b22c8409d4efd8af8d4f200b3fa0b4e.nq.gz
│   ├── a0c32f556c08624f9dbf42b0039928e125f65a89.nq.gz
│   ├── a28fda7faaab98c0b9b9cfe057475ec4bfd0bc4e.nq.gz
│   ├── a39d33412d561967c70542a6db1e8f4c661a3971.nq.gz
│   ├── a69f586a5357844496bbed4766115f9affb05fca.nq.gz
│   ├── a7e7a8bf13236f9da3e5e6ccfe5916e9e16db35d.nq.gz
│   ├── ae9c6561920aec8455b3d336bed7db79e3527dff.nq.gz
│   ├── af7e479932e6eae76c6026a747ce463cf81902ae.nq.gz
│   ├── b097fafbfa9e61cac25ba58bab59b7071ae2c06c.nq.gz
│   ├── b2050e7f8754e6a7e3159f0e834bb6a6218ac7d6.nq.gz
│   ├── b5805fb348b37459883a10d0c99da21541db3a4a.nq.gz
│   ├── b8371e4b1bd48785650ee4e372dc25b9270fcc9f.nq.gz
│   ├── ba586d4a8721c3762bbc0bde9ffec550ff8e238d.nq.gz
│   ├── bb47d6d3822fff0647e037d283817cb2e3b40e9d.nq.gz
│   ├── bbcbbe7d61558adde3cbfd0c7a63a67c27ed6d30.nq.gz
│   ├── bdc5160a2c9a3b55b672d127b89be4ce5cf006f7.nq.gz
│   ├── be448f97ad864565ab62efb9807a263210530d0a.nq.gz
│   ├── bf68dc02b7021b41bb76a8107a8f4e900287cdee.nq.gz
│   ├── c01e1576c257c63393de1840715314404e1be98d.nq.gz
│   ├── c12c2637385ef35e02c30b96b33074f04003ff6e.nq.gz
│   ├── c22dcf871b25da63213028b5a8cf83ec9f5b0c6f.nq.gz
│   ├── c26152646ffb3db6667e2476184a42b28ea59266.nq.gz
│   ├── c51ecb253c2131380deee4f86bf5858e5dccf89a.nq.gz
│   ├── c64a4a564fad1b8d1afcdb82a628e7b94b8f7e3c.nq.gz
│   ├── c690aad97ae500bcb56e88af88c1a97e7a7f21e6.nq.gz
│   ├── c8cfe3959183f8e9a50f83f54cd723f2dc9c252d.nq.gz
│   ├── cbab1ca478ec5eccaee6552f701eb6f5dd037761.nq.gz
│   ├── ccaa3d69a247575e33968fc242631a3ee92353a1.nq.gz
│   ├── cdba4ce646ec2e8aa579fecda72da6c17ca15550.nq.gz
│   ├── d08dabc936040dd0098f4586d03152f7c6210c6f.nq.gz
│   ├── d1c522a8162b808c348d8b3f962b8bf361a2a88e.nq.gz
│   ├── d88b8f6d2d61f661f3979f89c57d28033ac2e2ca.nq.gz
│   ├── d9fe2de6c82c2c5a3fbe6c131c2b225a84de1e45.nq.gz
│   ├── dbc890815065449d933096217a5fbb6889e0a6b4.nq.gz
│   ├── dc56e918216bb0ca2b741b9366e27df5a0b25bba.nq.gz
│   ├── dd84ea7824f11be1eeda22377549cbc1aec7f980.nq.gz
│   ├── df674e91e4e7b2f56463b5e67cdadbe8ce34a592.nq.gz
│   ├── df9da433a21fc61a643344fb5786a63b347214f0.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6eff3d46326810e52596461956634fc4764e7cd.nq.gz
│   ├── e859165a97c26403a8b5ff8a63f30478a952555c.nq.gz
│   ├── e95b75cd58f7cc62e79ea17620d3ff05de5a02dc.nq.gz
│   ├── ee7cb2fab79becd077ce36b3c61ee41e54ea76f9.nq.gz
│   ├── ef4af84cb67e4604c8379c8d29f7b56c5051c116.nq.gz
│   ├── f2107d6ba412d8403d90cab7eac52f835040f512.nq.gz
│   ├── f352de5a0ae5a8db5c181d1b5c17cb89d485a45c.nq.gz
│   ├── fb5bda106b26051b68b00e95cfbdf5e3c52e08c1.nq.gz
│   ├── fd05c77371db986975b435a6c8864e99eef05ae5.nq.gz
│   ├── fddf83fa767819f66715778de7133ad2e8d0b457.nq.gz
│   └── fe3f3380a4d5a1167efc0ca73737b2940f639938.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── ebb81d3b2b675cf48225047c0f85e6d6296dc970.nq.gz
└── tag
    └── tag.nq.gz

11 directories, 138 files
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

[samuelcolvin/python-sdk](https://github.com/samuelcolvin/python-sdk)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
