# Space UI
 UI for the trading space

#Repository 
repo location for Space UI

# Pre-requisites

### node.js

In command prompt or terminal, type

```bash
node -v
```

You should get the version number, e.g. `v5.10.0`.


## Installing Pre-requisites
If you have the pre-requisites installed, you may skip this section.

### node.js

Browse to https://nodejs.org/ and download the relevant flavour for your OS. Get the latest version, it should be `v5.10.1` (as of writing).

Run the installer to get `node` & `npm` installed.

### GIT
Install [Git](https://git-scm.com/downloads).

### Developer Tools
Install [React developer tools](https://chrome.google.com/webstore/detail/react-developer-tools/fmkadmapgofadopljbjfkapdkoienihi?hl=en) and [Redux Dev Tools](https://chrome.google.com/webstore/detail/redux-devtools/lmhkpmbekcpmknklioeibfkpmmfibljd?hl=en) in Chrome. (Optional, but helpful.)


## Setting up the project

Once the pre-requisites are sorted out, browse to the root directory of this project.

Run

```bash
npm install
```

## Running the project

In the root folder of the project, run

```bash
npm start
```

When you see `Listening on port 3000` is printed on the command prompt or terminal, the web server has started and browsing to http://localhost:3000 should bring you to the dashboard.

##Technologies

| **Tech** | **Description** |
|----------|-------|
|  [React](https://facebook.github.io/react/)  |   Fast, composable client-side components. | 
|  [Redux](http://redux.js.org) |  Enforces unidirectional data flows and immutable, hot reloadable store. Lean alternative to [Facebook's Flux](https://facebook.github.io/flux/docs/overview.html).|
|  [React Router](https://github.com/reactjs/react-router) | A complete routing library for React | 
|  [React Hot Loader](https://gaearon.github.io/react-hot-loader) | A stable for daily use in development implementation of React live code editing |
|  [Redux Thunk](https://github.com/gaearon/redux-thunk) | [A complete example](http://redux.js.org/docs/advanced/ExampleRedditAPI.html) |
|  [Babel](http://babeljs.io) |  Compiles ES6 to ES5. Enjoy the new version of JavaScript today. [ES6 REPL](https://babeljs.io/repl/), [ES6 vs ES5](http://es6-features.org), [ES6 Katas](http://es6katas.org)|
| [Webpack](http://webpack.github.io) | Bundles npm packages and our JS into a single file. | 
| [SASS](http://sass-lang.com/) | Compiled CSS styles with variables, functions, and more. |
| [ESLint](http://eslint.org/)| Lint JS. Reports syntax and style issues. Using [eslint-plugin-react](https://github.com/yannickcr/eslint-plugin-react) for additional React specific linting rules. | 

