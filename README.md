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
1、如果你没安装Package Control，请先安装，安装方法请自行百度。安装OK后，接下来步骤请参考第2步即可。

2、如果你已经安装过Package Control，安装vue高亮插件就比较方便。 
①如下图：References菜单中会出现Package Control选项。 
②点击后，弹出如下搜索框，选择Install Package或者直接输入都行。 
也可以使用快捷键Ctrl+Shift+P来召唤出Package Control 
③然后回车，出现下图搜索框，输入vue，就可以看到Vue Syntax Highlight插件选项，选中回车即可（因为我已经安装过，所以下图未出现该选项） 
④安装成功后，重新打开vue文件（如果你之前开了vue文件，一定要关闭重新打开才会变为高亮），可以发现代码都变为高亮了，并且可以进行智能提示
