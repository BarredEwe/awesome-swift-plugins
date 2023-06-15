![Swift Plugins](https://i.postimg.cc/zX00Tfsn/Frame-2455.jpg)

- [Guides](#guides)
- [Frameworks with plugins](#frameworks-with-plugins)

## Guides

### Official Guides

* [Swift Package Manager: Plugins](https://github.com/apple/swift-package-manager/blob/main/Documentation/Plugins.md#getting-started-with-plugins) - This guide provides a brief overview of Swift Package Manager plugins, describes how a package can make use of plugins, and shows how to get started writing your own plugins.
* [WWDC](https://developer.apple.com/videos/play/wwdc2022/110359) - Discover how you can perform actions on Swift packages and Xcode projects with Swift package plugins.

### Third party Guides
* [WWDC Notes](https://www.wwdcnotes.com/notes/wwdc22/110359/) - WWDC Notes is an open-source and community-driven effort to collect notes for all Apple's WWDC videos.
* [The.Swift.Dev.](https://theswiftdev.com/beginners-guide-to-swift-package-manager-command-plugins/) - Learn how to create command plugins for the Swift Package Manager to execute custom actions using SPM and other tools.
* [Polpiella](https://www.polpiella.dev/code-generation-using-swift-package-plugins/) - Code generation using Swift Package Plugins

## Frameworks with plugins

* [Benchmark](https://github.com/ordo-one/package-benchmark) - Benchmark allows you to easily create sophisticated Swift performance benchmarks
  * [BenchmarkPlugin](https://github.com/ordo-one/package-benchmark) - Plugin that generates the boilerplate needed to interface with the Benchmark infrastructure
* [Prefire](https://github.com/BarredEwe/Prefire) - A library for easily generating automatic Playbook view and Tests using SwiftUI Preview.
  * [PrefireTestsPlugin](https://github.com/BarredEwe/Prefire#swift-package-plugin) - Generation Snapshot and Accesability tests
  * [PrefirePlaybookPlugin](https://github.com/BarredEwe/Prefire#swift-package-plugin) - Generation Playbook view
* [R.swift](https://github.com/mac-cain13/R.swift) - Get strong typed, autocompleted resources like images, fonts and segues in Swift projects
  * [RswiftGenerateResources](https://github.com/mac-cain13/R.swift#packageswift-based-spm-project) - A plugin for generation strong typed autocompleted resources
* [SwiftFormat](https://github.com/nicklockwood/SwiftFormat) - SwiftFormat is a code library and command-line tool for reformatting Swift code on macOS or Linux.
  *  [SwiftFormatPlugin](https://github.com/nicklockwood/SwiftFormat#swift-package-manager-plugin) - Trigger SwiftFormat using swift plugin
* [SwiftLint](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions, loosely based on the now archived GitHub Swift Style Guide.
  * [SwiftLintPlugin](https://github.com/realm/SwiftLint#plug-in-support) - SwiftLint can be used as a build tool plug-in for both Xcode projects as well as Swift packages.
* [SecretsManager](https://github.com/vdka/SecretsManager) - Effortless Secrets Management for Swift projects using Code Generation.
  * [SecretsManagerPlugin](https://github.com/vdka/SecretsManager) - Using this plugin the following Swift code is generated and available directly to your targets source code.
