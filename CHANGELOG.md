# RandomSkunk.Logging.Testing.Moq

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog],
and this project adheres to [Semantic Versioning].

## [Unreleased]

## [1.1.0] - 2023-01-02

### Added

- Add overload of `VerifyLog` that doesn't have a `configureQuery` parameter, which makes verifying any log invocation easier.

## [1.0.0] - 2022-04-25

### Added

- Create initial project, solution, and package structures.
- Add `TestingLogger`, an implementation of `ILogger` for testing.
- Add `TestingLogger<TCategoryName>`, an implementation of `ILogger<TCategory>` for testing.
- Add `MockLogger`, an inheritor of `Mock<TestingLogger>`.
- Add `VerifyLog` & `SetupLog` extension methods.

[Keep a Changelog]: https://keepachangelog.com/en/1.0.0/
[Semantic Versioning]: https://semver.org/spec/v2.0.0.html
[Unreleased]: https://github.com/bfriesen/RandomSkunk.Logging.Testing.Moq/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/bfriesen/RandomSkunk.Logging.Testing.Moq/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/bfriesen/RandomSkunk.Logging.Testing.Moq/compare/v0.0.0...v1.0.0
