# Zed React JavaScript Snippets

A comprehensive collection of React, JavaScript, TypeScript, and React Native snippets for the Zed editor to accelerate your development workflow.

## Installation

1. Open Zed editor
2. Go to \`Extensions\` in the command palette (\`Cmd+K\`)
3. Search for "React Snippets"
4. Click \`Install\`

## ✨ Features

This extension provides comprehensive snippets for:

- **React Components** - Functional, Class, Pure, Memo components (JavaScript/JSX)
- **TypeScript React Components** - TypeScript-specific React and React Native components
- **React Hooks** - useState, useEffect, useCallback, useMemo, useRef, and more
- **Redux** - Actions, reducers, selectors, Redux Toolkit slices, and connect patterns
- **React Native** - Mobile components with and without StyleSheet
- **PropTypes** - Complete PropTypes definitions and validation
- **Console Methods** - Comprehensive console logging utilities (log, warn, error, table, time, etc.)
- **Testing** - Jest and React Testing Library test blocks
- **ES6+ JavaScript** - Modern JavaScript features (arrow functions, destructuring, promises, async/await)
- **DOM Manipulation** - querySelector, event listeners, and DOM methods
- **Imports/Exports** - ES6 module system, React Router, and more
- **Class Features** - Classes, methods, getters, setters, static methods
- **Array/Object Methods** - map, filter, reduce, forEach, Object utilities
- **Utility Functions** - Loops, conditionals, promises, fetch, localStorage, and more

## 📝 Snippet Categories

### React Components (JavaScript/JSX)

| Prefix | Description |
|--------|-------------|
| `rafce` | React Arrow Function Component with ES7 export |
| `rafcp` | React Arrow Function Component with PropTypes |
| `rfce` | React Functional Component with ES7 export |
| `rfcp` | React Functional Component with PropTypes |
| `rmc` | React Memo Function Component |
| `rmcp` | React Memo Function Component with PropTypes |
| `rpc` | React Pure Component Class |
| `rpce` | React Pure Component Class with export |
| `rpcp` | React Pure Component Class with PropTypes |
| `rccp` | React Component Class with PropTypes |
| `rcredux` | React Component with Redux connect |
| `rcreduxp` | React Component with Redux and PropTypes |
| `rfcredux` | React Functional Component with Redux |

### TypeScript Components

| Prefix | Description |
|--------|-------------|
| `tsrfc` | TypeScript React Functional Component |
| `tsrafc` | TypeScript React Arrow Function Component |
| `tsrce` | TypeScript React Component Class |
| `tsrpce` | TypeScript React Pure Component |
| `tsrcredux` | TypeScript React Component with Redux |
| `exptp` | Export TypeScript Type |
| `expint` | Export TypeScript Interface |

### React Native Components

| Prefix | Description |
|--------|-------------|
| `rnf` | React Native Functional Component |
| `rnfs` | React Native Functional Component with Styles |
| `rnfe` | React Native Functional Export Component |
| `rnfes` | React Native Functional Export Component with Styles |
| `rnc` | React Native Class Component |
| `rnce` | React Native Class Component Export |
| `rncs` | React Native Class Component with Styles |
| `rnpc` | React Native Pure Component |
| `rnpce` | React Native Pure Component Export |
| `rnstyle` | React Native StyleSheet |
| `tsrnf` | TypeScript React Native Functional Component |
| `tsrnfs` | TypeScript React Native Functional Component with Styles |

### React Hooks

| Prefix | Description |
|--------|-------------|
| `useStateSnippet` | useState Hook |
| `useEffectSnippet` | useEffect Hook with cleanup |
| `useContextSnippet` | useContext Hook |
| `useReducerSnippet` | useReducer Hook |
| `useCallbackSnippet` | useCallback Hook |
| `useMemoSnippet` | useMemo Hook |
| `useRefSnippet` | useRef Hook |
| `useImperativeHandleSnippet` | useImperativeHandle Hook |
| `useLayoutEffectSnippet` | useLayoutEffect Hook |

### Component Lifecycle & Class Methods

| Prefix | Description |
|--------|-------------|
| `rconst` | React Constructor with state |
| `cdm` | componentDidMount |
| `cdup` | componentDidUpdate |
| `cwun` | componentWillUnmount |
| `scu` | shouldComponentUpdate |
| `gdsfp` | getDerivedStateFromProps |
| `gsbu` | getSnapshotBeforeUpdate |
| `est` | Empty state object |
| `ssf` | setState with function |
| `props` | Access props |
| `state` | Access state |
| `bnd` | Bind method to this |

### Redux

| Prefix | Description |
|--------|-------------|
| `redux` | Import Redux connect |
| `rxaction` | Redux Action |
| `rxconst` | Redux Constant |
| `rxreducer` | Redux Reducer |
| `rxselect` | Redux Selector with reselect |
| `rxslice` | Redux Toolkit Slice |
| `reduxmap` | mapStateToProps & mapDispatchToProps |

### React Imports

| Prefix | Description |
|--------|-------------|
| `imr` | Import React |
| `imrc` | Import React with Component |
| `imrcp` | Import React with Component and PropTypes |
| `imrm` | Import React with memo |
| `imrmp` | Import React with memo and PropTypes |
| `imrpc` | Import React with PureComponent |
| `imrpcp` | Import React with PureComponent and PropTypes |
| `impt` | Import PropTypes |
| `imrd` | Import ReactDOM |
| `imrn` | Import from React Native |
| `imbr` | Import BrowserRouter |
| `imbrl` | Import Router Link |
| `imbrnl` | Import Router NavLink |
| `imbrs` | Import Router Switch |
| `imbrc` | Import Router components |
| `imrr` | Import BrowserRouter with Route and NavLink |

### PropTypes

| Prefix | Description |
|--------|-------------|
| `pta` | PropTypes array |
| `ptar` | PropTypes array required |
| `ptb` | PropTypes bool |
| `ptbr` | PropTypes bool required |
| `ptf` | PropTypes func |
| `ptfr` | PropTypes func required |
| `ptn` | PropTypes number |
| `ptnr` | PropTypes number required |
| `pto` | PropTypes object |
| `ptor` | PropTypes object required |
| `pts` | PropTypes string |
| `ptsr` | PropTypes string required |
| `ptnd` | PropTypes node |
| `ptndr` | PropTypes node required |
| `ptel` | PropTypes element |
| `ptelr` | PropTypes element required |
| `pti` | PropTypes instanceOf |
| `ptir` | PropTypes instanceOf required |
| `pte` | PropTypes oneOf (enum) |
| `pter` | PropTypes oneOf required |
| `ptet` | PropTypes oneOfType |
| `ptetr` | PropTypes oneOfType required |
| `ptao` | PropTypes arrayOf |
| `ptaor` | PropTypes arrayOf required |
| `ptoo` | PropTypes objectOf |
| `ptoor` | PropTypes objectOf required |
| `ptsh` | PropTypes shape |
| `ptshr` | PropTypes shape required |
| `ptex` | PropTypes exact |
| `ptexr` | PropTypes exact required |
| `ptany` | PropTypes any |

### React Context & Refs

| Prefix | Description |
|--------|-------------|
| `rcontext` | Create React Context |
| `cref` | Create Ref |

### Testing

| Prefix | Description |
|--------|-------------|
| `desc` | describe block |
| `test` | test block |
| `testa` | asynchronous test block |
| `tit` | it block |
| `tita` | asynchronous it block |
| `stest` | Setup React test |
| `srtest` | Setup React test with Redux |
| `sntest` | Setup React Native test |
| `snrtest` | Setup React Native test with Redux |

### Higher Order Components

| Prefix | Description |
|--------|-------------|
| `hoc` | Higher Order Component |
| `hocredux` | Higher Order Component with Redux |

### React-Specific Utilities

| Prefix | Description |
|--------|-------------|
| `cp` | Destructure props |
| `cs` | Destructure state |

## 🚀 Usage

Simply type the snippet prefix and press `Tab` to expand the snippet. Most snippets include placeholders that you can navigate through using `Tab`.

### Example

Type `rafce` and press `Tab`:

```javascript
import React from 'react'

const ComponentName = () => {
  return (
    <div>first</div>
  )
}

export default ComponentName
```

### Quick Start Examples

| Prefix | Output                                   | Description           |
| ------ | ---------------------------------------- | --------------------- |
| `log`  | `console.log($0)`                        | Console log statement |
| `af`   | `const name = (params) => {}`            | Arrow function        |
| `asf`  | `async function name() {}`               | Async function        |
| `for`  | `for (let i = 0; i < array.length; i++)` | For loop              |
| `fetch`| `fetch(url).then().catch()`              | Fetch API call        |

## 📋 JavaScript & Modern ES6+ Snippets

### Console Methods

- `log` / `clg` - Console log
- `clo` - Console log with label
- `clj` - Console log JSON.stringify
- `warn` / `cwa` - Console warn
- `error` / `cer` - Console error
- `table` / `ctl` - Console table
- `time` / `ctm` - Console time
- `cte` - Console timeEnd
- `cas` - Console assert
- `ccl` - Console clear
- `cco` - Console count
- `cdi` - Console dir
- `cgr` - Console group
- `cge` - Console groupEnd
- `ctr` - Console trace
- `cin` - Console info

### Functions

- `function` - Function declaration
- `af` / `nfn` - Arrow function (named)
- `afi` - Arrow function (implicit return)
- `anfn` - Arrow function (anonymous)
- `asf` - Async function
- `aaf` - Async arrow function
- `fn` - Anonymous function
- `iife` - Immediately Invoked Function Expression
- `iiafe` - Async IIFE

### Loops & Iteration

- `for` - For loop
- `forof` / `fof` - For...of loop
- `forin` / `fin` - For...in loop
- `while` - While loop
- `dowhile` - Do...while loop
- `fre` - Array forEach
- `map` - Array map
- `filter` - Array filter
- `reduce` - Array reduce
- `find` - Array find
- `findi` - Array findIndex
- `some` - Array some
- `every` - Array every

### Conditionals

- `if` - If statement
- `ife` - If...else statement
- `ei` - Else if statement
- `ter` - Ternary operator
- `switch` - Switch statement

### Error Handling

- `tc` - Try...catch block
- `tcf` - Try...catch...finally
- `ther` - Throw error
- `cerr` - Custom error class

### Promises & Async

- `promise` / `prom` - New Promise
- `thenc` - Promise then/catch
- `await` - Await expression
- `awaitc` - Await with try/catch

### Classes

- `class` - Class declaration
- `clm` - Class with method
- `clx` - Class extends
- `met` - Class method
- `get` / `pge` - Getter method
- `set` / `pse` - Setter method
- `sm` - Static method

### Modules (Import/Export)

**Imports:**
- `imp` - Import default
- `imn` / `imd` - Import named/destructured
- `ima` / `ime` - Import all (as *)
- `imd` - Dynamic import (await)

**Exports:**
- `exp` - Export default
- `exd` - Export destructured
- `exa` - Export as
- `exn` - Export named
- `enf` - Export named function
- `edf` - Export default function
- `ednf` - Export default named function
- `exf` - Export function
- `exc` - Export const

### Variables & Destructuring

**Declarations:**
- `const` - Const declaration
- `let` - Let declaration
- `var` - Var declaration

**Destructuring:**
- `dsta` / `dar` - Array destructuring
- `dsto` / `dob` - Object destructuring
- `spa` - Spread array
- `spo` - Spread object
- `rp` - Rest parameters

### Objects

- `obj` - Object literal
- `om` - Object with method
- `os` - Object shorthand
- `oc` - Object computed property
- `ok` - Object.keys()
- `ov` - Object.values()
- `oe` - Object.entries()
- `oa` - Object.assign()
- `ofr` - Object.freeze()
- `oseal` - Object.seal()
- `ocr` - Object.create()

### Arrays & Collections

- `array` - Array literal
- `afrom` - Array.from()
- `aof` - Array.of()
- `nset` - New Set
- `nmap` - New Map
- `nws` - New WeakSet
- `nwm` - New WeakMap

### Strings

- `tl` - Template literal
- `tt` - Tagged template
- `match` - String match
- `replace` - String replace
- `split` - String split
- `trim` - String trim
- `includes` - String includes
- `startswith` - String startsWith
- `endswith` - String endsWith
- `padstart` - String padStart
- `padend` - String padEnd
- `repeat` - String repeat

### Timers

- `sto` / `sti` - setTimeout / setInterval
- `si` - setInterval
- `cto` - clearTimeout
- `ci` - clearInterval

### Fetch & JSON

- `fetch` - Fetch API
- `feta` - Fetch async/await
- `fetp` - Fetch POST request
- `jsp` - JSON.parse()
- `jss` - JSON.stringify()
- `jssp` - JSON.stringify() (pretty)

### DOM Manipulation

- `qs` - querySelector
- `qsa` - querySelectorAll
- `gid` - getElementById
- `gcl` - getElementsByClassName
- `gt` - getElementsByTagName
- `cel` - createElement
- `ael` - addEventListener
- `rel` - removeEventListener
- `domr` - DOMContentLoaded
- `wl` - Window load event
- `raf` - requestAnimationFrame

### Storage

- `lss` - localStorage.setItem()
- `lsg` - localStorage.getItem()
- `lsr` - localStorage.removeItem()
- `lsc` - localStorage.clear()
- `sss` - sessionStorage.setItem()
- `ssg` - sessionStorage.getItem()

### Advanced Features

- `gen` - Generator function
- `agen` - Async generator
- `proxy` - Proxy object
- `rget` - Reflect.get()
- `sym` - Symbol
- `symf` - Symbol.for()

### Regular Expressions

- `re` - RegExp pattern
- `ret` - RegExp test

### Math & Date

- `mra` - Math.random()
- `mfl` - Math.floor()
- `mce` - Math.ceil()
- `mro` - Math.round()
- `mmax` - Math.max()
- `mmin` - Math.min()
- `dnow` - Date.now()
- `ndate` - New Date()
- `diso` - ISO date string

### Operators & Type Checking

- `tof` / `tpf` - typeof check
- `iof` - instanceof check
- `nc` - Nullish coalescing (??)
- `oc` - Optional chaining (?.)

### Documentation & Comments

- `cmt` / `cmmb` - Comment block
- `jsdoc` - JSDoc function documentation
- `us` - Use strict mode

## 🎯 Smart Placeholders

All snippets include intelligent placeholders that enhance your coding workflow:

- **Tab Navigation**: Press `Tab` to jump between placeholders in logical order
- **Auto-Fill Component Names**: Many React snippets use `${TM_FILENAME_BASE}` to automatically name components based on your file name
- **Smart Defaults**: Placeholders include sensible default values (e.g., `ComponentName`, `props`, `state`)
- **Contextual Hints**: Placeholder names provide context about what should be entered
- **Multiple Variations**: Many snippets have variants (with/without PropTypes, with/without Redux, etc.)

### Example Workflow

1. Type snippet prefix (e.g., `rafce`)
2. Press `Tab` to expand
3. Component name auto-fills from filename or use placeholder
4. Press `Tab` to move to next editable section
5. Continue until snippet is complete

## 🎯 Tips

- Use `${TM_FILENAME_BASE}` placeholders to auto-fill component names based on your file name
- Navigate through snippet placeholders using `Tab`
- Most snippets support multiple variations (with/without PropTypes, with/without Redux, etc.)
- TypeScript snippets are available within JavaScript files
- React Native snippets work in all JavaScript contexts
- Modern JavaScript utilities support ES6+ features (arrow functions, destructuring, async/await)
- DOM manipulation snippets work seamlessly with vanilla JavaScript projects
- All console methods include proper placeholder positioning for quick debugging

## 📄 Supported File Types

This extension provides snippets for JavaScript files with full React/JSX support:
- **JavaScript (`.js`)** - All JavaScript and JSX/React snippets
- **JSX (`.jsx`)** - All JavaScript and JSX/React snippets

**Note:** The snippets work in both `.js` and `.jsx` files, supporting modern React development where JSX is commonly used in `.js` files. TypeScript support (`.ts`, `.tsx`) requires a separate TypeScript-specific extension.

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new snippets or improvements to existing ones, please feel free to submit a pull request or open an issue.


## 👤 Author

**Chirag Saxena**

## 🔗 Repository

[https://github.com/allindiacoderlife/zed-react-javascript-snippets](https://github.com/allindiacoderlife/zed-react-javascript-snippets)

---

**Happy Coding!** 🚀
**Enjoy faster React development with Zed React JavaScript Snippets! 🚀**
