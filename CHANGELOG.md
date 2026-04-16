# Changelog

## [0.5.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.4.0...0.5.0) (2026-04-16)


### ⚠ BREAKING CHANGES

* update repo name ([mcp-toolbox#​2968](https://redirect.github.com/googleapis/mcp-toolbox/issues/2968))
* release upgraded docsite ([mcp-toolbox#​2831](https://redirect.github.com/googleapis/mcp-toolbox/issues/2831))
* **http:** sanitize non-2xx error output ([mcp-toolbox#​2654](https://redirect.github.com/googleapis/mcp-toolbox/issues/2654))
* add a new `enable-api` flag ([mcp-toolbox#​2846](https://redirect.github.com/googleapis/mcp-toolbox/issues/2846))
* remove deprecations and update tools-file flag ([mcp-toolbox#​2806](https://redirect.github.com/googleapis/mcp-toolbox/issues/2806))

### Features

* **auth:** Add generic `authService` type for MCP ([mcp-toolbox#​2619](https://redirect.github.com/googleapis/mcp-toolbox/issues/2619)) ([f6678f8](https://redirect.github.com/googleapis/mcp-toolbox/commit/f6678f8e29aa3346f4f73ce33cec37b4753d6947)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **auth:** Add Protected Resource Metadata endpoint ([mcp-toolbox#​2698](https://redirect.github.com/googleapis/mcp-toolbox/issues/2698)) ([b53dcf2](https://redirect.github.com/googleapis/mcp-toolbox/commit/b53dcf20694599f8b961c501a532bd122630b6f4)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **auth:** Support manual PRM override ([mcp-toolbox#​2717](https://redirect.github.com/googleapis/mcp-toolbox/issues/2717)) ([283e4e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/283e4e33172571e4b20fa6a3ea0cfc632a565e6a)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **auth:** Support opaque token validation for `generic` authService ([mcp-toolbox#​2944](https://redirect.github.com/googleapis/mcp-toolbox/issues/2944)) ([c924701](https://redirect.github.com/googleapis/mcp-toolbox/commit/c924701adede95877594423d78b7ae72fe0b9c82)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **bigquery:** Add conversational analytics tools for Data Agents ([mcp-toolbox#​2517](https://redirect.github.com/googleapis/mcp-toolbox/issues/2517)) ([2490a4b](https://redirect.github.com/googleapis/mcp-toolbox/commit/2490a4b4fb3c9232270f6f4347b8556d2d6e0390)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **cloudsqlpg:** Run `SELECT 1` after successful connection attempt ([mcp-toolbox#​2997](https://redirect.github.com/googleapis/mcp-toolbox/issues/2997)) ([6ed9700](https://redirect.github.com/googleapis/mcp-toolbox/commit/6ed9700e15f08b31e65eb0afa605f4a8ea937e66)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **dataplex:** Add support for lookup context tool. ([mcp-toolbox#​2744](https://redirect.github.com/googleapis/mcp-toolbox/issues/2744)) ([facb69d](https://redirect.github.com/googleapis/mcp-toolbox/commit/facb69d01fe0c7ff9e2e1c40804dd00762e508a6)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **embeddingModel:** Add Backend API selection fields ([mcp-toolbox#​2592](https://redirect.github.com/googleapis/mcp-toolbox/issues/2592)) ([912aa9e](https://redirect.github.com/googleapis/mcp-toolbox/commit/912aa9edd7bc3ce932828003fbd67d1a3b9c2348)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **http:** sanitize non-2xx error output ([mcp-toolbox#​2654](https://redirect.github.com/googleapis/mcp-toolbox/issues/2654)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Add Claude Code support to generated scripts ([mcp-toolbox#​2966](https://redirect.github.com/googleapis/mcp-toolbox/issues/2966)) ([a1609e1](https://redirect.github.com/googleapis/mcp-toolbox/commit/a1609e10a2eaf4ea68eae36acec3eed355b8a052)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Add codex user agent ([mcp-toolbox#​2973](https://redirect.github.com/googleapis/mcp-toolbox/issues/2973)) ([070e939](https://redirect.github.com/googleapis/mcp-toolbox/commit/070e9399c02f088d43175ce6bf343378beb7f584)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Tool invocation via npx ([mcp-toolbox#​2916](https://redirect.github.com/googleapis/mcp-toolbox/issues/2916)) ([377dc5b](https://redirect.github.com/googleapis/mcp-toolbox/commit/377dc5b00145a0044eef39314dd6b0ef5966fcd7)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **tool/dataplex-lookup-context:** Relax project constraint and enforce location ([mcp-toolbox#​2952](https://redirect.github.com/googleapis/mcp-toolbox/issues/2952)) ([7ebfdf1](https://redirect.github.com/googleapis/mcp-toolbox/commit/7ebfdf1cfc7debac020de51be1aa01c81628879e)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **ui:** Update to use `/mcp` endpoint ([mcp-toolbox#​2829](https://redirect.github.com/googleapis/mcp-toolbox/issues/2829)) ([c3059c2](https://redirect.github.com/googleapis/mcp-toolbox/commit/c3059c233502a1e99abb4d87e4b9bfe7c6ea7a4a)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* add a new `enable-api` flag ([mcp-toolbox#​2846](https://redirect.github.com/googleapis/mcp-toolbox/issues/2846)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* Add a new `enable-api` flag ([mcp-toolbox#​2846](https://redirect.github.com/googleapis/mcp-toolbox/issues/2846)) ([7a070da](https://redirect.github.com/googleapis/mcp-toolbox/commit/7a070dae4f1833671649ea605f36659675d402a9)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* add claude code plugin config ([#104](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/104)) ([5238172](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/523817249c1404dd59f52fff632a607ef37bbdf4))
* add codex plugin config ([#105](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/105)) ([0d660f9](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/0d660f9038529fab79eb69f1f160c0d6d75861b4))
* Add MCP tool annotations to all remaining tools ([mcp-toolbox#​2221](https://redirect.github.com/googleapis/mcp-toolbox/issues/2221)) ([ea09db9](https://redirect.github.com/googleapis/mcp-toolbox/commit/ea09db90ce3ed78225dc246cedefd30064a88fad)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* add support for skills ([#102](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/102)) ([f16120b](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/f16120b76720f5d88ea0a6b1fab7e4a874d86978))
* release upgraded docsite ([mcp-toolbox#​2831](https://redirect.github.com/googleapis/mcp-toolbox/issues/2831)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* remove deprecations and update tools-file flag ([mcp-toolbox#​2806](https://redirect.github.com/googleapis/mcp-toolbox/issues/2806)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* Remove deprecations and update tools-file flag ([mcp-toolbox#​2806](https://redirect.github.com/googleapis/mcp-toolbox/issues/2806)) ([ab64c95](https://redirect.github.com/googleapis/mcp-toolbox/commit/ab64c9514a467d92a4547eda5a4ecdd08f86b0c9)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* remove packaging workflow ([#103](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/103)) ([0d47ec6](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/0d47ec6e0ee29bbb9dbf2795190264d30790a948))
* update repo name ([mcp-toolbox#​2968](https://redirect.github.com/googleapis/mcp-toolbox/issues/2968)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))


### Bug Fixes

* **bigquery:** Add impersonateServiceAccount to prebuilt config ([mcp-toolbox#​2770](https://redirect.github.com/googleapis/mcp-toolbox/issues/2770)) ([9c3a748](https://redirect.github.com/googleapis/mcp-toolbox/commit/9c3a748de43eb588586f22590ff74bd433b24d68)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **ci:** Remove search index generation from preview deployment workflow ([mcp-toolbox#​2859](https://redirect.github.com/googleapis/mcp-toolbox/issues/2859)) ([f8891b8](https://redirect.github.com/googleapis/mcp-toolbox/commit/f8891b82fcaaef240e1031cd9f784749d91d4210)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **docs:** Skip empty folders in pagination & reduce PR comment noise ([mcp-toolbox#​2853](https://redirect.github.com/googleapis/mcp-toolbox/issues/2853)) ([9ebd93a](https://redirect.github.com/googleapis/mcp-toolbox/commit/9ebd93a8ecb9bae673aa77a859803629fc7a4e1d)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **http:** Sanitize non-2xx error output ([mcp-toolbox#​2654](https://redirect.github.com/googleapis/mcp-toolbox/issues/2654)) ([5bef954](https://redirect.github.com/googleapis/mcp-toolbox/commit/5bef954507c8e23b6c9b0eb2551265e4be32b452)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **knowledge-catalog:** Rename dataplex to knowledge-catalog across docs ([mcp-toolbox#​3039](https://redirect.github.com/googleapis/mcp-toolbox/pull/3039)) ([45c05e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/24ce6ce3bc6468d2b4b11a86b90ea223daa7e6cf)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **looker:** Convert configuration yaml to flat format ([mcp-toolbox#​3022](https://redirect.github.com/googleapis/mcp-toolbox/issues/3022)) ([45c05e3](https://redirect.github.com/googleapis/mcp-toolbox/commit/45c05e37eac867c5a444d950bc51fdf1b1b687ea)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **quickstart:** Robust tool lookup and modernize dependencies in Python samples ([mcp-toolbox#​2863](https://redirect.github.com/googleapis/mcp-toolbox/issues/2863)) ([4c0845d](https://redirect.github.com/googleapis/mcp-toolbox/commit/4c0845dc9081d79046dea5f28a032d531faff40f)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Fix integer parameter parsing through agent skills ([mcp-toolbox#​2847](https://redirect.github.com/googleapis/mcp-toolbox/issues/2847)) ([4564efe](https://redirect.github.com/googleapis/mcp-toolbox/commit/4564efe75436b4081d9f3d1f7c912bc64c13f850)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Fix skill generation template ([mcp-toolbox#​2914](https://redirect.github.com/googleapis/mcp-toolbox/issues/2914)) ([a01a15e](https://redirect.github.com/googleapis/mcp-toolbox/commit/a01a15ed1aa9a83eda8362578fed2e3a3c8dde99)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **skills:** Prevent empty strings overriding optional env vars in node scripts ([mcp-toolbox#​2963](https://redirect.github.com/googleapis/mcp-toolbox/issues/2963)) ([c52adeb](https://redirect.github.com/googleapis/mcp-toolbox/commit/c52adeba76fc13d0e6e415f6393def0648e478d6)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **tests/bigquery:** Implement uuid-based isolation and reliable resource cleanup ([mcp-toolbox#​2547](https://redirect.github.com/googleapis/mcp-toolbox/issues/2547)) ([479d842](https://redirect.github.com/googleapis/mcp-toolbox/commit/479d8424046406d50af02b0602e6bac58aea534f)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* **tests/Bigtable:** Implement uuid-based isolation and reliable resource cleanup ([mcp-toolbox#​2880](https://redirect.github.com/googleapis/mcp-toolbox/issues/2880)) ([a769f15](https://redirect.github.com/googleapis/mcp-toolbox/commit/a769f15c3ab8d631198546909a6dd1f09446e6b0)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* Update error for ConvertConfig function ([mcp-toolbox#​2993](https://redirect.github.com/googleapis/mcp-toolbox/issues/2993)) ([62bdabb](https://redirect.github.com/googleapis/mcp-toolbox/commit/62bdabb512d7875d2760c1cd8eb331221b58a09c)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))
* Update repo name ([mcp-toolbox#​2968](https://redirect.github.com/googleapis/mcp-toolbox/issues/2968)) ([3aae809](https://redirect.github.com/googleapis/mcp-toolbox/commit/3aae8097f1bda00e41667fb41c02094167c96ace)) ([bfbc709](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/bfbc709d67506d1947fd2b7e202945f06c7708f2))

## [0.4.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.3.1...0.4.0) (2026-04-10)


### ⚠ BREAKING CHANGES

* **renaming:** Renaming changes across all the files.  ([#93](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/93))

### Miscellaneous Chores

* **renaming:** Renaming changes across all the files.  ([#93](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/93)) ([6e9215a](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/6e9215ae9d4dd6e3ccf37a041ba963304b0b0a42))

## [0.3.1](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.3.0...0.3.1) (2026-03-20)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.30.0 ([#89](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/89)) ([0341db1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/0341db179417f95ad00b243edbb6f27de4717fc6))

## [0.3.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.2.2...0.3.0) (2026-03-16)


### ⚠ BREAKING CHANGES

* telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566))
* **source/knowledge-catalog:** restructure prebuilt toolsets ([mcp-toolbox#​2640](https://redirect.github.com/googleapis/mcp-toolbox/issues/2640))

### Features

* **skill:** Attach user agent metadata for generated skill ([mcp-toolbox#​2697](https://redirect.github.com/googleapis/mcp-toolbox/issues/2697)) ([9598a6a](https://redirect.github.com/googleapis/mcp-toolbox/commit/9598a6a32597b9c9abdb0f20c06d86a01b0d011f)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **skill:** Update skill generation logic ([mcp-toolbox#​2646](https://redirect.github.com/googleapis/mcp-toolbox/issues/2646)) ([c233eee](https://redirect.github.com/googleapis/mcp-toolbox/commit/c233eee98cd9621526cb286245f3874f5bd6e7da)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **skills:** Add additional-notes flag to generate skills command ([mcp-toolbox#​2696](https://redirect.github.com/googleapis/mcp-toolbox/issues/2696)) ([73bf962](https://redirect.github.com/googleapis/mcp-toolbox/commit/73bf962459b76872f748248bb5e289be232a30b6)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **source/knowledge-catalog:** restructure prebuilt toolsets ([mcp-toolbox#​2640](https://redirect.github.com/googleapis/mcp-toolbox/issues/2640)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **source/knowledge-catalog:** Restructure prebuilt toolsets ([mcp-toolbox#​2640](https://redirect.github.com/googleapis/mcp-toolbox/issues/2640)) ([acb9a80](https://redirect.github.com/googleapis/mcp-toolbox/commit/acb9a80cf2438e04c76cf10267b1c9ca9227da0b)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Add user agent to embeddings generation ([mcp-toolbox#​2572](https://redirect.github.com/googleapis/mcp-toolbox/issues/2572)) ([287251a](https://redirect.github.com/googleapis/mcp-toolbox/commit/287251a0cfed4d24617e5d0d957026a94f65d820)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Telemetry metrics updates as per semantic convention ([mcp-toolbox#​2566](https://redirect.github.com/googleapis/mcp-toolbox/issues/2566)) ([131d764](https://redirect.github.com/googleapis/mcp-toolbox/commit/131d764f895c14908e29914b3c0c273d91a2654f)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))


### Bug Fixes

* **mcp:** Guard nil SSE session lookup and return 400 for missing session ([mcp-toolbox#​2681](https://redirect.github.com/googleapis/mcp-toolbox/issues/2681)) ([f66189f](https://redirect.github.com/googleapis/mcp-toolbox/commit/f66189fe43cb711da3a041fa31edbacd7bbc7153)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **oracle:** Update oracle-execute-sql tool interface to match source signature ([mcp-toolbox#​2627](https://redirect.github.com/googleapis/mcp-toolbox/issues/2627)) ([81699a3](https://redirect.github.com/googleapis/mcp-toolbox/commit/81699a375b7e5af37945f4124aa4c5f2a1a9f7a6)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **server/mcp:** Scope defer span.End inside loop iteration ([mcp-toolbox#​2558](https://redirect.github.com/googleapis/mcp-toolbox/issues/2558)) ([c88a62d](https://redirect.github.com/googleapis/mcp-toolbox/commit/c88a62dcf4c16118ae706cc43d18cad827e7496d)), closes [mcp-toolbox#​2549](https://redirect.github.com/googleapis/mcp-toolbox/issues/2549) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **skill:** Fix env variable propagation ([mcp-toolbox#​2645](https://redirect.github.com/googleapis/mcp-toolbox/issues/2645)) ([5271368](https://redirect.github.com/googleapis/mcp-toolbox/commit/52713687208994c423da64333cb0a04fb483f794)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **telemetry:** Histogram buckets from OTel standard to MCP standards ([mcp-toolbox#​2729](https://redirect.github.com/googleapis/mcp-toolbox/issues/2729)) ([87cd4a0](https://redirect.github.com/googleapis/mcp-toolbox/commit/87cd4a0bf48605225ef25ca554cc787def976d11)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* **ui:** Remove module from script ([mcp-toolbox#​2703](https://redirect.github.com/googleapis/mcp-toolbox/issues/2703)) ([6943ab6](https://redirect.github.com/googleapis/mcp-toolbox/commit/6943ab6839d21da7b6a4241700c7891c6f4a9b2c)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Improve list locks integration test for postgres ([mcp-toolbox#​2279](https://redirect.github.com/googleapis/mcp-toolbox/issues/2279)) ([d9ebe5d](https://redirect.github.com/googleapis/mcp-toolbox/commit/d9ebe5d4bf1b7ca04cae47386b36c38ca5b77b8a)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Return AllParams for GetParameter() for tools with templateParameter([mcp-toolbox#​2734](https://redirect.github.com/googleapis/mcp-toolbox/issues/2734)) ([bfd7ba6](https://redirect.github.com/googleapis/mcp-toolbox/commit/bfd7ba601a52294fa71623d88af71bd0288bf887)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))
* Update toolset attributes naming ([mcp-toolbox#​2554](https://redirect.github.com/googleapis/mcp-toolbox/issues/2554)) ([3d6ae4e](https://redirect.github.com/googleapis/mcp-toolbox/commit/3d6ae4eeaf5acfbde83374a244573edd8fc9012b)) ([7e9fdd1](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7e9fdd1141c48c2397edbdb6985c42ef3f300b96))

## [0.2.2](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.2.1...0.2.2) (2026-03-03)


### Features

* **dataproc:** Add dataproc source and list/get clusters/jobs tools ([mcp-toolbox#​2407](https://redirect.github.com/googleapis/mcp-toolbox/issues/2407)) ([cc05e57](https://redirect.github.com/googleapis/mcp-toolbox/commit/cc05e5745d1c25a6088702b827cd098250164b7e)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **ui:** Make tool list panel resizable ([mcp-toolbox#​2253](https://redirect.github.com/googleapis/mcp-toolbox/issues/2253)) ([276cf60](https://redirect.github.com/googleapis/mcp-toolbox/commit/276cf604a2bb41861639ed6881557e38dd97a614)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Add polling system to dynamic reloading ([mcp-toolbox#​2466](https://redirect.github.com/googleapis/mcp-toolbox/issues/2466)) ([fcaac9b](https://redirect.github.com/googleapis/mcp-toolbox/commit/fcaac9bb957226ee3db1baea24330f337ba88ab7)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Added basic template for sdks doc migrate ([mcp-toolbox#​1961](https://redirect.github.com/googleapis/mcp-toolbox/issues/1961)) ([87f2eaf](https://redirect.github.com/googleapis/mcp-toolbox/commit/87f2eaf79cdecca7b939151e1543eccf2f812a69)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))


### Bug Fixes

* **ci:** Add path for forked PR unit test runs ([mcp-toolbox#​2540](https://redirect.github.com/googleapis/mcp-toolbox/issues/2540)) ([04dd2a7](https://redirect.github.com/googleapis/mcp-toolbox/commit/04dd2a77603c7babf01da724dfb77808e3f25fe5)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **docs/adk:** Resolve dependency duplication ([mcp-toolbox#​2418](https://redirect.github.com/googleapis/mcp-toolbox/issues/2418)) ([4d44abb](https://redirect.github.com/googleapis/mcp-toolbox/commit/4d44abb4638926ca50b0fa4dcf10a03e7fab657f)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **docs/langchain:** Fix core at 0.3.0 and align compatible dependencies ([mcp-toolbox#​2426](https://redirect.github.com/googleapis/mcp-toolbox/issues/2426)) ([36edfd3](https://redirect.github.com/googleapis/mcp-toolbox/commit/36edfd3d506e839c092d04cbca1799b5ebc38160)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **oracle:** Enable DML operations and resolve incorrect array type error ([mcp-toolbox#​2323](https://redirect.github.com/googleapis/mcp-toolbox/issues/2323)) ([72146a4](https://redirect.github.com/googleapis/mcp-toolbox/commit/72146a4b1605bcdd3e1038106bfb1f899e677e39)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **server/mcp:** Guard nil dereference in sseManager.get ([mcp-toolbox#​2557](https://redirect.github.com/googleapis/mcp-toolbox/issues/2557)) ([e534196](https://redirect.github.com/googleapis/mcp-toolbox/commit/e534196303c2b8d9b6e599ac25add337e6fc9b8f)), closes [mcp-toolbox#​2548](https://redirect.github.com/googleapis/mcp-toolbox/issues/2548) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **tests:** Resolve LlamaIndex dependency conflict in JS quickstart ([mcp-toolbox#​2597](https://redirect.github.com/googleapis/mcp-toolbox/issues/2597)) ([ac11f5a](https://redirect.github.com/googleapis/mcp-toolbox/commit/ac11f5af9c7bcf228d667e1b8e08b5dc49ad91a0)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **tests/postgres:** Implement uuid-based isolation and reliable resource cleanup ([mcp-toolbox#​2377](https://redirect.github.com/googleapis/mcp-toolbox/issues/2377)) ([8a96fb1](https://redirect.github.com/googleapis/mcp-toolbox/commit/8a96fb1a8874baa3688e566f3dea8a0912fcf2df)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* **tests/postgres:** Restore list\_schemas test and implement dynamic owner ([mcp-toolbox#​2521](https://redirect.github.com/googleapis/mcp-toolbox/issues/2521)) ([7041e79](https://redirect.github.com/googleapis/mcp-toolbox/commit/7041e797347f337d6f7f44ca051ae31acd58babe)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Deflake alloydb omni ([mcp-toolbox#​2431](https://redirect.github.com/googleapis/mcp-toolbox/issues/2431)) ([62b8309](https://redirect.github.com/googleapis/mcp-toolbox/commit/62b830987d65c3573214d04e50742476097ee9e9)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))
* Enforce required validation for explicit null parameter values ([mcp-toolbox#​2519](https://redirect.github.com/googleapis/mcp-toolbox/issues/2519)) ([d5e9512](https://redirect.github.com/googleapis/mcp-toolbox/commit/d5e9512a237e658f9b9127fdd8c174ec023c3310)) ([50346c5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/50346c5bf9e5e43fb4a0156032f518c7e4cf278c))

## [0.2.1](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.2.0...0.2.1) (2026-02-19)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.27.0 ([#74](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/74)) ([7297207](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7297207178cf6367225a1c041b3ae1e28eafeb54))

## [0.2.0](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.4...0.2.0) (2026-01-26)


### ⚠ BREAKING CHANGES

* Validate tool naming ([mcp-toolbox#​2305](https://redirect.github.com/googleapis/mcp-toolbox/issues/2305)) ([5054212](https://redirect.github.com/googleapis/mcp-toolbox/commit/5054212fa43017207fe83275d27b9fbab96e8ab5))

### Features

* **embeddingModel:** Add embedding model to MCP handler ([mcp-toolbox#​2310](https://redirect.github.com/googleapis/mcp-toolbox/issues/2310)) ([e4f60e5](https://redirect.github.com/googleapis/mcp-toolbox/commit/e4f60e56335b755ef55b9553d3f40b31858ec8d9)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* **prebuilt/cloud-sql:** Add create backup tool for Cloud SQL ([mcp-toolbox#​2141](https://redirect.github.com/googleapis/mcp-toolbox/issues/2141)) ([8e0fb03](https://redirect.github.com/googleapis/mcp-toolbox/commit/8e0fb0348315a80f63cb47b3c7204869482448f4)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* **prebuilt/cloud-sql:** Add restore backup tool for Cloud SQL ([mcp-toolbox#​2171](https://redirect.github.com/googleapis/mcp-toolbox/issues/2171)) ([00c3e6d](https://redirect.github.com/googleapis/mcp-toolbox/commit/00c3e6d8cba54e2ab6cb271c7e6b378895df53e1)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* **tools:** Add `valueFromParam` support to Tool config ([mcp-toolbox#​2333](https://redirect.github.com/googleapis/mcp-toolbox/issues/2333)) ([15101b1](https://redirect.github.com/googleapis/mcp-toolbox/commit/15101b1edbe2b85a4a5f9f819c23cf83138f4ee1)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* add Configuration settings ([#67](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/67)) ([1c05d52](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/1c05d52d1907373855b146c76d7793ba3056585e))
* Add new `user-agent-metadata` flag ([mcp-toolbox#​2302](https://redirect.github.com/googleapis/mcp-toolbox/issues/2302)) ([adc9589](https://redirect.github.com/googleapis/mcp-toolbox/commit/adc9589766904d9e3cbe0a6399222f8d4bb9d0cc)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Add remaining flag to Toolbox server in MCP registry ([mcp-toolbox#​2272](https://redirect.github.com/googleapis/mcp-toolbox/issues/2272)) ([5e0999e](https://redirect.github.com/googleapis/mcp-toolbox/commit/5e0999ebf5cdd9046e96857738254b2e0561b6d2)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Support combining multiple prebuilt configurations ([mcp-toolbox#​2295](https://redirect.github.com/googleapis/mcp-toolbox/issues/2295)) ([e535b37](https://redirect.github.com/googleapis/mcp-toolbox/commit/e535b372ea81864d644a67135a1b07e4e519b4b4)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Support MCP specs version 2025-11-25 ([mcp-toolbox#​2303](https://redirect.github.com/googleapis/mcp-toolbox/issues/2303)) ([4d23a3b](https://redirect.github.com/googleapis/mcp-toolbox/commit/4d23a3bbf2797b1f7fe328aeb5789e778121da23)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))
* Validate tool naming ([mcp-toolbox#​2305](https://redirect.github.com/googleapis/mcp-toolbox/issues/2305)) ([5054212](https://redirect.github.com/googleapis/mcp-toolbox/commit/5054212fa43017207fe83275d27b9fbab96e8ab5)) ([cbaee3d](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/cbaee3dfa77050e7bbacbc7ffdd40c9992de4bf4))

## [0.1.4](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.3...0.1.4) (2026-01-15)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.25.0 ([#64](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/64)) ([dbf5a4a](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/dbf5a4a71ff3a6ccd3e35a54f931896620966c92))

## [0.1.3](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.2...0.1.3) (2025-12-29)


### Features

* **deps:** update dependency googleapis/mcp-toolbox to v0.24.0 ([#62](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/62)) ([fccf2a5](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/fccf2a5979bbc49b82a8b4c9074868f77df5b385))

## [0.1.2](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.1...0.1.2) (2025-12-11)


### Bug Fixes

* Update knowledge-catalog context for new syntax ([#60](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/60)) ([82281dd](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/82281dd94143814629cd47729220ea2f85af9096))

## [0.1.1](https://github.com/gemini-cli-extensions/knowledge-catalog/compare/0.1.0...0.1.1) (2025-09-30)


### Features

* additional instructions for the context file ([#26](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/26)) ([16e0d13](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/16e0d13f56ec98206f58f04b00220f191aaba07c))
* standardize mcp server names ([#24](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/24)) ([5cfdc0b](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/5cfdc0b9f7461ea3161db54b797650e79ced8504))

## 0.1.0 (2025-09-21)


### Features

* add knowledge-catalog Extension ([#9](https://github.com/gemini-cli-extensions/knowledge-catalog/issues/9)) ([7ed91b2](https://github.com/gemini-cli-extensions/knowledge-catalog/commit/7ed91b2fdc551739485e212b91080ce8285f87be))
