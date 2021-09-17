<!--
 * @Author: your name
 * @Date: 2021-09-17 14:22:46
 * @LastEditTime: 2021-09-17 16:18:03
 * @LastEditors: your name
 * @Description: In User Settings Edit
 * @FilePath: \vue3.2-demo\src\assets\notes\webpack.md
-->
## loader

### babel-loader (js)

* 使用 Babel 和 webpack 转译 JavaScript 文件

### cache-loader (loader)

* 在一些性能开销较大的 loader 之前添加此 loader，以将结果缓存到磁盘里

### less-loader (less)

* webpack 将 Less 编译为 CSS

### postcss-loader (css)

* 使用 PostCSS 处理 CSS

### css-loader (css)

* 对 css 中 @import 和 url() 进行处理

### style-loader/vue-style-loader (css)

* 把 CSS 插入到 DOM 中

### sass-loader (scss/sass)

* 加载 Sass/SCSS 文件并将他们编译为 CSS

### file-loader (font/image/media/svg)

* 处理 import/require() 成 url 并发送到 output 目录中

### url-loader (font/image/media)

* 将文件作为 data URI 内联到 bundle 中

### vue-loader (vue)

* 加载并编译 Vue 组件

## plugin

### DefinePlugin

* 在 编译时 创建可以配置的全局常量

### case-sensitive-paths-webpack-plugin

* 强制所有模块的完整路径必须与磁盘上的路径的确切大小写一致

### friendly-errors-webpack-plugin

* 识别某些 webpack 错误并整理，以提供开发人员更好的体验

### HotModuleReplacementPlugin

* 热模块更新

### ProgressPlugin

* 提供了一种自定义编译期间进度报告方式的方法

### HtmlWebpackPlugin

* 根据模板或使用加载器生成 html 文件

### PreloadPlugin 

* 在 HtmlWebpackPlugin 生成的 html 中添加预加载

### CopyWebpackPlugin

* 将单个文件或整个目录复制到构建目录

### mini-css-extract-plugin (css)

* 将 css 提取到单独的文件，为每个包含 css 的 js 文件创建一个 css 文件

### optimize-css-assets-webpack-plugin

* 用于在构建期间优化/最小化 css 文件

### compression-webpack-plugin

* 为 js/html/css 开启 gzip 压缩
