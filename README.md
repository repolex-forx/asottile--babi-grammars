# Repolex Knowledge Graph of asottile/babi-grammars

RDF knowledge graph data for [asottile/babi-grammars](https://github.com/asottile/babi-grammars), parsed by [repolex](https://repolex.ai).

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
rlex download asottile/babi-grammars
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 4f4e49f99d8d18ee543401a967cb1e30fa0dd5c2
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 4f4e49f99d8d18ee543401a967cb1e30fa0dd5c2
│           └── chunk-001.nq.gz
└── blob
    ├── 00b28c01afc39691f678569d082db592167d0d30.nq.gz
    ├── 026f7a7ecbc09e30f84d295992cb213844c93b85.nq.gz
    ├── 0323b353d2879071b00d102b387697667057f10a.nq.gz
    ├── 03a4c255f3af9bdd892673bbc1cc2530567108de.nq.gz
    ├── 07657791aed1e64f37fcb1a6c9d50a3e445959d6.nq.gz
    ├── 085537a963497593a41557950fd1ddde5c3fce71.nq.gz
    ├── 090d95af6a1723e9bb0144ed9e7d2741abd30da4.nq.gz
    ├── 09771c0723c00c9464009ec3736c52ffbfc6191a.nq.gz
    ├── 0a4968c108c218fbb2dc74028c3985c8feed7d67.nq.gz
    ├── 0c888322a9f7c2665122735619e9fc00452e4822.nq.gz
    ├── 0dd677ff566c28bbb4324b189c151107fa646650.nq.gz
    ├── 0e4d8c99198be278a715e793189bbb7e5ab63a0d.nq.gz
    ├── 0ee4ee75aa379703dd11dac88346f85712473e6c.nq.gz
    ├── 0f387eb068a6f81438bed49cfdfebe46b8b7e7a8.nq.gz
    ├── 10e4c14dcba9f9ce548e96374c1e2bbf6cd908ec.nq.gz
    ├── 111097896ac9530bb8f7bc72a85268b6c6916e9d.nq.gz
    ├── 115d6af9631c961c7e158f7418718cefd94cc278.nq.gz
    ├── 12a794f5529c92451f87a77744d76dfad7b28d59.nq.gz
    ├── 15dbcdd295984f6e1df385a49fe2cb671fd7c1b6.nq.gz
    ├── 16b4228277bf41f93d3dd2ac7299dde56c4885e0.nq.gz
    ├── 16f4cb8f228a17561f91919d734ed2a84ea6912a.nq.gz
    ├── 171c1e43145de39e4f8bb2d07f68cf2fde068431.nq.gz
    ├── 175c332281d7232781a8966eb44997b4b18a4b57.nq.gz
    ├── 17ca397e7056ec9a64b274fa431964d27f2a878c.nq.gz
    ├── 1c795de16b1bea05b711014bcc3d773064bf3adb.nq.gz
    ├── 1d6e2fe1ec8d031448147cda591d7a7ffbc1354b.nq.gz
    ├── 1e4cbe5a40e4ebb23a3d30e399c7fda70f0c4c45.nq.gz
    ├── 1e6060cbce6ef20dd2bda71506e26b270362368a.nq.gz
    ├── 1f462cd0ef387c54283d64f36e2de9f348dddc76.nq.gz
    ├── 23de4b92e6a2b872fc19512fd3cf00d935c019cd.nq.gz
    ├── 259e332e6ac3093c428501f5221dfd79515a8ba0.nq.gz
    ├── 25d5d855a153fcf38c68d2d8242d04f7fbe5bc9e.nq.gz
    ├── 26c14e24ed1e35e77646e1196c7790955e954504.nq.gz
    ├── 2982c05afe28c9eea31e0d6ecf5f34ed950d60a9.nq.gz
    ├── 2aa7c9e1ecf75049e31044d1fba389c2cb152183.nq.gz
    ├── 2b1dc7dcf19d577c258b9bedabadd5aa0044f729.nq.gz
    ├── 2b2e79f8339f18bb59a8a68aaabfc931ed38b188.nq.gz
    ├── 2bbf5810e3cd2aac9fd26839e343968d8ab7926b.nq.gz
    ├── 2dab85ecb8a481f8b14950965ef1357a84659d93.nq.gz
    ├── 2dd373e8e477ad92ab74720a2bc6d34e0a8c1d4b.nq.gz
    ├── 2de59ec1bd42c640aebad427796b94425f5f9777.nq.gz
    ├── 2e8053ae064690145c26257d627ab51c4a63c350.nq.gz
    ├── 2fac821c952a037d1d696627f914a1536a826760.nq.gz
    ├── 307d926415aef5bd41480886df80bca9d9f70de9.nq.gz
    ├── 310a88e8471cda0fda92e4743e737535c65ce213.nq.gz
    ├── 314dfb77f0fc2bf82db7c68184a017a27f5eb217.nq.gz
    ├── 315834e23aeb279408ad4de9104ce03a86a0378d.nq.gz
    ├── 31d0d31eb83a4939fe11cc5c447429b2bb6f7f83.nq.gz
    ├── 35bdc50ee353fef6fbda8b3629193dd6182c358c.nq.gz
    ├── 39d3959ba56d7e1e37caf6f3f1e367d44f4c1cca.nq.gz
    ├── 3cb30976dc260574f96ae21917f15938e3193d5b.nq.gz
    ├── 3d93aefb2da505dba9c0114404cfaaeee5ad0d3f.nq.gz
    ├── 3e73cc5d08230dfc8c593df7ac03bcb3d74797ae.nq.gz
    ├── 406dd666e535e0cbea6e7e3d63c37198db7fe94f.nq.gz
    ├── 4193775238f6bab724a428570f1c07f13a9d0980.nq.gz
    ├── 453ec34af6fbc6f2880718f2e7f2a256a20281ed.nq.gz
    ├── 4581892bf6c9cf88777a5230b56a4b9aa156d427.nq.gz
    ├── 45ff28a2c66d3afb07b03b23c758c948ed8793fc.nq.gz
    ├── 47a9b8f1a20f6becfd5a855433d822e20a988af0.nq.gz
    ├── 47b35e123a687a95a39403c08baa1816c8a657be.nq.gz
    ├── 4912b3d1fc68710db9d43f48e235f7328775c2c2.nq.gz
    ├── 4957052074a217bf3895d920224cb948cb9112f3.nq.gz
    ├── 4967aae7f08e30f83d3962aa6a04aa0c27a03af6.nq.gz
    ├── 49cbbfaf4ada364bfd53d1355b96ebe8cbf690d6.nq.gz
    ├── 4aceaa355a1ca5fef40abe418bf1c5a83f4d5465.nq.gz
    ├── 4b20edc4c2341a383bb691b69d3f53a2afab370a.nq.gz
    ├── 4b2c4a6d13f758705be4eba4f1028b070d109f74.nq.gz
    ├── 4d831b582f208dd7b112c18b69148ddb13b64bb1.nq.gz
    ├── 51da641257a75ea0dec68fd87d5d82b0c09de45d.nq.gz
    ├── 5337913ea7cb9d4417fb1a9565bcfb3c7ebdb63f.nq.gz
    ├── 560b50d372a1c297ca2688af6b753467b007aab3.nq.gz
    ├── 56fa7ce93a4855e910668b236f5eadc804da45b1.nq.gz
    ├── 5762805961a253f2ce071b1522f03acd1966b6d5.nq.gz
    ├── 59230055d8d598780e2001ef76f9d1127d342ea9.nq.gz
    ├── 596400a80f6bc7dd53c30451b0c078667b986cb4.nq.gz
    ├── 5cb66a3e64517496cbc19a2634ef0f580f354f94.nq.gz
    ├── 5fe9195270ee08f828ba81f951e083f0703bf3ec.nq.gz
    ├── 641026edad3be71c773a9a07a4f6378b8ad5f69d.nq.gz
    ├── 641e2a217ed65cd800b1c197ef3abcd57259894f.nq.gz
    ├── 66ed03d4c4bef5eead558096a44d59fe8cc0d732.nq.gz
    ├── 68819c3031a2e07a4e6705c2e9735ff23fe781bb.nq.gz
    ├── 688a15a89e08825bc7728d308453d515b44f4533.nq.gz
    ├── 69a0b2e2398eeee096ad56d644f09685dd1b0a70.nq.gz
    ├── 6a6f80cf1aa118570962b32b81f0b3387a56e0e3.nq.gz
    ├── 6a7bf12e59eaa01275d9441c86b2be6f4771e629.nq.gz
    ├── 6b8236a4b6ffa069c8f000bd8bf9d39bd88240dc.nq.gz
    ├── 6bc9c9d46d317bebfa9bfead72378b05a2b70290.nq.gz
    ├── 6cb1b6cad50b28f2bda1b0e88b4d96cbd75028e7.nq.gz
    ├── 6fa4062b060f7a9dbc34f8fd0654db6b85b2dcc5.nq.gz
    ├── 713b7e494e0cf677ccc5d8c3b5a6f800a2a4832c.nq.gz
    ├── 71a7ba94e07997f524ce51d0b2874adbbe7ea474.nq.gz
    ├── 73107eaa0a49c9b0e720bbfc156b2b360b5e2736.nq.gz
    ├── 738587fb1cfb593d53d305a82ef69a47a23347af.nq.gz
    ├── 751686a3fedb4b74bf3eb24cae03246ac7543a73.nq.gz
    ├── 7519cf0661e36f6c4431b44bcc5d0da8e32f53dd.nq.gz
    ├── 7575abfaa20188283d92b062c496c3a643dc3761.nq.gz
    ├── 77da7585d6a65c1bb635e4cc5bb37080deba577c.nq.gz
    ├── 7815e0bbc71841a86e8260889c24c6932c0e505e.nq.gz
    ├── 7850d561b3fb054f5b20657d5165738691ec0ca8.nq.gz
    ├── 793600c5f9d05f9c1fac1c6354fda34dfaa26d76.nq.gz
    ├── 7a6e1d3a5bb9ae36b8459f3f40b208ac5f712ce2.nq.gz
    ├── 7aa15fa9973e9a9738736efd7118125b2e6fe75d.nq.gz
    ├── 7ca6806a9255668881718cdc3c680205b8463c48.nq.gz
    ├── 7ce0c99fef2ab38f41a41c757cb34f0eb36ad7f7.nq.gz
    ├── 7e8a804d51a8c2635de5b088d73026931bb75813.nq.gz
    ├── 7f90895037dd403f12457755974e0cfb08bcf68e.nq.gz
    ├── 7fe0e680ac1ebe87f9dedd925303f7424bd748bb.nq.gz
    ├── 81bc640782e6f0de2a3f10ff0689c39fa887716f.nq.gz
    ├── 81e0b5ea9ecd1d0edda48f7bb12dca4cca5d9c7b.nq.gz
    ├── 82524c1334ad07553caac57098fdd42270736479.nq.gz
    ├── 842c1cc1509513339c8ebe081347a2131b447b9d.nq.gz
    ├── 84b0b516803f4712bd0e733803f8b8a9012e5d8c.nq.gz
    ├── 852c557ed2675f7b678e06644355dd56b597bde2.nq.gz
    ├── 8628b117dbc82e19d7f249a8ac31602b3dd2662b.nq.gz
    ├── 867c0411db75cb7be4471420338810833b7da9ef.nq.gz
    ├── 8763d82778cd8475e232b0b79c6662e045ea10cd.nq.gz
    ├── 8951dce5db0e9b11688037fdb15a1284c897fc90.nq.gz
    ├── 89bb5fe272fcdf41265ce23d01aa987c8e312416.nq.gz
    ├── 8a91eb32fa2d7e0bf86589816bc20762f83fdb27.nq.gz
    ├── 8aba102fe1777547803b99ba79b70d8efae8b7f9.nq.gz
    ├── 8b8b92e1fea83afb214d9253fd52fd2e3f670ab2.nq.gz
    ├── 8d1e498ba36c5ea6ef4ad0f03c2294bf2443a60a.nq.gz
    ├── 8e155c664f07b081ddd84bfb529bd5ede31af96d.nq.gz
    ├── 8e3b48e929897b9c827215830818547166ac77c6.nq.gz
    ├── 8f12410f6507f7299d3f3add050565bde7318f5f.nq.gz
    ├── 8ff4b924ed92c6d831b5844503cdcb000f3887f6.nq.gz
    ├── 90b6089144bff78f2abd5d96b06d64bef43b91b7.nq.gz
    ├── 91392765bce86a3e059247e6c8ed078bf1c7b84d.nq.gz
    ├── 91a503644a6ca57745b90d57c0a40b3314fe2f36.nq.gz
    ├── 91bf1d396efd24a48de5fb893818d9348ad839d5.nq.gz
    ├── 92a8bb3bca5f9ea6e5fcc3e4f6f1ff466ee3cdbc.nq.gz
    ├── 93f95d62cdf221a6dc50594fbb32c3fadd47da3f.nq.gz
    ├── 946b2bfcef61d2890c8f331c1106be34468ea60e.nq.gz
    ├── 9611db3853d79819e63fbb58fdff83a5f6ac6dde.nq.gz
    ├── 965d574ab607d18a11d9fd0e73c776706d595b64.nq.gz
    ├── 96730199173530104f99accc96d7035be7e8d360.nq.gz
    ├── 9aaee557f8b4f652756daa5d376c066d8beacfe0.nq.gz
    ├── 9bd0194ba1b3e1de3b6a40d0e3e6403340c7b6b9.nq.gz
    ├── 9d6a0efd6bce15eb2fdd261b2f30ba9cd03f3f34.nq.gz
    ├── a0444296e98899bc1a7af466fdb7ff7deb99a398.nq.gz
    ├── a2495b880299d75e3a30766a22d335b36562c03f.nq.gz
    ├── a30400e4fc6fd6b5a28162475080cec677277a92.nq.gz
    ├── a350aa81dbf4bc904aa9608a2b8a161a989ee1a3.nq.gz
    ├── a3daa62c23419e78e613eb099c26f07cbdf4f9ed.nq.gz
    ├── a3e4eb3b4c05c188e8e22142080a17086426b120.nq.gz
    ├── abc3e47de509b3febe50629b74245cfc9d627f6e.nq.gz
    ├── ad120ade0ad614bc0c14b0e48bf63b4cf45e87a7.nq.gz
    ├── b29acae0fb62c64a0bc18e5194106d8153d4b326.nq.gz
    ├── b52dca8d05a22002dbe9ea8c26235e7235641f2b.nq.gz
    ├── b65d0b0b9e2ca9dd0af927c30b5f4acc7fbea18b.nq.gz
    ├── b6c2693071afdfc05b396e4c087145783ad3d0d7.nq.gz
    ├── b6d5e4df9bf616a6a54cb681bdea148c36972e3d.nq.gz
    ├── b79a8aa704de96b3dc08777be2866a9e6305d9d1.nq.gz
    ├── b7a18bd82ee182cd4b997965d088f34fa62abef4.nq.gz
    ├── b934bb9c7f6e30bcfbc615f8c5d0b872ba0facc1.nq.gz
    ├── b96cb5e435174a9e1156c65e2e749133728e4f79.nq.gz
    ├── ba28c6bf1d231e69058dc173574293876eefcd39.nq.gz
    ├── bc709384ab6ba8cc942e377b7f7714ad9f98f298.nq.gz
    ├── bcc6196900eb2a25a1afd3cd829dbb2f5082483e.nq.gz
    ├── be4ac85308861da6e53b890ab4ad4706c06986b1.nq.gz
    ├── c0dbdf4727f8b3addd3ee0cf649ac609eeef26f1.nq.gz
    ├── c2e0446c7d8ab8b35edcdbf7f218968c9721b2ab.nq.gz
    ├── c340f3d3b6f9f0ad317880fff478b059ecb48811.nq.gz
    ├── c4811ca964389c6a3a0ac6de8fe77659b2da0974.nq.gz
    ├── c51a7ed4765f092cdd917f86107f2c5f0bbd4f55.nq.gz
    ├── c696d104d8652b9f2f2c5bbe72b2378768469119.nq.gz
    ├── c7139d020b0b37a15f39b7d37909213223ff33a2.nq.gz
    ├── c950baa753f07afc4f64fcb70a7388716a50ccfa.nq.gz
    ├── ca78dc90c439ebc9e877a1d3f7636491cec2c48b.nq.gz
    ├── cccd1cba231ee38d11877ba20e94162b7308e7c4.nq.gz
    ├── ccf6cbefc7772ad88c140198abdf12d4adb653d7.nq.gz
    ├── ce71c5575acd791ae2eeb1a0a04de63296e9ed19.nq.gz
    ├── cf841ae7a1bee2b74307a124a75534a73e92a360.nq.gz
    ├── cfbdc821cd84099f8565d1e4e96be760360c5a06.nq.gz
    ├── d02c7f8cb6529e4526896167fa2deba28d87e182.nq.gz
    ├── d18058b0b78dd517721ccd519dcaaf4ea9612180.nq.gz
    ├── d2929b9ad2b320aac8e05b61f80a626c9cad86e3.nq.gz
    ├── d3251cbd44706e1569051e4b3ad39ef0a6e3e7cf.nq.gz
    ├── d33dc32d68b874aabb7c535832081194dafa9d55.nq.gz
    ├── d720593d1f468fe58750e3239678003551466bc5.nq.gz
    ├── d7586c569268a1da0c7ad9582b5d83cca29b922f.nq.gz
    ├── d81a5f13a456a94cfbcf891788a56d52fa5c7613.nq.gz
    ├── d8aa3f2d48bd7e9733e74d41242621637222d048.nq.gz
    ├── da2022b887221995d3453bc0b87945d856e33d9e.nq.gz
    ├── da7fdb13d8c60ce386bf1bb7a1191894949aa104.nq.gz
    ├── dbcdefaadbc94e7706fed611d42852721d8116d6.nq.gz
    ├── df1b0d704c84004ee3112b9744003c2b9915305e.nq.gz
    ├── e4b217ca650bc1101052a0953e96662f3bc6f3ab.nq.gz
    ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
    ├── e88783ea9d1c5763e2b746c7269c9ff0d4832794.nq.gz
    ├── e8f53ef8d23f4ec9003654bea49cc031e71f0b01.nq.gz
    ├── ea0a978d96f49674b173b939f52e47b9cf952e24.nq.gz
    ├── eb1ab0d21e54a7ca2c540c37cb6a8e18a8082cee.nq.gz
    ├── eecb1cac85e680ba4533eeb9fe1f28fd8fb33c7a.nq.gz
    ├── f11ab0bb2bd72ae9e791ca55968f94d754f1a66b.nq.gz
    ├── f2ac3c39c16b7dc5332e80140570fa5b548a9d9d.nq.gz
    ├── f33e2096272b7d3a633f2cb8a4dd8e00fbd197f1.nq.gz
    └── f59294f8cb9029b222c34ee75f7a010beb3022e1.nq.gz

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

[asottile/babi-grammars](https://github.com/asottile/babi-grammars)

---
*Parsed on 2026-10-20 by [repolex](https://repolex.ai)*
