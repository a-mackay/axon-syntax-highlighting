# Axon Syntax Highlighting

A Visual Studio Code extension which provides syntax highlighting for the Axon programming language.
The Axon programming language is a part of SkyFoundry LLC's "SkySpark" software for building analytics.

Highlighting gets applied in .axon and .trio files.
Trio files are treated as being primarily for Axon source code, meaning tags which are not "src" tags are treated as code comments.

Pull requests welcome.

## Known Issues

* Adding a unit of measurement to a literal will stop it from being recognised as a literal.