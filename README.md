# trace-design-instrumenter README

This PR contains a VS Code extension that automates dynamic trace instrumentation and assists with capturing the semantic relationships between design abstractions to enable automated debugging.

## Features

- Automatically instrument the dynamic trace. 
- Provide interface for instrumenting design semantics (constraints, failure modalities).
- Generate files which describe the project structure for individual programs and systems.
- Intelligent modifications to instrumentation when code changes are introduced.
- Provide an interface to run the instrumented program in one step for simplicity.
- Serve [trace viewer][trace-viewer] and open generated trace file for immediate automated debugging.
- Alternatively, bring trace viewer into VSCode environment (but this is not necessary right now).
- Provide an interface to generate a file that intergrates into production pipelines. 
- Provide a visual overview of the semantic design graph.
- More to come. 

## Following extension guidelines

Ensure that you've read through the extensions guidelines and follow the best practices for creating your extension.

* [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines)

## For more information

* [Visual Studio Code's Markdown Support](http://code.visualstudio.com/docs/languages/markdown)
* [Markdown Syntax Reference](https://help.github.com/articles/markdown-basics/)

[trace-viewer]: https://github.com/vishalpalaniappan/diagnostic-log-viewer
