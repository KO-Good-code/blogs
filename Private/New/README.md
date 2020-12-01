# 新知识笔记

## Node

`const validateProjectName = require('validate-npm-package-name')`：检测 `packageName` 是否合法。

`fs.existsSync`：检测目录是否存在。

`fs.remove(targetDir)`：删除目录。

```js
exports.getPromptModules = () => {
  return [
    "babel",
    "typescript",
    "pwa",
    "router",
    "vuex",
    "cssPreprocessors",
    "linter",
    "unit",
    "e2e",
  ].map((file) => require(`../promptModules/${file}`));
};
```

模块选择配置器。

## Css

`pointer-events` CSS 属性指定在什么情况下 (如果有) 某个特定的图形元素可以成为鼠标事件的 target。
