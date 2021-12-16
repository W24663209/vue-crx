## 基于vue-crx二开编写谷歌插件

## 目录结构
```
├── background
│   ├── App.vue
│   ├── background.html
│   ├── background.js
│   └── 背景页.md
├── content
│   ├── App.vue
│   ├── content.html
│   ├── content.js
│   ├── index.js
│   └── 注入js页.md
├── devtools
│   ├── devtools.html
│   ├── devtools.js
│   └── 开发页.md
├── manifest.json
├── panel
│   ├── App.vue
│   ├── panel.html
│   ├── panel.js
│   └── 开发工具页.md
└── popup
    ├── App.vue
    ├── popup.html
    ├── popup.js
    └── 弹出页.md


```

* 所有可视化页面都可以在App.vue中写
* 引用ElementUI  
* 让写插件变得更简单

## 使用

```bash
## 安装依赖
npm install 
## 打包
npm build
## 开发
npm run dev
```

## 感谢

* https://github.com/ylfeng250/vue-crx
* [《Chrome插件开发全攻略》配套完整Demo](https://github.com/sxei/chrome-plugin-demo)
* [Chrome扩展及应用开发](https://github.com/Sneezry/chrome_extensions_and_apps_programming)
* [Chrome扩展及应用开发（首发版）](http://www.ituring.com.cn/book/1421?utm_source=tuicool)