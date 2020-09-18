# express-pack
Node app template that uses webpack configured for separate frontend and backend bundles.
- *Webpack* configured to build separate frontend and backend bundles
- *webpack-dev-middleware* and *webpack-hot-middleware* for hot module reloading
- *Node.js* backend with *Express* server
- *Babel* compiler
- *ESLint* linter
## Installation
Fork/copy the repository then install dependencies
```bash
npm i
```
## Development setup
Build development server
```bash
npm run build-dev-server
```
Nodemon
```bash
npm run nodemon
```
## Production setup
Build then start app
```bash
npm run build
npm start
```
