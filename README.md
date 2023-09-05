# Pharo wiki

Wiki for the [Pharo](https://pharo.org/features) programming language and development environment.

The goals of the wiki are explained in the [Manifest](MANIFEST.md) and contribution guidelines in the [Contribution guide](CONTRIBUTION.md).

> Looking for a list of awesome projects? Check-out [awesome-pharo](https://github.com/pharo-open-documentation/awesome-pharo), a curated list of awesome Pharo projects.

- [Pharo wiki](#pharo-wiki)
  * [Beginners](#beginners)
  * [General](#general)
    + [Infrastructure](#infrastructure)
    + [Pharo Language](#pharo-language)
    + [Pharo Tooling](#pharo-tooling)
  * [Pharo projects](#pharo-projects)
  * [Pharo and OpenSmalltalk Virtual Machine](#pharo-and-opensmalltalk-virtual-machine)
  * [External projects](#external-projects)
    + [Data exchange](#data-exchange)
    + [Data structures](#data-structures)
  * [Migration guidelines](#migration-guidelines)
  * [External resources](#external-resources)

## Beginners

- [Setting up a new project](General/SettingUpANewProject.md) ![Unfinished](https://img.shields.io/badge/Progress-Unfinished-yellow.svg?style=flat)
- [Things beginners must learn](General/MustKnowForBeginners.md)
- [Interesting things to know for beginners](General/InterestingsToKnowForBeginners.md)
- [How to run Pharo from the command line](General/HowToRunPharoFromCommandLine.md) - How to run pharo from the command line.
- [Glossary](General/Glossary.md) ![Unfinished](https://img.shields.io/badge/Progress-Unfinished-yellow.svg?style=flat)

## General

### Infrastructure

- [How to deal with baselines](General/Baselines.md) - Configure your project and its dependencies.
- [Setup your CI through github actions](General/GithubActions.md) - Setup your CI via GitHub actions for your Pharo projects.
- [Pharo code export formats](General/ExportFormats.md) - Explanations about code formats used to export code to VCS such as git.
- [How to deploy a pharo application](General/DeployYourPharoApplication.md) - A guide to deploy a Pharo application.
- [Windows 10 Subsystem For Linux (WSL)](General/Windows10SubsystemForLinux.md) - Getting Pharo to run on Windows 10 Subsystem for Linux.
- [Using CJK (Chinese, Japanese, and Korean) characters](General/CJKCharacter.md) - Guide to help you configure Pharo to support Chinese, Japanese, and Korean characters.
- [Using CJK input methods](General/CJKInputMethod.md) - Guide to help you configure Pharo to support CJK input method.
- [Tweaking big images](General/TweakingBigImages.md) - Tips to make large pharo images more responsive.
- [Image file format](General/ImageFileFormat.md) - Documentation about binary format of Pharo images.
- [How to setup a travis build](General/Travis.md) - How to have automated build on travis

### Pharo Language

- [Extension methods](General/Extensions.md) - How to extend existing classes in your packages.
- [Traits](General/Traits.md) - Structure to build classes via composition.
- [Some cool snippets in Pharo](General/CoolSnippets.md) - A cook book to answer common needs of a Pharo developer.
- [Progress bar](General/ProgressBar.md) - Display a progress bar to give feedback to the user.
- [Morphic Layouts](General/Layout.md) - Documentation about the layout management in the Morphic Library of pharo.
- [Pragmas](General/Pragmas.md) - A guide on Pragmas, annotations to compiled methods to add additional properties.
- [Coding conventions](General/CodingConventions.md) - A list of convention to follow when writing Pharo code.
- [Exceptions](General/Exceptions.md) - How Pharo's exceptions work and explanations on how to use them.
- [Sorting collections](General/SortingCollections.md) - How to sort collections with Pharo's built-in API.
- [Sessions management](General/SessionsManagement.md) - Documentation on setting up start-up and shut-down actions in Pharo.

### Pharo Tooling

- [Playground](General/Playground.md) - Documentation on the usage of Pharo's playground.
- [Inspector](General/Inspector.md) - Documentation on the usage of Pharo's inspector.
- [Profiling](General/Profiling.md) - Measure the time and space your program takes to execute.
- [Menubar and World menu](General/MenuBar.md) - A guide to configure and customize Pharo's menubar and world menu.
- [Iceberg on Windows workaround](General/IcebergOnWindows.md) - Troubleshooting for some issues appearing when using Iceberg on Windows.
- [Refactoring](General/Refactorings.md) - Documentation on the usage of Pharo refactoring's tool.
- [Settings](General/Settings.md) - How to use Pharo's settings system to define your own settings.

## Pharo projects

<!-- - [How to deal with files](PharoProjects/Files.md) ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat) -->
<!-- - [Objects serialization](PharoProjects/ObjectsSerialization.md) - Lists possibilities to serialize your objects on disk. ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat) -->
- [Announcer](PharoProjects/Announcer.md) - Implementation of the observer design pattern built-in Pharo.
- [Basic interactions with OS](PharoProjects/OS.md)
- [Cursor](PharoProjects/Cursor.md)
- [Dynamic variables](PharoProjects/DynamicVariables.md)
- [Numbers](PharoProjects/Numbers.md)
- [Rich text](PharoProjects/RichText.md)
- [WebBrowser](PharoProjects/WebBrowser.md) - A project to open a link in the default web browser.<!-- - [Metalinks](PharoProjects/Metalinks.md) ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat) -->

## Pharo and OpenSmalltalk Virtual Machine
- [Pharo VM documentation map](PharoVirtualMachine/pharo-vm-map.md) -

## External projects
### Data exchange
- [CSV support](ExternalProjects/Export/CSV.md)
- [JSON support](ExternalProjects/Export/JSON.md)
<!--
- [XML support](ExternalProjects/Export/XML.md) ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat)
- [HTML support](ExternalProjects/Export/HTML.md) ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat)
- [Arff support](ExternalProjects/Export/Arff.md) - Arff is a format defined by [Weka](http://www.cs.waikato.ac.nz/ml/weka/) to be used for data importation. ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat)
-->

<!--
### Data structures
- [DataFrame](ExternalProjects/DataStructures/DataFrame.md) ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat)
-->

## Migration guidelines

- [Migrating Streams from Pharo 6.1 to Pharo 7.0](Migration/MigrationToPharo7.md)

## External resources
- [Pharo Community](ExternalResources/Community.md) - Various links of people involved in Pharo community. Helps to discover Pharo ecosystem.
- [Contributing to Pharo](https://github.com/pharo-project/pharo/wiki/Contribute-a-fix-to-Pharo) - Official tutorial on how to contribute to Pharo using Iceberg.
- [Generating your own Pharo images (Bootstrapping)](https://github.com/carolahp/pharo/tree/candle) - Tools for generating small Pharo images from source code.
- [Magritte3 Wiki](https://github.com/seandenigris/Magritte/wiki) - Wiki related to Magritte3.
- [Sean's wiki about pharo](https://github.com/seandenigris/pharo/wiki) - The wiki of Sean P. DeNigris related to Pharo.
- [#pharotip hashtag on twitter](https://twitter.com/hashtag/pharotip) - Tweets to help new users to easily get going with Pharo, started by [@astares](https://twitter.com/TorstenAstares).

![CC](https://mirrors.creativecommons.org/presskit/icons/cc.svg)
![BY](https://mirrors.creativecommons.org/presskit/icons/by.svg)

<!---
Badges:
* ![TODO](https://img.shields.io/badge/Progress-TODO-red.svg?style=flat)
* ![Unfinished](https://img.shields.io/badge/Progress-Unfinished-yellow.svg?style=flat)
* ![Review](https://img.shields.io/badge/Progress-Review-blue.svg?style=flat)

-->
