# Vue Syntax Highlight

Sublime Text Syntax highlighting for single-file [Vue.js](http://vuejs.org) components (enabled by [vue-loader](https://github.com/vuejs/vue-loader) or [vueify](https://github.com/vuejs/vueify)).

![screenshot](https://cloud.githubusercontent.com/assets/499550/11458853/99ed23aa-9696-11e5-9bf6-43c706487aee.png)

### Install

- Via Package Control: search for `Vue Syntax Highlight`.
- Manual: clone this repo into your Sublime `Packages` folder.

**NOTE:** You still need to install corresponding packages for pre-processors (e.g. Jade, SASS, CoffeeScript) to get proper syntax highlighting for them.

### Enabling JSX Highlighting

The `<script>` block uses the syntax highlighting currently active for you normal `.js` files. To support JSX highlighting inside Vue files, just set [Babel javascript highlighting package](https://packagecontrol.io/packages/Babel), which supports JSX, as your default JS highlighting. **Note you may need to explicitly disable Sublime's default `JavaScript` package to make it work.**

### License

[MIT](http://opensource.org/licenses/MIT)
1、下载packages资源，链接https://github.com/vuejs/vue-syntax-highlight

2、进入sublime/data/packages/目录下新建个VUE文件，将下载的包文件解压到新建目录文件VUE里(把vue-syntax-highlight改成vue)

3、打开sublime界面，按ctrl+shift+p弹出
4、输入install ，如果没有反应可能被墙了，打开菜单 Preferences->Packges Settings->Package Control->Setting Default，有一个外链的json文件，如果不能打开，那就是被墙了，需要翻墙进行替换下载文件。如果install有反应，那好，进行下一步，，在搜索框中输入VUE：选择vue Component
