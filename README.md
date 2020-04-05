# Monaco Editor for Eclipse Dirigible

## Overview

Monaco Plugin for the [Eclipse Dirigible](https://github.com/eclipse/dirigible) WebIDE v3.x and above.

Build the [Eclipse Dirigible](https://github.com/eclipse/dirigible), deploy on e.g. Tomcat Web Container and go to location:

> http://localhost:8080/services/v4/web/ide-monaco/editor.html

## Update

To update the Monaco version:
1. Go to [dirigiblelabs/monaco-editor](https://github.com/dirigiblelabs/monaco-editor)
1. Fetch the latest changes from the original repository
1. Run ``npm run release``
1. Copy the release artefacts from the ``release`` folder
1. Replace the content of [ide-monaco/monaco-editor](https://github.com/dirigiblelabs/ide-monaco/tree/master/ide-monaco/monaco-editor) with the content from the ``release`` folder

## License

Forked from: [Monaco](https://github.com/Microsoft/monaco-editor)
