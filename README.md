# trace-design-instrumenter

This repo contains a VS Code extension that automates dynamic trace instrumentation and assists with instrumenting the semantic relationships between design abstractions to enable automated debugging.

## Features

### Basic features:
- Automatically instrument the dynamic trace. 
- Provide interface for instrumenting design semantics (constraints, failure modalities).
- Provide an interface to instrument and run program in one step for ease of use.
- Serve [trace viewer][trace-viewer] and open generated trace file for automated debugging.

### Future Features
- Intelligent modifications to instrumentation when code changes are introduced.
- Alternatively, bring trace viewer into VSCode environment (but this is not necessary right now).
- Provide an interface to generate a file that integrates into production pipelines.
- Provide a visual overview of the semantic design graph.
- More to come. 

## Following extension guidelines

Ensure that you've read through the extensions guidelines and follow the best practices for creating your extension.

* [Extension Guidelines](https://code.visualstudio.com/api/references/extension-guidelines)

[trace-viewer]: https://github.com/vishalpalaniappan/diagnostic-log-viewer
