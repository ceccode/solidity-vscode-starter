# Solidity vscode starter

> This repository is a starter kit for working with Solidity (The Contract-Oriented Programming Language)

## Prerequisites

- [Node.js](https://nodejs.org/)
- The Solidity compiler and the javascript binding solcjs: `npm install -g solc` ([installing-solidity.html](http://solidity.readthedocs.io/en/develop/installing-solidity.html))
- [VS Code](https://code.visualstudio.com/)
- [VS Code extension for Solidity](https://github.com/juanfranblanco/vscode-solidity)


## Project Structure

| Name                               | Description                                                  |
| ---------------------------------- | ------------------------------------------------------------ |
| **.vscode**/                       | VS Code specific settings                                    |
| **src**/                           | source code that will be compiled to the dist dir            |
| soliumrc.json                      | Config settings                                              |


## Getting Started

* Clone this project.
* Put your .sol files in src directory

### Build 

Use solcjs (`solcjs --help`) or these pre-configured commands:

```bash
npm run build
```

Build and optimize:

```bash
npm run build-optimize
```


## Contributing

Feel free to contribute.


## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* [Juan Blanco](https://github.com/juanfranblanco) author of [Visual Studio Code extension for Solidity](https://github.com/juanfranblanco/vscode-solidity)

