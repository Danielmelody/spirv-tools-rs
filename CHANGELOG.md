# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

<!-- next-header -->
## [Unreleased] - ReleaseDate
## [0.3.1] - 2020-12-17
### Fixed
- [PR#13](https://github.com/EmbarkStudios/spirv-tools-rs/pull/13) Fix the spirv-as and spirv-val tool arguments that were broken by [PR#12](https://github.com/EmbarkStudios/spirv-tools-rs/pull/12).

## [0.3.0] - 2020-12-17
### Added
- [PR#12](https://github.com/EmbarkStudios/spirv-tools-rs/pull/12) Added the ability to disassemble binary to text.

### Fixed
- [PR#12](https://github.com/EmbarkStudios/spirv-tools-rs/pull/12) Fixed several bugs in the optimizer, as well as the command line for the validator.

## [0.2.0] - 2020-12-14
### Fixed
- [PR#9](https://github.com/EmbarkStudios/spirv-tools-rs/pull/9) Fixed bug in the compiled optimizer that resulted in no output. Thanks [@khyperia](https://github.com/khyperia)!

## [0.1.1] - 2020-11-18
### Added
- [PR#4](https://github.com/EmbarkStudios/spirv-tools-rs/pull/4) added more clear compile errors if neither of the `use-*-tools` features are enabled for either `spirv-tools` or `spirv-tools-sys`.

### Changed
- [PR#4](https://github.com/EmbarkStudios/spirv-tools-rs/pull/4) made `use-compiled-tools` the default feature for `spirv-tools-sys`. This would only affect direct consumers of `spirv-tools-sys`.

## [0.1.0] - 2020-11-13
### Added
- Added initial implementation, which includes the assembler, validator, and most of the optimizer, which meets the current needs of rust-gpu.

<!-- next-url -->
[Unreleased]: https://github.com/EmbarkStudios/spirv-tools-rs/compare/0.3.1...HEAD
[0.3.1]: https://github.com/EmbarkStudios/spirv-tools-rs/compare/0.3.0...0.3.1
[0.3.0]: https://github.com/EmbarkStudios/spirv-tools-rs/compare/0.2.0...0.3.0
[0.2.0]: https://github.com/EmbarkStudios/spirv-tools-rs/compare/0.1.1...0.2.0
[0.1.1]: https://github.com/EmbarkStudios/spirv-tools-rs/compare/0.1.0...0.1.1
[0.1.0]: https://github.com/EmbarkStudios/spirv-tools-rs/releases/tag/0.1.0