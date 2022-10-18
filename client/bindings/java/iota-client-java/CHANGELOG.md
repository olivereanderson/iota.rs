# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- ## Unreleased - YYYY-MM-DD

### Added

### Changed

### Deprecated

### Removed

### Fixed

### Security -->

## 1.0.0-rc.2 - 2022-10-17

### Added

- Allow integers values in QueryParams;

### Changed

- Improve performance of tests by avoiding unnecessary indexer requests;

## 1.0.0-rc.1 - 2022-09-29

### Added

- Client APIs:
    - `BaseApi`;
    - `HighLevelApi`;
    - `MiscellaneousApi`;
    - `NodeCoreApi`;
    - `NodeIndexerApi`;
    - `UtilsApi`;

- Examples:
    - `CreateBlock`;
    - `GenerateAddresses`
    - `GenerateMnemonic`;
    - `GetBlock`;
    - `GetBlockMetadata`;
    - `GetBlockRaw`;
    - `GetHealth`;
    - `GetInfo`;
    - `GetMilestoneById`;
    - `GetMilestoneByIdRaw`;
    - `GetMilestoneByIndex`;
    - `GetMilestoneByIndexRaw`;
    - `GetOutputs`;
    - `GetReceipts`;
    - `GetReceiptsMigratedAt`;
    - `GetTips`;
    - `GetTreasury`;
    - `GetUtxoChangesById`;
    - `GetUtxoChangesByIndex`;
    - `PostBlock`;
    - `PostBlockRaw`;
    - `PrepareAndSignTransaction`;

### Changed

- Rust interaction through a JSON passing approach;

### Removed

- All glue code;