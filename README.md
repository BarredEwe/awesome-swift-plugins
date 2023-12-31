![Swift Plugins](https://i.postimg.cc/zX00Tfsn/Frame-2455.jpg)

- [Frameworks with plugins](#frameworks-with-plugins)
- [Guides](#guides)

## Frameworks with plugins

&#x25CF; [**Apollo iOS**](https://github.com/apollographql/apollo-ios) - A strongly-typed, caching GraphQL client, written in Swift
  * [InstallCLI](https://github.com/apollographql/apollo-ios) - Installs the Apollo iOS Command line interface.

&#x25CF; [**Benchmark**](https://github.com/ordo-one/package-benchmark) - Benchmark allows you to easily create sophisticated Swift performance benchmarks.
  * [BenchmarkPlugin](https://github.com/ordo-one/package-benchmark) - Plugin that generates the boilerplate needed to interface with the Benchmark infrastructure.

&#x25CF; [**CodegenKit**](https://github.com/omochi/CodegenKit) - This is a framework for introducing code generation on your Swift project.
  * [CodegenKitPlugin](https://github.com/omochi/CodegenKit) - After writing renderers, generate codes. Perform code generation with plugin.

&#x25CF; [**DiscordBM**](https://github.com/DiscordBM/DiscordBM) - A New Multiplatform Swift Discord Library, Primarily For Making Bots.
  * [GenerateAPIEndpoints](https://github.com/DiscordBM/DiscordBM) - Add Generated Endpoints.

&#x25CF; [**LicensePlist**](https://github.com/mono0926/LicensePlist) - A license list generator of all your dependencies for iOS applications
  * [LicensePlistBuildTool](https://github.com/mono0926/LicensePlist) - Plugin, which automatically generates a Plist of all your dependencies.

&#x25CF; [**Lighter**](https://github.com/Lighter-swift/Lighter) - A set of technologies applying code generation to access SQLite3 databases from Swift.
  * [Enlighter](https://github.com/Lighter-swift/Lighter) - A SwiftPM build plugin that searches for SQLite databases and .sql files within the selected targets, and then generates Swift sources to use those databases.
  * [Generate Code for SQLite](https://github.com/Lighter-swift/Lighter) - Generate Swift code for SQLite DBs into the Sources directory.

&#x25CF; [**LiveViewNative**](https://github.com/liveview-native/liveview-client-swiftui) - The LiveViewNative Swift package lets you use Phoenix LiveView to build native iOS apps with SwiftUI.
  * [BuiltinRegistryGeneratorPlugin](https://github.com/liveview-native/liveview-client-swiftui) - Builtin registry generator Plugin.
  * [DocumentationExtensionGeneratorPlugin](https://github.com/liveview-native/liveview-client-swiftui) - This command generates documentation extension markdown files.
  * [SortDocumentationJSONPlugin](https://github.com/liveview-native/liveview-client-swiftui) - This command sorts the JSON files in the docs repo folder.

&#x25CF; [**Orion**](https://github.com/theos/orion) - A DSL for elegant tweak development in Swift.
  * [OrionPlugin](https://github.com/theos/orion) - A plugin for running Orion Preprocessor.

&#x25CF; [**Prefire**](https://github.com/BarredEwe/Prefire) - A library for easily generating automatic Playbook view and Tests using SwiftUI Preview.
  * [PrefireTestsPlugin](https://github.com/BarredEwe/Prefire#swift-package-plugin) - Generation Snapshot and Accesability tests.
  * [PrefirePlaybookPlugin](https://github.com/BarredEwe/Prefire#swift-package-plugin) - Generation Playbook view.

&#x25CF; [**R.swift**](https://github.com/mac-cain13/R.swift) - Get strong typed, autocompleted resources like images, fonts and segues in Swift projects.
  * [RswiftGenerateResources](https://github.com/mac-cain13/R.swift#packageswift-based-spm-project) - A plugin for generation strong typed autocompleted resources.

&#x25CF; [**SecretsManager**](https://github.com/vdka/SecretsManager) - Effortless Secrets Management for Swift projects using Code Generation.
  * [SecretsManagerPlugin](https://github.com/vdka/SecretsManager) - Using this plugin the following Swift code is generated and available directly to your targets source code.

&#x25CF; [**SmokeFrameworkApplicationGenerate**](https://github.com/amzn/smoke-framework-application-generate) - Code generator to generate SmokeFramework-based applications from service models.
  * [SmokeFrameworkGenerateClient](https://github.com/amzn/smoke-framework-application-generate) - The SPM plugin with a model defined in a seperate package by declaring that package as a dependency of the targets using the generator.

&#x25CF; [**Sourcery**](https://github.com/krzysztofzablocki/Sourcery) - A code generator for Swift language, built on top of Apple's own SwiftSyntax.
  * [SourceryCommandPlugin](https://github.com/krzysztofzablocki/Sourcery) - Trigger Sourcery using swift plugin.

&#x25CF; [**swift-argument-parser**](https://github.com/apple/swift-argument-parser) - Straightforward, type-safe argument parsing for Swift.
  * [GenerateManual](https://github.com/apple/swift-argument-parser) - Generate a manual entry for a specified target.

 &#x25CF; [**Swift OpenAPI Generator**](https://github.com/apple/swift-openapi-generator) - Generate Swift client and server code from an OpenAPI document.
  * [OpenAPIGenerator](https://github.com/apple/swift-openapi-generator) - Swift OpenAPI Generator package plugin.

&#x25CF; [**SwiftFormat**](https://github.com/nicklockwood/SwiftFormat) - SwiftFormat is a code library and command-line tool for reformatting Swift code.
  *  [SwiftFormatPlugin](https://github.com/nicklockwood/SwiftFormat#swift-package-manager-plugin) - Trigger SwiftFormat using swift plugin.

&#x25CF; [**SwiftGen**](https://github.com/SwiftGen/SwiftGen) - А tool to automatically generate Swift code for resources of your projects, to make them type-safe to use.
  * [**SwiftGenPlugin**](https://github.com/SwiftGen/SwiftGenPlugin) - A prebuild tool will execute it and generate your files before each build

&#x25CF; [**SwiftLint**](https://github.com/realm/SwiftLint) - A tool to enforce Swift style and conventions, loosely based on the now archived GitHub Swift Style Guide.
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
