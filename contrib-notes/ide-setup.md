# Contributing to Concerto
* [Step-by-step development environment setup](./getting-started.md)
* Currently reading ->  [Suggested IDE setup](./ide-setup.md)
* [Coding Guidelines](./coding-guidelines.md)
* [Pull Request Guidelines](./submitting-pull-request.md)
* [Release process](./release-process/weekly-qa-validation.md)

# IDE setup for Concerto development

Both Atom.io and VS Code are popular editors amongst the Concerto contributors.

# Using Atom

[Atom](https://atom.io/) is the preferred code editor for contributors the Concerto project.  Many developers find Atom especially productive due to the wide range of plugins availability to assist with code development activities. These include syntax highlighting for node.js code, JavaScript and the Concerto modeling language, or *linting* to help eliminate potential bugs and ensure a consistent coding style. Developers can also develop their own plugins. Here's a list of Atom plugins for you consider as you develop within the Concerto project.

## JavaScript and Node.js linting

Use the [linter-eslint plugin](https://atom.io/packages/linter-eslint) to help with linting node.js and JavaScript code. For an example of the eslinter config file see [here](../packages/composer-admin/.eslintrc.yml).

## Concerto modelling language

Use the [composer-atom plugin](https://github.com/hyperledger/composer-atom-plugin) for syntax highlighting of the Concerto modelling language.  Follow the instructions in the README to install the plugin.

## Find unfinished work items

Use the [todo-show](https://atom.io/packages/todo-show) plugin to find indicators that code might not be complete by finding instances of indicative text, such as *TODO*, *FUTURE*, *BUG* etc.

## Match selected keywords

Use the [highlight-selected plugin](https://atom.io/packages/highlight-selected) to find all matches of a keyword in the current file.

## Documentation assistance

Use the [docblockr plugin](https://atom.io/packages/docblockr) to create pretty comments, function prototypes and other helpful code decorations.

## File type visualization

Use the [file-icons plugin](https://atom.io/packages/file-icons) to assign visual representations to file extension to help locate files of a given type.

# Using VSCode
_to do_

# Next step

Move on to read  [Coding Guidelines](./coding-guidelines.md)

## License <a name="license"></a>
Hyperledger Project source code files are made available under the Apache License, Version 2.0 (Apache-2.0), located in the LICENSE file. Hyperledger Project documentation files are made available under the Creative Commons Attribution 4.0 International License (CC-BY-4.0), available at http://creativecommons.org/licenses/by/4.0/.