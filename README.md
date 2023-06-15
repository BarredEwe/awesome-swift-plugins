![Swift Plugins](https://i.postimg.cc/zX00Tfsn/Frame-2455.jpg)

- [Frameworks with plugins](#frameworks-with-plugins)
- [Guides](#guides)

## Frameworks with plugins

* [**Benchmark**](https://github.com/ordo-one/package-benchmark) - Benchmark allows you to easily create sophisticated Swift performance benchmarks.
  * [BenchmarkPlugin](https://github.com/ordo-one/package-benchmark) - Plugin that generates the boilerplate needed to interface with the Benchmark infrastructure.
* [**CodegenKit**](https://github.com/omochi/CodegenKit) - This is a framework for introducing code generation on your Swift project.
  * [CodegenKitPlugin](https://github.com/omochi/CodegenKit) - After writing renderers, generate codes. Perform code generation with plugin.
* [**Lighter**](https://github.com/Lighter-swift/Lighter) - A set of technologies applying code generation to access SQLite3 databases from Swift.
  * [Enlighter](https://github.com/Lighter-swift/Lighter) - A SwiftPM build plugin that searches for SQLite databases and .sql files within the selected targets, and then generates Swift sources to use those databases.
  * [Generate Code for SQLite](https://github.com/Lighter-swift/Lighter) - Generate Swift code for SQLite DBs into the Sources directory.
* [**Orion**](https://github.com/theos/orion) - A DSL for elegant tweak development in Swift.
  * [OrionPlugin](https://github.com/theos/orion) - A plugin for running Orion Preprocessor.
* [**Prefire**](https://github.com/BarredEwe/Prefire) - A library for easily generating automatic Playbook view and Tests using SwiftUI Preview.
  * [PrefireTestsPlugin](https://github.com/BarredEwe/Prefire#swift-package-plugin) - Generation Snapshot and Accesability tests.
  * [PrefirePlaybookPlugin](https://github.com/BarredEwe/Prefire#swift-package-plugin) - Generation Playbook view.
* [**R.swift**](https://github.com/mac-cain13/R.swift) - Get strong typed, autocompleted resources like images, fonts and segues in Swift projects.
  * [RswiftGenerateResources](https://github.com/mac-cain13/R.swift#packageswift-based-spm-project) - A plugin for generation strong typed autocompleted resources.
* [**SecretsManager**](https://github.com/vdka/SecretsManager) - Effortless Secrets Management for Swift projects using Code Generation.
  * [SecretsManagerPlugin](https://github.com/vdka/SecretsManager) - Using this plugin the following Swift code is generated and available directly to your targets source code.
* [**Sourcery**](https://github.com/krzysztofzablocki/Sourcery) - A code generator for Swift language, built on top of Apple's own SwiftSyntax.
  * [SourceryCommandPlugin](https://github.com/krzysztofzablocki/Sourcery) - Trigger Sourcery using swift plugin.
* [**SwiftFormat**](https://github.com/nicklockwood/SwiftFormat) - SwiftFormat is a code library and command-line tool for reformatting Swift code.
  *  [SwiftFormatPlugin](https://github.com/nicklockwood/SwiftFormat#swift-package-manager-plugin) - Trigger SwiftFormat using swift plugin.
* [**SwiftLint**](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions, loosely based on the now archived GitHub Swift Style Guide.
  * [SwiftLintPlugin](https://github.com/realm/SwiftLint#plug-in-support) - SwiftLint can be used as a build tool plug-in for both Xcode projects as well as Swift packages.

## Guides

### Official Guides

* [Github: Swift Package Manager](https://github.com/apple/swift-package-manager/blob/main/Documentation/Plugins.md#getting-started-with-plugins) - This guide provides a brief overview of Swift Package Manager plugins, describes how a package can make use of plugins, and shows how to get started writing your own plugins.
* [WWDC](https://developer.apple.com/videos/play/wwdc2022/110359) - Meet Swift Package plugins. Discover how you can perform actions on Swift packages and Xcode projects with Swift package plugins.
* [WWDC](https://developer.apple.com/videos/play/wwdc2022/110401) - Create Swift Package plugins. Tailor your development workflow and learn how to write your own package plugins in Swift.

### Third party Guides
* [WWDC Notes](https://www.wwdcnotes.com/notes/wwdc22/110359/) - WWDC Notes is an open-source and community-driven effort to collect notes for all Apple's WWDC videos.
* [The.Swift.Dev.](https://theswiftdev.com/beginners-guide-to-swift-package-manager-command-plugins/) - Learn how to create command plugins for the Swift Package Manager to execute custom actions using SPM and other tools.
* [Polpiella](https://www.polpiella.dev/code-generation-using-swift-package-plugins/) - Code generation using Swift Package Plugins.

## Contributing

Contributions are most welcome!
