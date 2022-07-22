# Prettier-config

continuous integration prettier config

## Usage

In `prettier.config.js`
```js
module.exports = require('@douza/prettier-config')
```

In `.prettierignore`
copy from `'@douza/prettier-config/src/.prettierignore`

## Info

**file：**
- `.prettierignore`：prettierignore 基本配置

**dep：**
- `prettier-plugin-organize-imports`：按引用深度 排序 合并 删除没有使用的 `imports` 声明
- `@volar/vue-typescript`：上述插件对于单个 `vue` 文件的拓展
- `prettier-plugin-packagejson`：合理化排序 `package.json` 的 key

**dev：**
- `prettier`：格式化所有文件
- `typescript`：ts
