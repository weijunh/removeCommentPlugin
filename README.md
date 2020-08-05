这是一个清除注释的 webpack 插件

1.安装插件
npm i removecommentplugin -s-d

2.在 webpack.config.js 文件中引入
const commentPlugin = require('removeCommentPlugin');

3.在 webpack 的 plugin 配置中
plugins: [
new commentPlugin()
]

github 地址:
https://github.com/weijunh/removeCommentPlugin.git
