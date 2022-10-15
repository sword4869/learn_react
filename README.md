# setup

```bash
$ npx create-react-app <project-name>
```

```bash
.
├── node_modules
├── public
├── src
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── package.json
├── package-lock.json
└── README.md
```

# 1
## 1

![picture 3](/image/0aa99764acdb1edd67a99339a7ad1452da9fbc2d29e70e22b18c20e9ba35f867.png)  


![picture 1](/image/0e866078f95e816c77cb41045b82852933cd5dbed0c6506772d64d7c49df555d.png)  

html内容被注入到 `<div id="root">`中。

## 2

![picture 2](/image/a10593c729178540170e8b5c535343ae461106e72a9abb9d2cf9e326c6104d1d.png)  

将 html 内容写成一个组件。
- 这是一个类
- 类里有一个`render()`方法，此方法返回html内容。为了标识清晰，约定使用`()`包裹html内容。


PS：
- jsx和js一样（都是可以在js中写html）
- 为了标识清晰（因为显示的图标不同)，约定使用jsx来作为页面的后缀
- 为了标识清晰，约定页面文件名首字母大写