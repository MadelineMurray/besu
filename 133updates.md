# Change Log

## [Unreleased](https://github.com/hyperledger/besu/tree/HEAD)

[Full Changelog](https://github.com/hyperledger/besu/compare/1.3.2...HEAD)

**Merged pull requests:**

- Redesign of how JsonRpcMethods are created [\#159](https://github.com/hyperledger/besu/pull/159) ([CjHare](https://github.com/CjHare))
- disable circle publishing on releases for tomorrow's release [\#157](https://github.com/hyperledger/besu/pull/157) ([joshuafernandes](https://github.com/joshuafernandes))
- Moving JsonRpcMethods classes into the same package, prior to refactor [\#154](https://github.com/hyperledger/besu/pull/154) ([CjHare](https://github.com/CjHare))
- \[MINOR\] edits to test names [\#153](https://github.com/hyperledger/besu/pull/153) ([macfarla](https://github.com/macfarla))
- Add --identity flag for client identification in node browsers [\#150](https://github.com/hyperledger/besu/pull/150) ([shemnon](https://github.com/shemnon))
- \[PAN-3262\] Reflect default logging in CLI help [\#148](https://github.com/hyperledger/besu/pull/148) ([shemnon](https://github.com/shemnon))
- \[PAN-3143\] Handle zero port better in NAT [\#147](https://github.com/hyperledger/besu/pull/147) ([shemnon](https://github.com/shemnon))
- Rework how filter and log query parameters are created/used [\#146](https://github.com/hyperledger/besu/pull/146) ([RatanRSur](https://github.com/RatanRSur))
- Istanbul Mainnet Block [\#145](https://github.com/hyperledger/besu/pull/145) ([shemnon](https://github.com/shemnon))
- Using gradle root project build dir in check-license [\#144](https://github.com/hyperledger/besu/pull/144) ([usmansaleem](https://github.com/usmansaleem))
- adding in circle config [\#143](https://github.com/hyperledger/besu/pull/143) ([joshuafernandes](https://github.com/joshuafernandes))
- \[Refactor\] Don't generate shutdown tasks in controller [\#141](https://github.com/hyperledger/besu/pull/141) ([mbaxter](https://github.com/mbaxter))
- Ibft queries [\#138](https://github.com/hyperledger/besu/pull/138) ([rain-on](https://github.com/rain-on))
- Update ROADMAP.md [\#136](https://github.com/hyperledger/besu/pull/136) ([timbeiko](https://github.com/timbeiko))
- \[PAN-2798\] Enable pruning by default for fast sync [\#135](https://github.com/hyperledger/besu/pull/135) ([RatanRSur](https://github.com/RatanRSur))
- Ensure spotless runs in CI [\#132](https://github.com/hyperledger/besu/pull/132) ([ajsutton](https://github.com/ajsutton))
- \[Minor\] Add more logging around peer disconnects [\#131](https://github.com/hyperledger/besu/pull/131) ([mbaxter](https://github.com/mbaxter))
- Repair EthGetLogs returning incorrect results [\#128](https://github.com/hyperledger/besu/pull/128) ([rain-on](https://github.com/rain-on))
- \[PAN-3249\] Use Bloombits for Logs queries [\#127](https://github.com/hyperledger/besu/pull/127) ([shemnon](https://github.com/shemnon))
- \[PAN-2830\] improve message when extraData missing [\#121](https://github.com/hyperledger/besu/pull/121) ([kziemianek](https://github.com/kziemianek))
- rename eea\_getTransactionCount to priv\_getEeaTransactionCount [\#110](https://github.com/hyperledger/besu/pull/110) ([pinges](https://github.com/pinges))
- Fix miner startup logic [\#104](https://github.com/hyperledger/besu/pull/104) ([mbaxter](https://github.com/mbaxter))
- Support log reordring from reorgs in `LogSubscriptionService` [\#86](https://github.com/hyperledger/besu/pull/86) ([RatanRSur](https://github.com/RatanRSur))

## [1.3.2](https://github.com/hyperledger/besu/tree/1.3.2) (2019-10-22)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.3.1...1.3.2)

**Implemented enhancements:**

- Expose getPayload in Transaction plugin-api interface. [\#113](https://github.com/hyperledger/besu/pull/113) ([abdelhamidbakhta](https://github.com/abdelhamidbakhta))
- Add hash field in Transaction plugin interface. [\#111](https://github.com/hyperledger/besu/pull/111) ([abdelhamidbakhta](https://github.com/abdelhamidbakhta))

**Merged pull requests:**

- Prepare for version 1.3.3-SNAPSHOT [\#126](https://github.com/hyperledger/besu/pull/126) ([EdJoJob](https://github.com/EdJoJob))
- Added 1.3.2 changes to changelog [\#125](https://github.com/hyperledger/besu/pull/125) ([MadelineMurray](https://github.com/MadelineMurray))
- \[PIE-2052\] Besu CLI -V to print plugin versions [\#123](https://github.com/hyperledger/besu/pull/123) ([usmansaleem](https://github.com/usmansaleem))
- Removing duplicate gradle dependency [\#122](https://github.com/hyperledger/besu/pull/122) ([CjHare](https://github.com/CjHare))
- Update Governance and Code of Conduct verbiage. [\#120](https://github.com/hyperledger/besu/pull/120) ([shemnon](https://github.com/shemnon))
- \[PAN-3240\] fix private transaction root mismatch [\#118](https://github.com/hyperledger/besu/pull/118) ([iikirilov](https://github.com/iikirilov))
- \[PAN-3242\] Programatically enforce plugin CLI variable names [\#117](https://github.com/hyperledger/besu/pull/117) ([shemnon](https://github.com/shemnon))
- Additional unit test for selecting replaced pending transactions [\#116](https://github.com/hyperledger/besu/pull/116) ([jframe](https://github.com/jframe))
- \[PAN-3239\] Only set sync targets that have an estimated height value [\#115](https://github.com/hyperledger/besu/pull/115) ([mbaxter](https://github.com/mbaxter))
- \[Pan 3238\] Fix rlpx startup [\#114](https://github.com/hyperledger/besu/pull/114) ([mbaxter](https://github.com/mbaxter))
- Dependency Version Upgrades [\#112](https://github.com/hyperledger/besu/pull/112) ([shemnon](https://github.com/shemnon))
- Prepare for 1.3.2-SNAPSHOT [\#109](https://github.com/hyperledger/besu/pull/109) ([EdJoJob](https://github.com/EdJoJob))
- \[PIE-2031\] Rework sync status events [\#106](https://github.com/hyperledger/besu/pull/106) ([mbaxter](https://github.com/mbaxter))

## [1.3.1](https://github.com/hyperledger/besu/tree/1.3.1) (2019-10-15)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.3.0...1.3.1)

**Implemented enhancements:**

- Add totalDiffculty to BlockPropagated events. [\#97](https://github.com/hyperledger/besu/pull/97) ([abdelhamidbakhta](https://github.com/abdelhamidbakhta))

**Merged pull requests:**

- Update formatting in DCO [\#108](https://github.com/hyperledger/besu/pull/108) ([mastersingh24](https://github.com/mastersingh24))
- Added 1.3.1 PRs [\#105](https://github.com/hyperledger/besu/pull/105) ([MadelineMurray](https://github.com/MadelineMurray))
- \[PAN-3230\] Merge BlockchainQueries classes [\#101](https://github.com/hyperledger/besu/pull/101) ([shemnon](https://github.com/shemnon))
- \[PIE-2026\] Separate in-sync from sync-status listeners [\#100](https://github.com/hyperledger/besu/pull/100) ([mbaxter](https://github.com/mbaxter))
- \[PIE-2023\] Fixed casing of dynamic MetricCategorys [\#99](https://github.com/hyperledger/besu/pull/99) ([mark-terry](https://github.com/mark-terry))
- Removing redundant code [\#98](https://github.com/hyperledger/besu/pull/98) ([CjHare](https://github.com/CjHare))
- \[PAN-3222\] Fix private transactions breaking evm [\#96](https://github.com/hyperledger/besu/pull/96) ([iikirilov](https://github.com/iikirilov))
- \[PIE-2003\] Make SyncState variables thread-safe [\#95](https://github.com/hyperledger/besu/pull/95) ([mbaxter](https://github.com/mbaxter))
- \[PAN-3223\] Add GraphQL query/logs support [\#94](https://github.com/hyperledger/besu/pull/94) ([shemnon](https://github.com/shemnon))
- \[PIE-1998\] Fix transaction tracking by sender [\#93](https://github.com/hyperledger/besu/pull/93) ([mbaxter](https://github.com/mbaxter))
- Make logic in PersistBlockTask more explicit to fix a LGTM warning [\#92](https://github.com/hyperledger/besu/pull/92) ([ajsutton](https://github.com/ajsutton))
- Removed Unused methods in the transaction simulator. [\#91](https://github.com/hyperledger/besu/pull/91) ([rojotek](https://github.com/rojotek))
- Fix ThreadBesuNodeRunner BesuConfiguration setup [\#90](https://github.com/hyperledger/besu/pull/90) ([mbaxter](https://github.com/mbaxter))
- \[Minor\] Rework balance checks to use stronger types [\#89](https://github.com/hyperledger/besu/pull/89) ([mbaxter](https://github.com/mbaxter))
- 1.3 Changelog updates [\#84](https://github.com/hyperledger/besu/pull/84) ([MadelineMurray](https://github.com/MadelineMurray))
- New Maintainer candidate: Ivaylo Kirilov [\#83](https://github.com/hyperledger/besu/pull/83) ([lucassaldanha](https://github.com/lucassaldanha))
- JsonRpc method disabled error condition rewrite and unit test [\#80](https://github.com/hyperledger/besu/pull/80) ([CjHare](https://github.com/CjHare))
- Round trip testing of state trie account values [\#31](https://github.com/hyperledger/besu/pull/31) ([drinkcoffee](https://github.com/drinkcoffee))

## [1.3.0](https://github.com/hyperledger/besu/tree/1.3.0) (2019-10-03)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.3.0-RC1...1.3.0)

**Merged pull requests:**

- 1.3 Release [\#88](https://github.com/hyperledger/besu/pull/88) ([EdJoJob](https://github.com/EdJoJob))
- specify that pruning options are minimums [\#87](https://github.com/hyperledger/besu/pull/87) ([RatanRSur](https://github.com/RatanRSur))
- Add privDistributeTransaction AT [\#81](https://github.com/hyperledger/besu/pull/81) ([iikirilov](https://github.com/iikirilov))
- \[PAN-3203\] add --required-block flag to deal with chainsplits [\#79](https://github.com/hyperledger/besu/pull/79) ([shemnon](https://github.com/shemnon))
- Add CII badge to README [\#78](https://github.com/hyperledger/besu/pull/78) ([EdJoJob](https://github.com/EdJoJob))
- We should be building SNAPSHOT releases now [\#77](https://github.com/hyperledger/besu/pull/77) ([EdJoJob](https://github.com/EdJoJob))
- Check for duplicate Maven coordinates [\#75](https://github.com/hyperledger/besu/pull/75) ([shemnon](https://github.com/shemnon))
- \[minor\] add openjdk to platform detector [\#74](https://github.com/hyperledger/besu/pull/74) ([shemnon](https://github.com/shemnon))
- Fixing rocksdb artifact name conflicts [\#73](https://github.com/hyperledger/besu/pull/73) ([lucassaldanha](https://github.com/lucassaldanha))
- Fixing rocksdb artifact name conflicts [\#72](https://github.com/hyperledger/besu/pull/72) ([lucassaldanha](https://github.com/lucassaldanha))
- Fixes race condition between `NodeAddedListener` and `FullBlockImportStep` [\#56](https://github.com/hyperledger/besu/pull/56) ([RatanRSur](https://github.com/RatanRSur))

## [1.3.0-RC1](https://github.com/hyperledger/besu/tree/1.3.0-RC1) (2019-09-30)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.2.4...1.3.0-RC1)

**Implemented enhancements:**

- Disallow comments in Genesis JSON file. [\#49](https://github.com/hyperledger/besu/pull/49) ([abdelhamidbakhta](https://github.com/abdelhamidbakhta))
- Store db metadata file in the root data directory. [\#46](https://github.com/hyperledger/besu/pull/46) ([abdelhamidbakhta](https://github.com/abdelhamidbakhta))
- Introduce virtual operation. [\#45](https://github.com/hyperledger/besu/pull/45) ([abdelhamidbakhta](https://github.com/abdelhamidbakhta))
- \[PAN-3023\] Add command line option for target gas limit [\#24](https://github.com/hyperledger/besu/pull/24) ([cfelde](https://github.com/cfelde))

**Fixed bugs:**

- Update download link [\#54](https://github.com/hyperledger/besu/pull/54) ([NicolasMassart](https://github.com/NicolasMassart))

**Merged pull requests:**

- Prepare for version 1.4.0-SNAPSHOT [\#70](https://github.com/hyperledger/besu/pull/70) ([EdJoJob](https://github.com/EdJoJob))
- Undo "Add CODEOWNERS to match MAINTAINERS" [\#69](https://github.com/hyperledger/besu/pull/69) ([shemnon](https://github.com/shemnon))
- add LGTM badges [\#68](https://github.com/hyperledger/besu/pull/68) ([NicolasMassart](https://github.com/NicolasMassart))
- 1.3 RC Changelog updates [\#67](https://github.com/hyperledger/besu/pull/67) ([MadelineMurray](https://github.com/MadelineMurray))
- removing azure artifacts and process [\#66](https://github.com/hyperledger/besu/pull/66) ([joshuafernandes](https://github.com/joshuafernandes))
- Adding whitespace to separate words in log message [\#65](https://github.com/hyperledger/besu/pull/65) ([CjHare](https://github.com/CjHare))
- Remove orphaned Javadoc [\#64](https://github.com/hyperledger/besu/pull/64) ([CjHare](https://github.com/CjHare))
- Add CODEOWNERS to match MAINTAINERS [\#62](https://github.com/hyperledger/besu/pull/62) ([ryjones](https://github.com/ryjones))
- Fix docker tags [\#60](https://github.com/hyperledger/besu/pull/60) ([joshuafernandes](https://github.com/joshuafernandes))
- \[PAN-3183\] Less verbose synching subscriptions [\#59](https://github.com/hyperledger/besu/pull/59) ([shemnon](https://github.com/shemnon))
- Add default SECURITY policy [\#58](https://github.com/hyperledger/besu/pull/58) ([ryjones](https://github.com/ryjones))
- Fixing Typo in validation error message [\#55](https://github.com/hyperledger/besu/pull/55) ([CjHare](https://github.com/CjHare))
- return enclave key instead of private transaction hash [\#53](https://github.com/hyperledger/besu/pull/53) ([iikirilov](https://github.com/iikirilov))
- Clean up BesuConfiguration construction [\#51](https://github.com/hyperledger/besu/pull/51) ([mbaxter](https://github.com/mbaxter))
- Fix some mark sweep pruner bugs where nodes that should be kept were being swept  \(Re-merge of \#38\) [\#50](https://github.com/hyperledger/besu/pull/50) ([RatanRSur](https://github.com/RatanRSur))
- PAN-3175: Private tx nonce errors return same msg as any tx [\#48](https://github.com/hyperledger/besu/pull/48) ([lucassaldanha](https://github.com/lucassaldanha))
- Fix default logging [\#47](https://github.com/hyperledger/besu/pull/47) ([shemnon](https://github.com/shemnon))
- Downgrade some RocksDBPlugin Logging Levels [\#44](https://github.com/hyperledger/besu/pull/44) ([shemnon](https://github.com/shemnon))
- Fix some mark sweep pruner bugs where nodes that should be kept were being swept [\#38](https://github.com/hyperledger/besu/pull/38) ([RatanRSur](https://github.com/RatanRSur))
- PIE-1858: Infrastructure for exposing PoA metrics for plugins. [\#37](https://github.com/hyperledger/besu/pull/37) ([mark-terry](https://github.com/mark-terry))
- \[PAN-3122\] Allow private contracts to access public state [\#9](https://github.com/hyperledger/besu/pull/9) ([josh-richardson](https://github.com/josh-richardson))
- refactor-privacy-storage [\#7](https://github.com/hyperledger/besu/pull/7) ([iikirilov](https://github.com/iikirilov))

## [1.2.4](https://github.com/hyperledger/besu/tree/1.2.4) (2019-09-24)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.2.2...1.2.4)

**Merged pull requests:**

- Only publish on Azure for SNAPSHOT releases [\#43](https://github.com/hyperledger/besu/pull/43) ([EdJoJob](https://github.com/EdJoJob))
- Update version to 1.2.5-SNAPSHOT [\#42](https://github.com/hyperledger/besu/pull/42) ([EdJoJob](https://github.com/EdJoJob))
- \[PIE-1950\] Disable json-rpc trace API's [\#40](https://github.com/hyperledger/besu/pull/40) ([mbaxter](https://github.com/mbaxter))
- Added 1.2.4 changes [\#39](https://github.com/hyperledger/besu/pull/39) ([MadelineMurray](https://github.com/MadelineMurray))
- \[PAN-3160\] Rinkeby Istanbul fork block [\#35](https://github.com/hyperledger/besu/pull/35) ([shemnon](https://github.com/shemnon))
- \[PAN-3113\] Refactors pantheon private key to signing private key [\#34](https://github.com/hyperledger/besu/pull/34) ([josh-richardson](https://github.com/josh-richardson))
- Support both BESU\_ and PANTHEON\_ env var prefixes [\#32](https://github.com/hyperledger/besu/pull/32) ([ajsutton](https://github.com/ajsutton))
- Adding a spdx license check gradle task [\#30](https://github.com/hyperledger/besu/pull/30) ([joshuafernandes](https://github.com/joshuafernandes))
- \[PIE-1785\] Require minimum number of pivot confirmations [\#29](https://github.com/hyperledger/besu/pull/29) ([mbaxter](https://github.com/mbaxter))
- Initial Maintainers [\#28](https://github.com/hyperledger/besu/pull/28) ([shemnon](https://github.com/shemnon))
- \[PAN-3158\] Add Istanbul block for Goerli [\#27](https://github.com/hyperledger/besu/pull/27) ([shemnon](https://github.com/shemnon))
- \[PAN-3158\] Add Istanbul block for Ropsten [\#26](https://github.com/hyperledger/besu/pull/26) ([shemnon](https://github.com/shemnon))
- \[PAN-3139\] Add privDistributeRawTransaction endpoint [\#23](https://github.com/hyperledger/besu/pull/23) ([josh-richardson](https://github.com/josh-richardson))
- Publish jars to Azure [\#22](https://github.com/hyperledger/besu/pull/22) ([ajsutton](https://github.com/ajsutton))
- \[PAN-2333\] Use only fully validated peers for fast sync pivot selection [\#21](https://github.com/hyperledger/besu/pull/21) ([mbaxter](https://github.com/mbaxter))
- Support Version Rollbacks for RocksDB \(\#6\) [\#19](https://github.com/hyperledger/besu/pull/19) ([RatanRSur](https://github.com/RatanRSur))
- update Cava library to Tuweni Library [\#18](https://github.com/hyperledger/besu/pull/18) ([NicolasMassart](https://github.com/NicolasMassart))
- StateTrieAccountValue:Version should be written as an int, not a long [\#17](https://github.com/hyperledger/besu/pull/17) ([drinkcoffee](https://github.com/drinkcoffee))
- \[PAN-3155\] Handle discovery peers with updated endpoints [\#12](https://github.com/hyperledger/besu/pull/12) ([mbaxter](https://github.com/mbaxter))
- \[minor\] Change retesteth port. [\#11](https://github.com/hyperledger/besu/pull/11) ([shemnon](https://github.com/shemnon))
- \[PAN-3111\] Renames eea\_getTransactionReceipt to priv\_getTransactionReceipt [\#10](https://github.com/hyperledger/besu/pull/10) ([josh-richardson](https://github.com/josh-richardson))
- \[PAN-3127\] remove-enclave-url-plugin [\#8](https://github.com/hyperledger/besu/pull/8) ([iikirilov](https://github.com/iikirilov))
- Support Version Rollbacks for RocksDB [\#6](https://github.com/hyperledger/besu/pull/6) ([RatanRSur](https://github.com/RatanRSur))
- Moving AT DSL into its own module [\#3](https://github.com/hyperledger/besu/pull/3) ([rain-on](https://github.com/rain-on))
- No snapshots to bintray + fixup docs link in readme [\#2](https://github.com/hyperledger/besu/pull/2) ([joshuafernandes](https://github.com/joshuafernandes))
- Update Jenkins Build for Pantheon → Besu considerations [\#1](https://github.com/hyperledger/besu/pull/1) ([EdJoJob](https://github.com/EdJoJob))

## [1.2.2](https://github.com/hyperledger/besu/tree/1.2.2) (2019-08-28)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.2.1...1.2.2)

## [1.2.1](https://github.com/hyperledger/besu/tree/1.2.1) (2019-08-14)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.2.0...1.2.1)

## [1.2.0](https://github.com/hyperledger/besu/tree/1.2.0) (2019-07-31)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.2.0-RC1...1.2.0)

## [1.2.0-RC1](https://github.com/hyperledger/besu/tree/1.2.0-RC1) (2019-07-17)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.1.4...1.2.0-RC1)

## [1.1.4](https://github.com/hyperledger/besu/tree/1.1.4) (2019-07-03)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.1.3...1.1.4)

## [1.1.3](https://github.com/hyperledger/besu/tree/1.1.3) (2019-06-20)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.1.2...1.1.3)

## [1.1.2](https://github.com/hyperledger/besu/tree/1.1.2) (2019-06-06)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.1.1...1.1.2)

## [1.1.1](https://github.com/hyperledger/besu/tree/1.1.1) (2019-05-22)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.1.0...1.1.1)

## [1.1.0](https://github.com/hyperledger/besu/tree/1.1.0) (2019-04-29)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.1.0-RC1...1.1.0)

## [1.1.0-RC1](https://github.com/hyperledger/besu/tree/1.1.0-RC1) (2019-04-17)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.0.3...1.1.0-RC1)

## [1.0.3](https://github.com/hyperledger/besu/tree/1.0.3) (2019-04-10)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.0.2...1.0.3)

## [1.0.2](https://github.com/hyperledger/besu/tree/1.0.2) (2019-03-27)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.0.1...1.0.2)

## [1.0.1](https://github.com/hyperledger/besu/tree/1.0.1) (2019-03-07)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.0.0...1.0.1)

## [1.0.0](https://github.com/hyperledger/besu/tree/1.0.0) (2019-02-27)
[Full Changelog](https://github.com/hyperledger/besu/compare/1.0.0-RC1...1.0.0)

## [1.0.0-RC1](https://github.com/hyperledger/besu/tree/1.0.0-RC1) (2019-02-21)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.9.1...1.0.0-RC1)

## [0.9.1](https://github.com/hyperledger/besu/tree/0.9.1) (2019-01-31)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.9.0...0.9.1)

## [0.9.0](https://github.com/hyperledger/besu/tree/0.9.0) (2019-01-31)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.5...0.9.0)

## [0.8.5](https://github.com/hyperledger/besu/tree/0.8.5) (2019-01-15)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.4...0.8.5)

## [0.8.4](https://github.com/hyperledger/besu/tree/0.8.4) (2019-01-15)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.3...0.8.4)

## [0.8.3](https://github.com/hyperledger/besu/tree/0.8.3) (2018-12-10)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.2...0.8.3)

## [0.8.2](https://github.com/hyperledger/besu/tree/0.8.2) (2018-11-19)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.1...0.8.2)

## [0.8.1](https://github.com/hyperledger/besu/tree/0.8.1) (2018-10-26)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.0...0.8.1)

## [0.8.0](https://github.com/hyperledger/besu/tree/0.8.0) (2018-10-26)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.0-RC2...0.8.0)

## [0.8.0-RC2](https://github.com/hyperledger/besu/tree/0.8.0-RC2) (2018-10-19)
[Full Changelog](https://github.com/hyperledger/besu/compare/0.8.0-RC1...0.8.0-RC2)

## [0.8.0-RC1](https://github.com/hyperledger/besu/tree/0.8.0-RC1) (2018-10-12)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*