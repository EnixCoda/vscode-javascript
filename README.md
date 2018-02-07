# JavaScript
## VS Code JavaScript (ES6) snippets
-------------------

This project is forked from [xabikos/vscode-javascript](https://github.com/xabikos/vscode-javascript).

This extension contains code snippets for JavaScript in ES6 syntax for [Vs Code][code] editor (supports both JavaScript and TypeScript).

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones. Search for *JavaScript code snippets* and install it.

## Supported languages (file extensions)
* JavaScript (.js)
* TypeScript (.ts)
* JavaScript React (.jsx)
* TypeScript React (.tsx)
* Vue (.vue)

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

### Import and export
| Trigger  | Description | Content |
| -------: | ------- | ------- |
| imp | Imports entire module statement in ES6 syntax | import ${2:moduleName} from '${1:module}'$0 |
| imp{} | Imports entire module in ES6 syntax without module name | import '${1:module}'$0 |
| impall | Imports all as alias from the module in ES6 syntax | import * as ${2:alias} from '${1:module}'$0 |
| impas | Imports a specific portion of the module by assigning a local alias in ES6 syntax | import { ${2:originalName} as ${3:alias} } from '${1:module}'$0 |
| expc | Export const value in ES6 syntax | export const ${1:functionName}\n |
| expd | Export default value in ES6 syntax | export default ${1:params} |
| afn | Creates an anonymous function in ES6 syntax | (${1:params}) => {\n\t${2}\n} |
| pms | Creates and returns a new Promise in the standard ES6 syntax | new Promise((resolve, reject) => {\n\t${1}\n}) |
| clg | Displays a message in the console | console.log(${1:object}) |
