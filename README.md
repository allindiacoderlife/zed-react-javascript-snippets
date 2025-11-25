# Zed React JavaScript Snippets

A comprehensive collection of React, JavaScript, TypeScript, and React Native snippets for the Zed editor to accelerate your development workflow.

## Installation

1. Open Zed editor
2. Go to \`Extensions\` in the command palette (\`Cmd+K\`)
3. Search for "React Snippets"
4. Click \`Install\`

## ✨ Features

This extension provides snippets for:

- **React Components** - Functional, Class, Pure, Memo components
- **TypeScript Support** - TypeScript-specific React components
- **React Hooks** - useState, useEffect, useCallback, and more
- **Redux** - Actions, reducers, selectors, and Redux Toolkit
- **React Native** - Mobile components with and without styles
- **PropTypes** - Complete PropTypes definitions
- **Console Methods** - Various console logging utilities
- **Testing** - Jest and React Testing Library snippets
- **ES6+ Utilities** - Imports, exports, destructuring, and more

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

### Imports

| Prefix | Description |
|--------|-------------|
| `imp` | Import module |
| `imr` | Import React |
| `imrc` | Import React with Component |
| `imrcp` | Import React with Component and PropTypes |
| `imrm` | Import React with memo |
| `imrmp` | Import React with memo and PropTypes |
| `imrpc` | Import React with PureComponent |
| `imrpcp` | Import React with PureComponent and PropTypes |
| `impt` | Import PropTypes |
| `imrd` | Import ReactDOM |
| `imd` | Import destructured |
| `ima` | Import as |
| `ime` | Import everything as |
| `imn` | Import without module name |
| `imrn` | Import from React Native |
| `imbr` | Import BrowserRouter |
| `imbrl` | Import Router Link |
| `imbrnl` | Import Router NavLink |
| `imbrs` | Import Router Switch |
| `imbrc` | Import Router components |
| `imrr` | Import BrowserRouter with Route and NavLink |

### Exports

| Prefix | Description |
|--------|-------------|
| `exp` | Export default |
| `exd` | Export destructured |
| `exa` | Export as |
| `enf` | Export named function |
| `edf` | Export default function |
| `ednf` | Export default named function |

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

### Console Methods

| Prefix | Description |
|--------|-------------|
| `clg` | console.log |
| `clo` | console.log with label |
| `clj` | console.log JSON.stringify |
| `cas` | console.assert |
| `ccl` | console.clear |
| `cco` | console.count |
| `cdi` | console.dir |
| `cer` | console.error |
| `cgr` | console.group |
| `cge` | console.groupEnd |
| `ctr` | console.trace |
| `ctm` | console.time |
| `cte` | console.timeEnd |
| `cwa` | console.warn |
| `cin` | console.info |
| `ctl` | console.table |

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

### JavaScript Utilities

| Prefix | Description |
|--------|-------------|
| `cp` | Destructure props |
| `cs` | Destructure state |
| `dob` | Destructure object |
| `dar` | Destructure array |
| `nfn` | Named arrow function |
| `anfn` | Anonymous arrow function |
| `met` | Class method |
| `pge` | Getter |
| `pse` | Setter |
| `fre` | forEach |
| `fof` | for...of loop |
| `fin` | for...in loop |
| `sti` | setInterval |
| `sto` | setTimeout |
| `prom` | Promise |
| `tpf` | typeof |
| `cmmb` | Comment block |

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

## 🎯 Tips

- Use `${TM_FILENAME_BASE}` placeholders to auto-fill component names based on your file name
- Navigate through snippet placeholders using `Tab`
- Most snippets support multiple variations (with/without PropTypes, with/without Redux, etc.)
- TypeScript snippets are available in `.ts` and `.tsx` files
- React Native snippets work in all JavaScript/TypeScript contexts

## 📄 Supported File Types

- JavaScript (`.js`)
- JSX (`.jsx`)
- TypeScript (`.ts`)
- TSX (`.tsx`)

## 🤝 Contributing

Contributions are welcome! If you have suggestions for new snippets or improvements to existing ones, please feel free to submit a pull request or open an issue.


## 👤 Author

**Chirag Saxena**

## 🔗 Repository

[https://github.com/allindiacoderlife/zed-react-javascript-snippets](https://github.com/allindiacoderlife/zed-react-javascript-snippets)

---

**Happy Coding!** 🚀
**Enjoy faster React development with Zed React JavaScript Snippets! 🚀**
