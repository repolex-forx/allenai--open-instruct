# Repolex Knowledge Graph of allenai/open-instruct

RDF knowledge graph data for [allenai/open-instruct](https://github.com/allenai/open-instruct), parsed by [repolex](https://repolex.ai).

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
rlex download allenai/open-instruct
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── d39e4247c8c9814b55074be229be8af4d368fb8c
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── d39e4247c8c9814b55074be229be8af4d368fb8c
│           └── chunk-001.nq.gz
└── blob
    ├── 000f49fbdfd2bce01c4181bd3df2bab42bcfb1e5.nq.gz
    ├── 00b204f6808113627cbc53d3e994dabef5c999d3.nq.gz
    ├── 00c6e3944d69dbea0de4c1ecc47c8e629f6acee3.nq.gz
    ├── 02104d268c25d51402552b0466c7c230421097fd.nq.gz
    ├── 02f5498793a333064236a53416a1260d885dc366.nq.gz
    ├── 038c8802d6ed78aed9c30e17e2e4e9d2ad3e827b.nq.gz
    ├── 04e899330e7cb1460caa926867fcb9858f0e6be2.nq.gz
    ├── 0542ec9a08bd34a166204a83293f464ce6752736.nq.gz
    ├── 0643c14c57c5ff341d0ba029e1c2a04e09a66561.nq.gz
    ├── 0659cc7f22b5f254a05d8f70e7109cde5de06cae.nq.gz
    ├── 06613abfd74f0d1bf0830b92403ab0fa21031568.nq.gz
    ├── 07a374bbdf5c01d8b2ada97c003b2acf80c45344.nq.gz
    ├── 0851fdea79868d5b8f5642c15dc915812c3d02d1.nq.gz
    ├── 09009909389e0f30b3665d3b878892c4c01d22b8.nq.gz
    ├── 09e0809301f2917eb6fcf8742d7e95cbe5b3d04f.nq.gz
    ├── 09faf4504f4778ceaca0e686b79cbaaca8c73bbc.nq.gz
    ├── 0a1b7fca5c90ad0054a1164367f9eacc32f9408b.nq.gz
    ├── 0a634c4e14a08a27b2c7987dca3172d90ed94ee9.nq.gz
    ├── 0ac44bfb9543070a03bab6a4171586a329733f2a.nq.gz
    ├── 0b4644d2bf908940e04f85dd1422cee062c99843.nq.gz
    ├── 0b579ec1740e5a17962c0a416465f5b061a8b16c.nq.gz
    ├── 0bbab34690e292fe0dc2fb58bb7494b677bb49a1.nq.gz
    ├── 0bd08c79d9c825693d832902cdaf3e1a8db6011b.nq.gz
    ├── 0c4f790bf3e5789c0f4ac0d4a64574953219de24.nq.gz
    ├── 0cbaf49f6c6b19adacb4839edfcbb999a75cf9c8.nq.gz
    ├── 0e7bb626a84ac9ef5a27af63f0885ff83a1803bb.nq.gz
    ├── 0fb87fe25cce4e0c0eceed1d491a8a505a69f4e9.nq.gz
    ├── 101ebba4d1bc2e99f16b2dd7e8b9e18d0867e6ca.nq.gz
    ├── 10d449542ca9b4554deb5870545de78123e5cd7c.nq.gz
    ├── 118a7db4fb6c44edd97526f29eacd6273e780e5d.nq.gz
    ├── 12aa04d259fb76c919725458be1df5edaeff74b2.nq.gz
    ├── 12e5ba1fd824466e0e28211d341831a8417ad13f.nq.gz
    ├── 14250a4388923f72a3b6f169a7895d92bc93e66f.nq.gz
    ├── 146024ad644c9978d364a1399582ebf8c171b577.nq.gz
    ├── 154f84cc76b8223055c60094cce702e04930986f.nq.gz
    ├── 156d5443fc917c13242d99380d688c1dd520f6eb.nq.gz
    ├── 15dc2f16492b6050a6172cd8ed583929eed8a720.nq.gz
    ├── 172e91bf2af87d4fdfbb5efecc0003df79769155.nq.gz
    ├── 17301bb50a7ec0025ec8b040ad38e6dec1f13508.nq.gz
    ├── 173c27cbe1b2958b73e92dba9b6676105be674bc.nq.gz
    ├── 1861e7160b2ba2e93a3c9875d70ba073aac50453.nq.gz
    ├── 18a3bcafcee2a0c5917aff6bb48db26f7b3857c9.nq.gz
    ├── 18e7200a0fb80e80815e056044c83c48be2dc490.nq.gz
    ├── 18ff582d529daa4488dd1438385c5b758c51f9e5.nq.gz
    ├── 19571b7dc3167d959752f1a4933396fbeafd5fa0.nq.gz
    ├── 19f0d5d4c04c933ad4ba47f62357f733a11a3b82.nq.gz
    ├── 1a5309a3e3e444b7443171e3b7cbab9b78091a73.nq.gz
    ├── 1ae3f25df68a16f4e3e5d0927044b53abaad5f2d.nq.gz
    ├── 1b12954d37f987b5264e72ffa09fe5229985a729.nq.gz
    ├── 1b66624a44212da49a63c190ea7062fcfcd1b30a.nq.gz
    ├── 1c21086e8c043b4dd057c4af777f783802b91e3f.nq.gz
    ├── 1cec880fe8d2df35d87eff9d3eba5b652f03a525.nq.gz
    ├── 1cf0bdcea066b3480aa5688e94623ffb2f90bfa6.nq.gz
    ├── 1d22b1008f48994a9a1e2ba8de4b68d45a51e407.nq.gz
    ├── 1d72b17a26b50949453f8a93e4b197b51d69787b.nq.gz
    ├── 1d8a780447698f4726a99014a2afa02689986dcc.nq.gz
    ├── 1d8c1c32c905fdfa7dcc33d0c2f93f60728e7f9f.nq.gz
    ├── 1dfb1d9eecc52b4509284761d082f49620642202.nq.gz
    ├── 1e1261b0252aeb002c885f67f2b0397172f9fb4f.nq.gz
    ├── 1e41c7771a7e7b0af73236371c84dcc17f38020f.nq.gz
    ├── 1e45e8aba2db1406a3990bf9633af0ccfe95f039.nq.gz
    ├── 1e8dc3335d465aa2e3985e5dce5671f16731d49f.nq.gz
    ├── 1eae46d8986dec72fd1f970bc77325f66ca22d82.nq.gz
    ├── 1f4c60f160e40da8c37107f8fea027b496992380.nq.gz
    ├── 1f5ace272f5e98cf2be4a3695dc1bedfe26740fd.nq.gz
    ├── 2016484c86ba933e67f92229d2dc30efb2db5df1.nq.gz
    ├── 205f8dd51d488f35a2954cec15505f0185d55760.nq.gz
    ├── 208b7978b08eadff8e2a8ed59d6757f4c3ecbd35.nq.gz
    ├── 208e7b7c45108cbb79f2d60989c8b0767a1483ce.nq.gz
    ├── 20da90db105aaefdc2a074d10e719396fc58a2a5.nq.gz
    ├── 217e36aa62d4865a07f43063087e2d4bb4104419.nq.gz
    ├── 2235eaa2d0284229bba8759ddc97a74cebabe7e8.nq.gz
    ├── 22839eb417efbe9982f86b6213cdf4f93d450bd3.nq.gz
    ├── 23b61a8f1142745f4464292115184ec5902ac6df.nq.gz
    ├── 23da8161a97a38753e34299ef0ab0cb7ee70db2c.nq.gz
    ├── 240c1f91a6ca72fbf47810a293203e6c41c51ed5.nq.gz
    ├── 24c49d40f7ff22fab153c137c592f1db2ebc0a6a.nq.gz
    ├── 267bc7710a3c52fc39119824ec4a2666ec8782fb.nq.gz
    ├── 27f91c9c0febd1aa473cd870fb8db93d595db7cd.nq.gz
    ├── 2961b88ad0e7dfb74b7c16d7d3bc483af22a4a28.nq.gz
    ├── 2a143df8c34225fe711cd45836846bb454871fb0.nq.gz
    ├── 2a987d783868e9de6cad4f807cab273260692b75.nq.gz
    ├── 2ab97e5ed91ea177c7ab0181d8e4dd29e4dff36b.nq.gz
    ├── 2acaf8a12e51ff74c826df47d579ff84abe78072.nq.gz
    ├── 2bf7bd92bb6805d03c3e7b4324de617a9cda9b75.nq.gz
    ├── 2c00cb51fe07f7503a95cdfd97b44a5e7c0d1fd5.nq.gz
    ├── 2ca0fac7d52aa806a044de08f073e98fe8258fd3.nq.gz
    ├── 2d4e772888725455fef7fbb8dc398b2dc476c7af.nq.gz
    ├── 2db0fa0a5d86f54b055f23520e6d7ffffcd8ec46.nq.gz
    ├── 2df100ee253a3335898abde496a74d1579493bc0.nq.gz
    ├── 2f03c24b7d7b3cecab89adf46f16f0e42fe219ae.nq.gz
    ├── 2f07f5a014991331da740390632f79849387f134.nq.gz
    ├── 2fdf4bd1c553c1c0bb96d83b318facca0258b357.nq.gz
    ├── 30306f69c75d24a2e4b29a9fff4d641e2a146ab4.nq.gz
    ├── 30c9cf78db534a152bb8f754a0985084ef5aa1bd.nq.gz
    ├── 30da5f4bffdad20d96c19e8c1cf9737cff36ee1e.nq.gz
    ├── 312c424ee8d9ac159fbd0ab5e2679a9898fa91e3.nq.gz
    ├── 3180a0248b7c0249fcce430daa058dc3810fe8f0.nq.gz
    ├── 318bda11c04b39c16be204f0187f876280dbe22c.nq.gz
    ├── 3209e8eb0377b1423426b5365f095f06869ccea2.nq.gz
    ├── 328e052e5087fd73903fe6de0b1f3bf95c8f29b4.nq.gz
    ├── 32a0caccc3cb62bd4ba0394e9e51162fdcb31af5.nq.gz
    ├── 33b4300714eb7af86a2d28791460c1c40f2f3da8.nq.gz
    ├── 33d45d04d45dae021bb39e92ee048e75bc23d1b2.nq.gz
    ├── 33f11e0ab4522940b6dd222e8fc893f804e88ab0.nq.gz
    ├── 34c8d549a1a38557a94abafbc38450d38abca9f0.nq.gz
    ├── 352387008b59aa1ede152affedc96f1fe6a61bd5.nq.gz
    ├── 357ae2c59efcf063ec217ee2af8b0b4b3fd77206.nq.gz
    ├── 35880bea43780e46bf38245f766a3219becc99ee.nq.gz
    ├── 35b1fe2b7ee7ddc2a507e24b0e9f54c5e7254f86.nq.gz
    ├── 35df50a23233c1da42b7ab92fc28c4c7dd65b719.nq.gz
    ├── 36877b62a97031307ad0ed9fcea724a8eda06c6f.nq.gz
    ├── 3765d584473733266f43711ca60a8a0f2d98f5ee.nq.gz
    ├── 379c1e4363f504da921e3007082a9e9f9c47eef9.nq.gz
    ├── 3806d6f095ede1c20101e66f505525ac43c166fa.nq.gz
    ├── 380c91173d3ab9c16b47bdeabb21ae6272acc5fa.nq.gz
    ├── 38924f80fdcc481503fb2d137b51afdee50b356e.nq.gz
    ├── 38a0aaef97a6feb1ff6d3bbcc1e201a28371b517.nq.gz
    ├── 38e725886c3ece74160a7fe6589c6d931b9a3921.nq.gz
    ├── 3968898c3d3ee4e4858d37f2b71dbb4dc5667389.nq.gz
    ├── 397d6258ead3369e48f2fd9bfd5d56388fe15fc5.nq.gz
    ├── 3a12789386f966405efd9af8074f6d38b3db9a39.nq.gz
    ├── 3a48162ab61c6e4bcbf0061e1956f647e1772656.nq.gz
    ├── 3bb2f31731e39c967ac83084b13c5b0eabde8a53.nq.gz
    ├── 3bd0cb6ea638fe7c72876010961ce2b42282d92c.nq.gz
    ├── 3c28b741b59003f479a7a2ba6a031fb90852a686.nq.gz
    ├── 3c7c69025baffbb838040d92306e8e4f0048165b.nq.gz
    ├── 3d3e03185f4161a19e205b788abd6ba2cb6e4469.nq.gz
    ├── 3d44a2973059f2272cd2494ecec3ab2d80a44737.nq.gz
    ├── 3e4034e41ee913cb2bd84715e00a88deff1f8a5b.nq.gz
    ├── 3e805b66dafe77db112c69788fe98a359e76f5d2.nq.gz
    ├── 3ef3842d8fc4c8acd01a1063834e14d71d10ca07.nq.gz
    ├── 3f093c0e512b8c8f1b2747cce2a3e60c7ed16279.nq.gz
    ├── 3f69e209fedecd9c35d794ac42c7d353d382e759.nq.gz
    ├── 3fcc33306f431988375136adf1fbcdc876cd658e.nq.gz
    ├── 4016e11d8a79bd962b21b1486189229118384376.nq.gz
    ├── 40aa0a1de8aa0b7f5b36eec69fa735a64756975c.nq.gz
    ├── 40f12f165377e886ff3f8752d4e080850b5faf85.nq.gz
    ├── 411466465ff8a25134e801775e53bf9117663fdc.nq.gz
    ├── 4240e29537f2aa362000926f86c36d7ee3caa690.nq.gz
    ├── 42ffe103819c048536bb377707bb5a6e49b93e17.nq.gz
    ├── 4327329de83520c6c1894a3c2b07304ebb57511c.nq.gz
    ├── 454b8427cd757f30dc7fdb9a325d19c399770417.nq.gz
    ├── 468cf281aafcc2e55c4333392bb4b534c70d4cf7.nq.gz
    ├── 4715a243ad10bc8ba241c4f6f9ff95d1b53fe06a.nq.gz
    ├── 472f65890bb464fb218747b414a9e6b34a9110bb.nq.gz
    ├── 4742d7cfd3ece324313cfadd03e51434e42b483d.nq.gz
    ├── 47467cbd1226f5ecaae98e65b018c37551ec9ac8.nq.gz
    ├── 4814deb07b2fce2b8fa1f445284b56668b596231.nq.gz
    ├── 484cfe8e37f2f7e7156ba79f0f5baf4f1296d148.nq.gz
    ├── 486b73d700ca1c428c88b251c8205ca4ae736971.nq.gz
    ├── 48a48eccc87b9dce4959db37b60a1ec9eb2cbe06.nq.gz
    ├── 4ba90c4e6baec6c72fb073366f13bde7c19e0da0.nq.gz
    ├── 4bb58f11452e76e3089e4a0768d457010bf002b9.nq.gz
    ├── 4c04e1efa11eb476465715b50d95dedb40c3f35a.nq.gz
    ├── 4cbec56b6a5d03e4e0ef373d519ac35a71ba885d.nq.gz
    ├── 4d25f8437b60869f985c9f6a9dd697f53ca6c538.nq.gz
    ├── 4db524b236b8917688baa634caf9ac98503c5ce0.nq.gz
    ├── 4dd4a2175f7f8ff85c3cfa6a40e1e73c188ba007.nq.gz
    ├── 4e2d23008759b72aef80936294382ae8a5580597.nq.gz
    ├── 4e35698bfb1f9ba02c7918da443bbb3b38020aa7.nq.gz
    ├── 4f816101d756ef4acbe8d7cf83b8e5ce393efee6.nq.gz
    ├── 502a8cf8df84280326ab4e89c34780699662d940.nq.gz
    ├── 505687e03a1e9ac34eedb5ff039a2db280e74d89.nq.gz
    ├── 5081c25a70aecef956e7db2ba164102e8eb58cb8.nq.gz
    ├── 51710f85b72903b92da4b1d2aea843c1c21ad7d0.nq.gz
    ├── 51c8d92fc11216c7fb8369b6b258bfc61884fabb.nq.gz
    ├── 524db1c75d0c5d26c0a5d266d83cb14a5ac7bdbe.nq.gz
    ├── 52b1cb1190a57c3c5e811de3a898d6455792246b.nq.gz
    ├── 5311e29372adea153189d4b94da775dab68b65e3.nq.gz
    ├── 54911ae30a44d3863ff483fdd3d2c10fff826bdc.nq.gz
    ├── 551d555dfb5617e811327e6fa5f0365829f3f61f.nq.gz
    ├── 5582ce6b36361cb79b4a0aaa8fbaa38f0e8bdafc.nq.gz
    ├── 5583d04cf68db321d0af25c779b5abbdf0468629.nq.gz
    ├── 55b60529865385643c24571d29b2f3a30aedf0e0.nq.gz
    ├── 55b9617be979af1ddcc9203ffd0f238ea09b702d.nq.gz
    ├── 55ebdb1c9059bb7e6f7182c43205483284ca45ae.nq.gz
    ├── 565148b59477f16f5928c452f266f21ddab8f661.nq.gz
    ├── 5696e58ca40c6725fd4469fdd335e71db33f1564.nq.gz
    ├── 579a99f6a302771820a8f8c69ba9d48b8f4f0683.nq.gz
    ├── 587b331073d1f964fba78ecc786ecfbd4f6862dc.nq.gz
    ├── 5a1b7d301358cf6ebb89e626b1c9348ddc9d1bb0.nq.gz
    ├── 5a9c45bb6c832952f751d4519b7f8f0b1c015314.nq.gz
    ├── 5b7de4e8c5e946215e0f0034d728cb02bd789507.nq.gz
    ├── 5c0cf4b7ddc79c176f2b88db76666b921892881e.nq.gz
    ├── 5c2ea598bc722a0ee9e3ab7e4129fd7944593a47.nq.gz
    ├── 5d693951913d00e5688b97ccf55e6036e905903c.nq.gz
    ├── 5d880e5a5fbc9e479cffbe675eec7c2d4bb4a0f4.nq.gz
    ├── 5ec724c297ac4b947e5305df99dd627ce710d438.nq.gz
    ├── 5ed960c665b6482ef31672bb0dbbd0415a630c45.nq.gz
    ├── 5f621f6bd1cf9e34578be9ab8fd5e15dbc1e4ae1.nq.gz
    ├── 6047db6d18fd84b570710603cb59837d7838ccaa.nq.gz
    ├── 604d8f1a105723da9f5073041edaf98da2307450.nq.gz
    ├── 607c7efad63e8a6d71898bc9aecf68e091c816a2.nq.gz
    ├── 6116ca0a6264482819960f6c52c280a9590cd0bd.nq.gz
    ├── 61e7bc0154da0140235bfa1b20064f9be3c3fcc8.nq.gz
    ├── 61e9f1646d7580c54a440d308eed5312823af6bc.nq.gz
    └── 6270bdb446eaf99c1d032ea811611245fa1b1fdb.nq.gz

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

[allenai/open-instruct](https://github.com/allenai/open-instruct)

---
*Parsed on 2026-11-07 by [repolex](https://repolex.ai)*
