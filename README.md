# gradio-node-fix
Fixes runtime errors when using `@gradio/client` outside of a browser.

Includes a slightly modified version of the [`eventsource` polyfill](https://www.npmjs.com/package/eventsource), and sets a couple props on `window`.

To use it, simply `import "gradio-node-fix"` at the top of your JS entrypoint (index.ts, index.js, etc).
