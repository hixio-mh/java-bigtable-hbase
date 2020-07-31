# Changelog

## [1.15.0](https://www.github.com/googleapis/java-bigtable-hbase/compare/v1.14.0...v1.15.0) (2020-07-31)


### Features

* adding client wrapper interfaces ([#2406](https://www.github.com/googleapis/java-bigtable-hbase/issues/2406)) ([1ad48d9](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ad48d9418e4d25180ca3dc66aaefcf80e00314b))
* extend RowCell to include labels field ([#2397](https://www.github.com/googleapis/java-bigtable-hbase/issues/2397)) ([80a85fe](https://www.github.com/googleapis/java-bigtable-hbase/commit/80a85fee02958d0fbe4fb32c6c809db7c0803358))
* tune default settings to align with java-bigtable ([#2439](https://www.github.com/googleapis/java-bigtable-hbase/issues/2439)) ([4aedcd9](https://www.github.com/googleapis/java-bigtable-hbase/commit/4aedcd9a572ef5ad246628654e06d31348dfd383))


### Bug Fixes

* deadlock scenario from BulkReadVeneerApi and fixed flaky tests ([#2484](https://www.github.com/googleapis/java-bigtable-hbase/issues/2484)) ([e4cd4ef](https://www.github.com/googleapis/java-bigtable-hbase/commit/e4cd4ef7b38777d1692a15d5f2182889271f6645))
* **build:** update return codes for build scripts ([#2583](https://www.github.com/googleapis/java-bigtable-hbase/issues/2583)) ([96e8d8e](https://www.github.com/googleapis/java-bigtable-hbase/commit/96e8d8ec38fcb9f8b3b678bcbba91de402f32c36))
* **logs:** type aligned to in log statement ([#2536](https://www.github.com/googleapis/java-bigtable-hbase/issues/2536)) ([76c41ca](https://www.github.com/googleapis/java-bigtable-hbase/commit/76c41ca37986cc703a27af971012949c425fb329))
* ReadRows not counting the rpc as the first attempt ([#2568](https://www.github.com/googleapis/java-bigtable-hbase/issues/2568)) ([c748f23](https://www.github.com/googleapis/java-bigtable-hbase/commit/c748f23b60f83d6468fcb52ac5477b74a3bab964))
* remove duplicated cell when interleave filter is applied ([#2491](https://www.github.com/googleapis/java-bigtable-hbase/issues/2491)) ([2915bfd](https://www.github.com/googleapis/java-bigtable-hbase/commit/2915bfd5527bd6beabab264a79fa764f2e6a7629))
* to fix deleteRowRangeByPrefix for integer values above 127 ([#2511](https://www.github.com/googleapis/java-bigtable-hbase/issues/2511)) ([1ae8c03](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ae8c03f1636b18c3fb6310db61a30f6ab7e9646)), closes [#2509](https://www.github.com/googleapis/java-bigtable-hbase/issues/2509)
* updated assertions and scan for firstKeyOnlyFilter test ([#2483](https://www.github.com/googleapis/java-bigtable-hbase/issues/2483)) ([a2cbe7a](https://www.github.com/googleapis/java-bigtable-hbase/commit/a2cbe7a97c2f65bd1f2a21eaba0c8868b315d55d)), closes [#1996](https://www.github.com/googleapis/java-bigtable-hbase/issues/1996)


### Dependencies

* add maven-enforcer-plugin ([#2401](https://www.github.com/googleapis/java-bigtable-hbase/issues/2401)) ([1ef4b9c](https://www.github.com/googleapis/java-bigtable-hbase/commit/1ef4b9cb23a11d630114f382080baac66fa2f26d))
* align bigtable-hbase-1.x-mapreduce to use the same hadoop version as other 1.x modules ([#2455](https://www.github.com/googleapis/java-bigtable-hbase/issues/2455)) ([60a5f82](https://www.github.com/googleapis/java-bigtable-hbase/commit/60a5f82e3e3c9affdcaf5ae2a8b79c433b5a1a1b))
* fix undeclared used dependencies ([#2419](https://www.github.com/googleapis/java-bigtable-hbase/issues/2419)) ([d9b109f](https://www.github.com/googleapis/java-bigtable-hbase/commit/d9b109f01b53924476b0d2b8cdbe5b36ef83bdad))
* update bigtable veneer version to 1.12.2 ([#2526](https://www.github.com/googleapis/java-bigtable-hbase/issues/2526)) ([c422b07](https://www.github.com/googleapis/java-bigtable-hbase/commit/c422b07f06cb55831e2287fd6dced7ce46ea25da))
* update bigtable.version to v1.13.0 ([#2540](https://www.github.com/googleapis/java-bigtable-hbase/issues/2540)) ([2167870](https://www.github.com/googleapis/java-bigtable-hbase/commit/21678704f17cc5487bb280e6be56e5cd26a3a9bc))
* update dependency com.fasterxml.jackson.core:jackson-databind to v2.11.0 ([#2505](https://www.github.com/googleapis/java-bigtable-hbase/issues/2505)) ([dd8856f](https://www.github.com/googleapis/java-bigtable-hbase/commit/dd8856f81b64249b8a9da28f0aa9350fa9887b4a))
* update dependency com.fasterxml.jackson.core:jackson-databind to v2.11.1 ([#2557](https://www.github.com/googleapis/java-bigtable-hbase/issues/2557)) ([65373ce](https://www.github.com/googleapis/java-bigtable-hbase/commit/65373ced9dd22050ce464c285d1f5d5d70f1b76d))
* update dependency com.google.auto.value:auto-value to v1.7.2 ([#2513](https://www.github.com/googleapis/java-bigtable-hbase/issues/2513)) ([409b309](https://www.github.com/googleapis/java-bigtable-hbase/commit/409b3094846e98cbc3286057ac98cba2f3332339))
* update dependency com.google.auto.value:auto-value to v1.7.3 ([#2549](https://www.github.com/googleapis/java-bigtable-hbase/issues/2549)) ([1161524](https://www.github.com/googleapis/java-bigtable-hbase/commit/1161524ecc3335d0e824bc7045159319f9885a83))
* update dependency com.google.auto.value:auto-value to v1.7.4 ([#2571](https://www.github.com/googleapis/java-bigtable-hbase/issues/2571)) ([4dd36a7](https://www.github.com/googleapis/java-bigtable-hbase/commit/4dd36a732ce229508f2d49dcb09ed36fe0f6ede6))
* **fix:** add log4j12 to mincluster h2 tests ([#2450](https://www.github.com/googleapis/java-bigtable-hbase/issues/2450)) ([bf5ef7c](https://www.github.com/googleapis/java-bigtable-hbase/commit/bf5ef7c80dd504baa56887fbdfe975677c05ab34))
* update dependency com.google.auto.value:auto-value-annotations to v1.7.2 ([#2532](https://www.github.com/googleapis/java-bigtable-hbase/issues/2532)) ([818f435](https://www.github.com/googleapis/java-bigtable-hbase/commit/818f4354846b848307b74c4d927d73833da254e6))
* update dependency com.google.auto.value:auto-value-annotations to v1.7.3 ([#2550](https://www.github.com/googleapis/java-bigtable-hbase/issues/2550)) ([218bcbe](https://www.github.com/googleapis/java-bigtable-hbase/commit/218bcbebecfc99ccc3a2b26d817c904e967daa3c))
* update dependency com.google.auto.value:auto-value-annotations to v1.7.4 ([#2572](https://www.github.com/googleapis/java-bigtable-hbase/issues/2572)) ([bf79eaf](https://www.github.com/googleapis/java-bigtable-hbase/commit/bf79eaf6e229f42b4b74cf46500e06ebf932239b))
* update dependency com.google.http-client:google-http-client-jackson2 to v1.35.0 ([#2507](https://www.github.com/googleapis/java-bigtable-hbase/issues/2507)) ([73f5c5e](https://www.github.com/googleapis/java-bigtable-hbase/commit/73f5c5e6ee599db681e3c27bc96fe0664db7d45e))
* update dependency org.mockito:mockito-core to v3.3.3 ([#2414](https://www.github.com/googleapis/java-bigtable-hbase/issues/2414)) ([e82bc10](https://www.github.com/googleapis/java-bigtable-hbase/commit/e82bc102f25085f3c223073d5e142f3376b0ec55))
* update dependency org.mockito:mockito-core to v3.4.0 ([#2578](https://www.github.com/googleapis/java-bigtable-hbase/issues/2578)) ([d6a351e](https://www.github.com/googleapis/java-bigtable-hbase/commit/d6a351ecac04b58fd7b3706ff074d4af65212121))


### Documentation

* automatically update version numbers with release ([#2476](https://www.github.com/googleapis/java-bigtable-hbase/issues/2476)) ([2ad78e9](https://www.github.com/googleapis/java-bigtable-hbase/commit/2ad78e919fada035e1c6d92f056c8dbf64771f4a))
* update CONTRIBUTING.md to include code formatting ([#534](https://www.github.com/googleapis/java-bigtable-hbase/issues/534)) ([#2542](https://www.github.com/googleapis/java-bigtable-hbase/issues/2542)) ([1c92056](https://www.github.com/googleapis/java-bigtable-hbase/commit/1c920563edd114589ff6896f396a0a2d021fd698))
* Update CONTRIBUTING.md with integration test instructions ([#2560](https://www.github.com/googleapis/java-bigtable-hbase/issues/2560)) ([9b1a6e5](https://www.github.com/googleapis/java-bigtable-hbase/commit/9b1a6e5738dd0362be8a12a2cf18f623015f5243))
