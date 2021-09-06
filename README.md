# base64-browser
直接在浏览器使用的 base64 encode/decode 函数。支持中文或其他 utf8 格式的字符串

## 安装
```shell
npm i base64-browser
```

## 使用
1. 引入
```js
// CMD...
const {encode, decode} = require('base64-browser')

// ES6...
import {encode,decode} from 'base64-browser'
```

2. 使用
```js
encode("你好，世界。") // 5L2g5aW977yM5LiW55WM44CC
decode("5L2g5aW977yM5LiW55WM44CC") // 你好，世界。
```
