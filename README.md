# Reactjs
## VS Code Reactjs snippets 
-------------------
This extension contains code snippets for [Reactjs][react] and is based on the awesome [babel-sublime-snippets][babelsublime] package.

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

## Usage
When installing the extension React development could be really fun 
![create react component](images/component.gif)

In order for the snippets to be available you need to either have the extension jsx to the source files or to select the JavaScript React language for the available options in the bottom right menu.

## JavaScript snippets
Except the snippets described below you can use all the [JavaScript snippets from the corresponding extension][javacript]

## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component skeleton |
| `rccp→`  | class component skeleton with prop types after the class |
| `rcfp→`  | class component skeleton that contains all the lifecycle methods |
| `con→`   | class default constructor |
| `cwm→`   | `componentWillMount method` |
| `cdm→`   | `componentDidMount method` |
| `cwr→`   | `componentWillReceiveProps method` |
| `scu→`   | `shouldComponentUpdate method` |
| `cwup→`  | `componentWillUpdate method` |
| `cdup→`  | `componentDidUpdate method` |
| `cwun→`  | `componentWillUnmount method` |
| `ren→`   | `render method` |
| `sso→`   | `this.setState with object as parameter` |
| `ssf→`   | `this.setState with function as parameter` |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `bnd→`   | `binds the this of method inside the constructor` |

## Known issues

Currently the available snippets are not shown automatically as it happens for JavaScript snippets. You can bypass that by hitting Ctrl + Space or Cmd + Space based on the operating system. This is a known issue and will be fixed in the upcoming versions. 


[react]: https://facebook.github.io/react/
[babelsublime]: https://github.com/babel/babel-sublime-snippets
[javacript]: https://github.com/xabikos/vscode-javascript