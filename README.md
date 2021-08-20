# React Webpack

React Webpack development platform. Similar to CRA, but more lightweight and customizable. Includes **react-refresh**.

---

## Notes

Currently includes both CSS and SCSS module importing - remove as necessary.

---

## Issues

- `browserlist.development` breaks **react-refresh** with current version of **webpack-dev-server**. [See thread](https://github.com/pmmmwh/react-refresh-webpack-plugin/issues/235). Add later to **package.json**: `"development": [ "last 1 chrome version", "last 1 firefox version", "last 1 safari version" ]`
