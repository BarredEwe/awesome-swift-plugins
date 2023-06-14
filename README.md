# awesome-swift-plugins

- [Guides](#guides)
- [Frameworks](#frameworks)

## Guides
*An awesome list of Swift related guides.* 

### Official Guides

* [Swift Package Manager: Plugins](https://github.com/apple/swift-package-manager/blob/main/Documentation/Plugins.md#getting-started-with-plugins) - This guide provides a brief overview of Swift Package Manager plugins, describes how a package can make use of plugins, and shows how to get started writing your own plugins.
* [WWDC](https://developer.apple.com/videos/play/wwdc2022/110359) - Discover how you can perform actions on Swift packages and Xcode projects with Swift package plugins.

### Third party Guides
* [WWDC Notes](https://www.wwdcnotes.com/notes/wwdc22/110359/) - WWDC Notes is an open-source and community-driven effort to collect notes for all Apple's WWDC videos.
* [The.Swift.Dev.](https://theswiftdev.com/beginners-guide-to-swift-package-manager-command-plugins/) - Learn how to create command plugins for the Swift Package Manager to execute custom actions using SPM and other tools.
* [Polpiella](https://www.polpiella.dev/code-generation-using-swift-package-plugins/) - Code generation using Swift Package Plugins

## Frameworks with plugins

* [Benchmark](https://github.com/ordo-one/package-benchmark) - Benchmark allows you to easily create sophisticated Swift performance benchmarks
  * [BenchmarkPlugin](https://github.com/ordo-one/package-benchmark/blob/5bc62b1b3ba8d4b03b93735e5a74e80b0aa5b4da/Package.swift#L52) - Plugin that generates the boilerplate needed to interface with the Benchmark infrastructure
* [Prefire](https://github.com/BarredEwe/Prefire) - A library for easily generating automatic Playbook view and Tests using SwiftUI Preview.
  * [PrefireTestsPlugin](https://github.com/BarredEwe/Prefire/blob/0cb793810b9dfe42cf07e79e3b8559e476105e80/Package.swift#L36) - Generation Snapshot and Accesability tests
  * [PrefirePlaybookPlugin](https://github.com/BarredEwe/Prefire/blob/0cb793810b9dfe42cf07e79e3b8559e476105e80/Package.swift#L29) - Generation Playbook view
* [R.swift](https://github.com/mac-cain13/R.swift) - Get strong typed, autocompleted resources like images, fonts and segues in Swift projects
  * [RswiftGenerateResources](https://github.com/mac-cain13/R.swift/blob/5721c1a948429232718fcbea3eb6132675192a72/Package.swift#L15) - A plugin for generation strong typed autocompleted resources
* [SwiftLint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions, loosely based on the now archived GitHub Swift Style Guide.
  * [SwiftLintPlugin](https://github.com/realm/SwiftLint/blob/c8cd311615ad3c1772fd0795e865c5f0ae069578/Package.swift#L23) - SwiftLint can be used as a build tool plug-in for both Xcode projects as well as Swift packages.
