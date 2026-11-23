# Better Highlights

Better Highlights (formerly Comments Highlighter) is a plugin for all JetBrains IDEs: IntelliJ IDEA, PyCharm, WebStorm, PhpStorm, Rider, CLion, GoLand, RubyMine, RustRover, Android Studio and others. It has more than 1 million downloads on the JetBrains Marketplace.

This repository is its issue tracker. The plugin source code is not here.

## Features

* Colorize comments by their first token (`*`, `!`, `?` or your own), and highlight whole regions with a background color.
* Show the cognitive complexity of each method as a live inlay hint, with an inspection that finds all methods with high complexity.
* Reference source code, files and other comments from a comment with wikilinks, such as `[[ClassName#method]]`, with go to definition, find usages and rename.
* Use gutter icons for highlights.
* Paid features: highlight keywords, methods and functions, highlight anything by regular expression, set a highlight severity, the Genese Cpx complexity algorithm, and wikilinks in Markdown and plain text files.

The full feature list and the support per language are on the Marketplace page.

## Install

Install it from the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/12895-better-highlights), or in the IDE under Settings, Plugins, Marketplace, by searching for "Better Highlights".

## Report a bug or ask for a feature

Open an [issue](https://github.com/clutcher/bh/issues) in this repository. For a bug, write the IDE and its version, the plugin version, the language of the file, and the steps to see the problem. A screenshot helps for a highlight that looks wrong.

To ask for a feature or for support of another language, open an issue too.

## Cognitive complexity and the book

The cognitive complexity hint is there to help you write code that a reader can follow. This idea is developed further in the book [Laminar Software Design](https://clutcher.dev/book/laminar-software-design/).

## License

The plugin is distributed under the [EULA](EULA.md).

Maintained by [Igor Zarvanskyi](https://clutcher.dev).
