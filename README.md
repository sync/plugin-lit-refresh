# @dblechoc/plugin-lit-refresh

Provides Lit HMR support support for Vite. State won't reload, just styles.

Basically [dev-server-hmr](https://github.com/open-wc/open-wc/blob/master/packages/dev-server-hmr/src/wcHmrRuntime.js) republished for Vite.

```js
// vite.config.js
import LitRefresh from "@dblechoc/plugin-lit-refresh";

export default {
  plugins: [LitRefresh()],
};
```
