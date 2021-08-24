# React Webpack

React Webpack development platform. Similar to CRA, but more lightweight and customizable. Includes **react-refresh** for a better development experience.

---

## Notes

### Proxy

By default the server runs on **8888** and proxies `/api` to `http://localhost:8080/api`. See more <a href="https://webpack.js.org/configuration/dev-server/#devserverproxy" target="_blank" rel="noreferrer">Webpack devServer.proxy</a>

### Style Import

Supports both **sass** and **css** imports. Also includes <a href="https://github.com/csstools/postcss-normalize" target="_blank" rel="noreferrer">normalize/sanitize css</a>

### Static File Serving

Files in `public` folder will be served as `/static/` in browser.

### Absolute Imports

Supports absolute imports, e.g. `import Test from '@components/Test'`. See more <a href="https://webpack.js.org/configuration/resolve/#resolvealias" target="_blank" rel="noreferrer">Webpack resolve.alias</a>

---

## Issues

- `browserlist.development` breaks **react-refresh** with current version of **webpack-dev-server**. Add later: `"development": [ "last 1 chrome version", "last 1 firefox version", "last 1 safari version" ]`
