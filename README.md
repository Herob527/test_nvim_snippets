# Test nvim snippets

Manual testing for of luasnip snippets

## console_snippet

Test if console snippet will have proper function name in log

Proper name if it has nearest named function or method name in log

ex.

```js
const test = () => {
  console.log("[test] -");
};
```

Should work for js, jsx, ts and tsx
