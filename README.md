# Reactjs
## VS Code Reactjs snippets
-------------------

[![Version](http://vsmarketplacebadge.apphb.com/version/xabikos.ReactSnippets.svg)](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
[![Installs](http://vsmarketplacebadge.apphb.com/installs/xabikos.ReactSnippets.svg)](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)
[![Ratings](https://vsmarketplacebadge.apphb.com/rating/xabikos.ReactSnippets.svg)](https://marketplace.visualstudio.com/items?itemName=xabikos.ReactSnippets)

This extension contains code snippets for [Reactjs][react] and is based on the awesome [babel-sublime-snippets][babelsublime] package.

## Installation

In order to install an extension you need to launch the Command Pallete (Ctrl + Shift + P or Cmd + Shift + P) and type Extensions.
There you have either the option to show the already installed snippets or install new ones.

## Supported languages (file extensions)
* JavaScript (.js)
* TypeScript (.ts)
* JavaScript React (.jsx)
* TypeScript React (.tsx)
* JSX after installing the [corresponding extension](https://marketplace.visualstudio.com/items?itemName=TwentyChung.jsx)

## Breaking change in version 1.0.0
Up until verion 1.0.0 all the [JavaScript snippets][javacript] where part of the extension. In order to avoid duplication
the snippets are now included only to this extension and if you want to use them you have to install it explicitly.

## Usage
When installing the extension React development could be really fun
![create react component](images/component.gif)

As VS Code from version 0.10.10 supports React components syntax inside js files the snippets are available for JavaScript language as well.
In the following example you can see the usage of a React stateless component with prop types snippets inside a js and not jsx file.
![create react stateless component](images/stateless.gif)


## Snippets

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

| Trigger  | Content |
| -------: | ------- |
| `rcc→`   | class component default export skeleton |
| `rjcc→`  | class component skeleton without import of default export |
| `rccp→`  | class component default export skeleton with prop types |
| `rjccp→` | class component skeleton with prop types, without import or default export |
| `rmcc→`  | mobx class component default export skeleton |
| `rmjcc→` | mobx class component skeleton without import or default export |
| `rmccp→` | mobx class component default export skeleton with prop types |
| `rmjccp→`| mobx class component skeleton with prop types, without import or default export |
| `rsc→`   | inline SFC default export skeleton |
| `rscb→`  | SFC default export skeleton |
| `rjsc→`  | inline SFC without import or export |
| `rjscb→` | SFC without import or export |
| `rscp→`  | inline SFC with prop types default export skeleton |
| `rscbp→` | SFC with prop types default export skeleton |
| `rjscp→` | inline SFC with prop types, without import or export |
| `rjscbp→`| SFC with prop types, without import or export |
| `rmsc→`   | mobx inline SFC default export skeleton |
| `rmscb→`  | mobx SFC default export skeleton |
| `rmjsc→`  | mobx inline SFC without import or export |
| `rmjscb→` | mobx SFC without import or export |
| `rmscp→`  | mobx inline SFC with prop types default export skeleton |
| `rmscbp→` | mobx SFC with prop types default export skeleton |
| `rmjscp→` | mobx inline SFC with prop types, without import or export |
| `rmjscbp→`| mobx SFC with prop types, without import or export |
| `rcfc→`  | class component skeleton that contains all the lifecycle methods |
| `rpt→`   | empty propTypes declaration |
| `con→`   | class default constructor with props|
| `conc→`  | class default constructor with props and context |
| `est→`   | empty state object |
| `cwm→`   | `componentWillMount method` |
| `cdm→`   | `componentDidMount method` |
| `cwr→`   | `componentWillReceiveProps method` |
| `scu→`   | `shouldComponentUpdate method` |
| `cwup→`  | `componentWillUpdate method` |
| `cdup→`  | `componentDidUpdate method` |
| `cwun→`  | `componentWillUnmount method` |
| `ren→`   | `render method` |
| `sst→`   | `this.setState with object as parameter` |
| `ssf→`   | `this.setState with function as parameter` |
| `props→` | `this.props` |
| `state→` | `this.state` |
| `bnd→`   | `binds the this of method inside the constructor` |

The following table lists all the snippets that can be used for prop types.
Every snippet regarding prop types begins with ```pt``` so it's easy to group it all together and explore all the available options.
On top of that each prop type snippets has one equivalent when we need to declare that this property is also required.
For example ```pta``` creates the ```PropTypes.array``` and ```ptar``` creates the ```PropTypes.array.isRequired```

| Trigger  | Content |
| -------: | ------- |
| `pta→`   | `PropTypes.array,` |
| `ptar→`  | `PropTypes.array.isRequired,` |
| `ptb→`   | `PropTypes.bool,` |
| `ptbr→`  | `PropTypes.bool.isRequired,` |
| `ptf→`   | `PropTypes.func,` |
| `ptfr→`  | `PropTypes.func.isRequired,` |
| `ptn→`   | `PropTypes.number,` |
| `ptnr→`  | `PropTypes.number.isRequired,` |
| `pto→`   | `PropTypes.object.,` |
| `ptor→`  | `PropTypes.object.isRequired,` |
| `pts→`   | `PropTypes.string,` |
| `ptsr→`  | `PropTypes.string.isRequired,` |
| `ptnd→`  | `PropTypes.node,` |
| `ptndr→` | `PropTypes.node.isRequired,` |
| `ptel→`  | `PropTypes.element,` |
| `ptelr→` | `PropTypes.element.isRequired,` |
| `pti→`   | `PropTypes.instanceOf(ClassName),` |
| `ptir→`  | `PropTypes.instanceOf(ClassName).isRequired,` |
| `pte→`   | `PropTypes.oneOf(['News', 'Photos']),` |
| `pter→`  | `PropTypes.oneOf(['News', 'Photos']).isRequired,` |
| `ptet→`  | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]),` |
| `ptetr→` | `PropTypes.oneOfType([PropTypes.string, PropTypes.number]).isRequired,` |
| `ptao→`  | `PropTypes.arrayOf(PropTypes.number),` |
| `ptaor→` | `PropTypes.arrayOf(PropTypes.number).isRequired,` |
| `ptoo→`  | `PropTypes.objectOf(PropTypes.number),` |
| `ptoor→` | `PropTypes.objectOf(PropTypes.number).isRequired,` |
| `ptsh→`  | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}),` |
| `ptshr→` | `PropTypes.shape({color: PropTypes.string, fontSize: PropTypes.number}).isRequired,` |


[react]: https://facebook.github.io/react/
[babelsublime]: https://github.com/babel/babel-sublime-snippets
[javacript]: https://github.com/xabikos/vscode-javascript
