# Changelog

## [1.0.0](https://github.com/itsharex/memU/compare/v0.7.0...v1.0.0) (2025-12-05)


### ⚠ BREAKING CHANGES

* **memu-js:** use fetch instead of axios

### Features

* add non-RAG retrieve solution ([#84](https://github.com/itsharex/memU/issues/84)) ([fb96e54](https://github.com/itsharex/memU/commit/fb96e5405f1c0e3477929b7d9874e624dd0453cb))
* add usecase examples ([#94](https://github.com/itsharex/memU/issues/94)) ([47b5b39](https://github.com/itsharex/memU/commit/47b5b390e065ccac1cd2173fa2d6c41549e01063))
* add user model and user context store ([#113](https://github.com/itsharex/memU/issues/113)) ([7c37fb1](https://github.com/itsharex/memU/commit/7c37fb166b0a85bf7c89d0b109cbaa882fa80064))
* add valcano model support ([#110](https://github.com/itsharex/memU/issues/110)) ([704c302](https://github.com/itsharex/memU/commit/704c3024946e8d4a1d1b13ffef33126bb68bd9c4))
* initialize the memorize and retrieve workflows with the new 3-layer architecture ([#81](https://github.com/itsharex/memU/issues/81)) ([4a2e86c](https://github.com/itsharex/memU/commit/4a2e86c0e8bc3e50c82c4fde33d07ad741c8a65e))
* retrieve args change conversation_history to queries ([#98](https://github.com/itsharex/memU/issues/98)) ([6370c6e](https://github.com/itsharex/memU/commit/6370c6e968c9d0922120bf2a41e8b4206bab87cb))
* support summary in sdk ([c553dd1](https://github.com/itsharex/memU/commit/c553dd1c070771f1d813b7a029f0efa0b321914f))


### Bug Fixes

* __version__ ([101eb85](https://github.com/itsharex/memU/commit/101eb85a9e5bdb33f797ed2b95a265b69f657b0e))
* action & recall_agent behavior ([458eb50](https://github.com/itsharex/memU/commit/458eb50b8ebfd209f8d498ecbd97f74a05dd4a62))
* api docs ([bd56372](https://github.com/itsharex/memU/commit/bd563724756df43786990851cdc3b0e8ecd93b15))
* base url ([6156523](https://github.com/itsharex/memU/commit/61565230ba5c6add52fc1afbd2111e7b7d4e828b))
* client bugs ([585a6ab](https://github.com/itsharex/memU/commit/585a6ab3f3bf62273144da27e283c4d8bb009a72))
* correct binary name after making a release ([#91](https://github.com/itsharex/memU/issues/91)) ([0fa721a](https://github.com/itsharex/memU/commit/0fa721aaae294c6f230221af11084a0a6c1f478d))
* delete memory api response ([da6ba8f](https://github.com/itsharex/memU/commit/da6ba8f2914e6c916e9659ae3e659de8cb73b5df))
* dependency & logger ([b36e0be](https://github.com/itsharex/memU/commit/b36e0be7bbc91ecacbecbe98db0c724414389b81))
* docker config ([57e2368](https://github.com/itsharex/memU/commit/57e2368635731f3b5d3e082a4fe7e6557ed47fd1))
* docker setting ([5de93e0](https://github.com/itsharex/memU/commit/5de93e0e79886f98aba7f80a5e899969d2f20f76))
* file management ([e026bd3](https://github.com/itsharex/memU/commit/e026bd330c7c0da7f786e2f4e19d03bdad0002ec))
* javascript api & reference ([15d5f03](https://github.com/itsharex/memU/commit/15d5f03cdb6d5fa37d8b5fb1328c04e2bef22885))
* js example ([2e60229](https://github.com/itsharex/memU/commit/2e60229d56549415266614f6280a7b8e1245b0bc))
* llm client bugs ([f895283](https://github.com/itsharex/memU/commit/f895283497cb9836c9ed1f592366ccfa02d72e56))
* llm model ([df7716d](https://github.com/itsharex/memU/commit/df7716d80e9381cb77358c7b9bbc96579043f463))
* memory server remove agent id ([619187d](https://github.com/itsharex/memU/commit/619187dfc8cd901695a10414f25329d453e129c0))
* memory type ([1b2acec](https://github.com/itsharex/memU/commit/1b2acece8267180f47ac90b5b52fb3b601999161))
* **memu-js:** add wantSummary to retrieveDefaultCategories options ([b1a27eb](https://github.com/itsharex/memU/commit/b1a27ebbefdb6465c2621d4102b75248e71db36b))
* **memu-js:** add wantSummary to retrieveDefaultCategories options ([22f0453](https://github.com/itsharex/memU/commit/22f045384845ef9dbbccee52166ba4fdf061d511))
* **memu-js:** use globalThis.process instead of process ([64d59f0](https://github.com/itsharex/memU/commit/64d59f0ca8738991e6d0af701dc7649e89735850))
* **memu-js:** use globalThis.process instead of process ([581805d](https://github.com/itsharex/memU/commit/581805d3aaea93579fee7968519c8d4eeb4466c3))
* model definition ([2656ba5](https://github.com/itsharex/memU/commit/2656ba59aad163bd9fe0144ac6e01a88ccc5c229))
* model name ([918dff6](https://github.com/itsharex/memU/commit/918dff6891a530cfc7b9866a57382f35868f24e5))
* node-js sdk ([3b2c625](https://github.com/itsharex/memU/commit/3b2c62569b8bdf75e68651ddf894012e402c92cf))
* path -&gt; str ([1d6f311](https://github.com/itsharex/memU/commit/1d6f3116041cd045758069b3534a58f5f6f57057))
* pydantic model mismatch ([5ac250e](https://github.com/itsharex/memU/commit/5ac250e6a189902ecfb13f43b6c89a2ede7c99a2))
* python sdk endpoint ([a05dfc8](https://github.com/itsharex/memU/commit/a05dfc823d931c364460e9fbd0f3cdbda8bf7f8a))
* qrcode ([c160284](https://github.com/itsharex/memU/commit/c1602846011f5659da8227bb116ad57a9f74ad14))
* resource caption miss problem ([#111](https://github.com/itsharex/memU/issues/111)) ([85586f5](https://github.com/itsharex/memU/commit/85586f52d6bd6355ae440ad06d8cc6779c689ce8))
* session_date ([27ba530](https://github.com/itsharex/memU/commit/27ba5308dbc13a22184564b713c98167b5a8823e))
* storage path & cleanup ([c4e968a](https://github.com/itsharex/memU/commit/c4e968a7e87af3a1208fdde2c1d7093d9f9d280f))
* version number ([efa3534](https://github.com/itsharex/memU/commit/efa35345754d41f453c11ae873837eaf2e3f9681))
* wechat img ([635bad8](https://github.com/itsharex/memU/commit/635bad851e1a513e0303d6ddab35d953b14fd8be))


### Documentation

* add German translation for README ([f6d6ab1](https://github.com/itsharex/memU/commit/f6d6ab1a51b76bd4312542422aebac89410b8da9))
* add German translation for README ([76c3fc4](https://github.com/itsharex/memU/commit/76c3fc4227a8e349fbcf1e5bfec29d68e984ff7a))
* fix example file path ([#105](https://github.com/itsharex/memU/issues/105)) ([21aad6a](https://github.com/itsharex/memU/commit/21aad6a7f070e7666ac6a41c91980a4fa9696918))
* fix readme test case ([#107](https://github.com/itsharex/memU/issues/107)) ([228306c](https://github.com/itsharex/memU/commit/228306c897402c633f57c7aa31e8c6cd4e995d5d))
* fix several words in README ([#89](https://github.com/itsharex/memU/issues/89)) ([1e3baf9](https://github.com/itsharex/memU/commit/1e3baf92d5a08ec51a7eda3249bbd4b40530f56c))
* highlight OpenAI key ([#106](https://github.com/itsharex/memU/issues/106)) ([5b6ce54](https://github.com/itsharex/memU/commit/5b6ce54def5aa7743a85bec629da65bfa9d8333b))
* highlight readme openai key ([#103](https://github.com/itsharex/memU/issues/103)) ([fc4154a](https://github.com/itsharex/memU/commit/fc4154a707220ced4359e7296218451c43cf0681))
* revise README for clarity and roadmap inclusion ([#86](https://github.com/itsharex/memU/issues/86)) ([2235b09](https://github.com/itsharex/memU/commit/2235b099acc7e92ac52b2613fa731f85259d58fd))
* update images and refine punctuation in README ([#88](https://github.com/itsharex/memU/issues/88)) ([cc375e8](https://github.com/itsharex/memU/commit/cc375e89a9b49bda0b7057eee696d74c4c1d9cee))


### Code Refactoring

* **memu-js:** use fetch instead of axios ([19e934e](https://github.com/itsharex/memU/commit/19e934e0bff3f6071c75277606d4b77835b1b040))

## [0.7.0](https://github.com/NevaMind-AI/memU/compare/v0.6.0...v0.7.0) (2025-12-05)


### Features

* add user model and user context store ([#113](https://github.com/NevaMind-AI/memU/issues/113)) ([7c37fb1](https://github.com/NevaMind-AI/memU/commit/7c37fb166b0a85bf7c89d0b109cbaa882fa80064))
* add valcano model support ([#110](https://github.com/NevaMind-AI/memU/issues/110)) ([704c302](https://github.com/NevaMind-AI/memU/commit/704c3024946e8d4a1d1b13ffef33126bb68bd9c4))


### Bug Fixes

* resource caption miss problem ([#111](https://github.com/NevaMind-AI/memU/issues/111)) ([85586f5](https://github.com/NevaMind-AI/memU/commit/85586f52d6bd6355ae440ad06d8cc6779c689ce8))


### Documentation

* fix example file path ([#105](https://github.com/NevaMind-AI/memU/issues/105)) ([21aad6a](https://github.com/NevaMind-AI/memU/commit/21aad6a7f070e7666ac6a41c91980a4fa9696918))
* fix readme test case ([#107](https://github.com/NevaMind-AI/memU/issues/107)) ([228306c](https://github.com/NevaMind-AI/memU/commit/228306c897402c633f57c7aa31e8c6cd4e995d5d))
* highlight OpenAI key ([#106](https://github.com/NevaMind-AI/memU/issues/106)) ([5b6ce54](https://github.com/NevaMind-AI/memU/commit/5b6ce54def5aa7743a85bec629da65bfa9d8333b))
* highlight readme openai key ([#103](https://github.com/NevaMind-AI/memU/issues/103)) ([fc4154a](https://github.com/NevaMind-AI/memU/commit/fc4154a707220ced4359e7296218451c43cf0681))

## [0.6.0](https://github.com/NevaMind-AI/memU/compare/v0.5.0...v0.6.0) (2025-11-20)


### Features

* retrieve args change conversation_history to queries ([#98](https://github.com/NevaMind-AI/memU/issues/98)) ([6370c6e](https://github.com/NevaMind-AI/memU/commit/6370c6e968c9d0922120bf2a41e8b4206bab87cb))

## [0.5.0](https://github.com/NevaMind-AI/memU/compare/v0.4.0...v0.5.0) (2025-11-18)


### Features

* add usecase examples ([#94](https://github.com/NevaMind-AI/memU/issues/94)) ([47b5b39](https://github.com/NevaMind-AI/memU/commit/47b5b390e065ccac1cd2173fa2d6c41549e01063))

## [0.4.0](https://github.com/NevaMind-AI/memU/compare/v0.3.0...v0.4.0) (2025-11-18)


### Features

* add non-RAG retrieve solution ([#84](https://github.com/NevaMind-AI/memU/issues/84)) ([fb96e54](https://github.com/NevaMind-AI/memU/commit/fb96e5405f1c0e3477929b7d9874e624dd0453cb))


### Bug Fixes

* correct binary name after making a release ([#91](https://github.com/NevaMind-AI/memU/issues/91)) ([0fa721a](https://github.com/NevaMind-AI/memU/commit/0fa721aaae294c6f230221af11084a0a6c1f478d))


### Documentation

* fix several words in README ([#89](https://github.com/NevaMind-AI/memU/issues/89)) ([1e3baf9](https://github.com/NevaMind-AI/memU/commit/1e3baf92d5a08ec51a7eda3249bbd4b40530f56c))
* revise README for clarity and roadmap inclusion ([#86](https://github.com/NevaMind-AI/memU/issues/86)) ([2235b09](https://github.com/NevaMind-AI/memU/commit/2235b099acc7e92ac52b2613fa731f85259d58fd))
* update images and refine punctuation in README ([#88](https://github.com/NevaMind-AI/memU/issues/88)) ([cc375e8](https://github.com/NevaMind-AI/memU/commit/cc375e89a9b49bda0b7057eee696d74c4c1d9cee))

## [0.3.0](https://github.com/NevaMind-AI/memU/compare/v0.2.2...v0.3.0) (2025-11-17)


### Features

* initialize the memorize and retrieve workflows with the new 3-layer architecture ([#81](https://github.com/NevaMind-AI/memU/issues/81)) ([4a2e86c](https://github.com/NevaMind-AI/memU/commit/4a2e86c0e8bc3e50c82c4fde33d07ad741c8a65e))


### Documentation

* add German translation for README ([f6d6ab1](https://github.com/NevaMind-AI/memU/commit/f6d6ab1a51b76bd4312542422aebac89410b8da9))
* add German translation for README ([76c3fc4](https://github.com/NevaMind-AI/memU/commit/76c3fc4227a8e349fbcf1e5bfec29d68e984ff7a))
