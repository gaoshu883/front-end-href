# 前端资料分类整理


## 工具

+ [Box Shadow CSS Generator | CSSmatic](http://www.cssmatic.com/box-shadow)
+ 占位图片
    * <del>[Placehold.it](http://placehold.it/) 访问快</del>
    * <del>[placeholder images for every case](http://lorempixel.com/)</del>
    * <del>[PLACEMAT](https://placem.at/) 图美，访问慢</del>
    * [generative placeholders](https://generative-placeholders.glitch.me/) 几何图案占位图
+ [乱数假文](http://cn.lipsum.com/)
+ Icon font:
    * [We Love Icon Fonts](http://weloveiconfonts.com/)
    * [Iconfont-阿里巴巴矢量图标库](http://iconfont.cn/)
    * [Pixel Perfect Icon Solutions](https://icomoon.io/)--矢量图转成字体
+ [unicode-table](https://unicode-table.com/en/)
+ <del>[HTML特殊字符大全](http://www.grycheng.com/tools/string.html)</del> 链接已失效
+ 免费的高质量的图片库
    * [Unsplash](https://unsplash.com/)
    * [pixabay](https://pixabay.com/)
+ [可视化正则](https://regexper.com/)
+ Let's google 
   * [蓝灯](https://github.com/getlantern/forum)
   * [西游](https://xiyou360.net/)
+ [测试用在线视频地址](https://www.jianshu.com/p/75a7db26d1d7)
+ 前端数据mock
   * [easy-mock](https://github.com/easy-mock/easy-mock)
   * [fastmock](https://www.fastmock.site/)
   * [yapi](https://github.com/YMFE/yapi)
+ [数据接口](https://api.isoyu.com/#/)

## Git
+ [把 master 分支下的 dist 文件夹推送到 gh-pages 分支](https://segmentfault.com/q/1010000007913675)
+ [git拉取远程指定分支到本地](https://www.cnblogs.com/hamsterPP/p/6810831.html)

## VSCode 
+ Setting Sync 插件
   + [使用方法](https://www.jianshu.com/p/0a273bf2a986)
   + [在不同设备上同步需要注意的问题](https://juejin.im/entry/5b57d3c0f265da0fa959bbf5)
+ vetur 插件
   + [VSCode中使用vetur插件格式化vue文件时，js代码会被添加上分号且单引号会转变为双引号](https://segmentfault.com/q/1010000011675886/a-1020000011676399)
+ 配置
   + "editor.foldingStrategy": "indentation"  根据缩进折叠代码
   + "editor.formatOnSave": true  保存代码时自动格式化
   + "editor.formatOnType": true  键入后自动设置行的格式
+ 快捷键
   + `Ctrl/Command + k + 0` 折叠代码
   + `Ctrl/Command + k + j` 展开代码

## Webpack
+ [webpack-dev-server无法通过ip访问](https://github.com/webpack/webpack-dev-server/issues/147)
   + --host 0.0.0.0

## Vue
+ [vue项目如何引入babel-polyfill](https://segmentfault.com/q/1010000012736467)
  * [babel-polyfill和tranform-runtime的比较](https://www.jianshu.com/p/844cf15341b3)

## 本地部署Easy-mock锦囊
+ [windows10启动redis总是一闪而过](https://blog.csdn.net/qq_40361770/article/details/80454248)
   + [CMD命令进入某个目录](https://blog.csdn.net/aidenliu/article/details/5390113)
+ [mongoDB无法链接，多半是node.js的版本问题，降低到8.x即可](https://github.com/easy-mock/easy-mock/issues/269)
+ [配置中的host：0.0.0.0 指代了本机所有的IP，所以，设置成0.0.0.0，就能通过本机的ip进行访问了](https://www.jianshu.com/p/ba8abad56ba9)
   + [localhost是域名](https://www.zhihu.com/question/23940717)


## 也许用的上
+ [一步步教你Android反编译](https://juejin.im/post/5aed9694518825673e358436)
   + 如果apktool反编译失败，多半是apktool的版本问题：[stackoverflow上的问答](https://stackoverflow.com/questions/30054156/apktools-apk-studio-could-not-decode-arsc-file)
   + 安装apktool的正确步骤请参考：[Install Instructions](https://ibotpeaches.github.io/Apktool/install/)
   + 如果反编译还失败，也许是路径问题，试试把apk放在桌面上再反编译
   + 如果反编译的结果没有dex文件，是反编译的太过了，试试：apktool d -s dem.apk命令（-s），具体参考了这里：[怎样反编译 Android APK？
](https://www.zhihu.com/question/29370382)
   + 其余就按照[一步步教你Android反编译](https://juejin.im/post/5aed9694518825673e358436)进行操作即可查看到源码了
   

## HTML & CSS

+ [我的HTML会说话——从实用出发，谈谈HTML的语义化](https://segmentfault.com/a/1190000004179484)
+ [怪异模式（Quirks Mode）对 HTML 页面的影响](https://www.ibm.com/developerworks/cn/web/1310_shatao_quirks/)
+ [20 Years of CSS](https://www.w3.org/Style/CSS20/?utm_source=CSS-Weekly&utm_campaign=Issue-244&utm_medium=email)
+ [A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)
+ [各个平台下相对比较好的 Web 英文字体分别是什么？](https://www.zhihu.com/question/20405658)
+ [CSS font-family 网页字体使用小结](http://moxfive.xyz/2015/12/09/css-font-family/)

## JavaScript

+ [A Short History of JavaScript](https://www.w3.org/community/webed/wiki/A_Short_History_of_JavaScript)
+ [How to Learn JavaScript Properly](http://javascriptissexy.com/how-to-learn-javascript-properly/)
    * 中文版：[如何正确学习JavaScript](http://www.shejidaren.com/how-to-learn-javascript.html?from=androidqq)
+ [JavaScript内部原理实践——真的懂JavaScript吗？](http://www.360doc.com/content/13/1105/19/9200790_326857427.shtml)
+ [我们应该如何去了解JavaScript引擎的工作原理](http://www.nowamagic.net/librarys/veda/detail/1579)
+ [Is floating point math broken?](http://stackoverflow.com/questions/588004/is-floating-point-math-broken)
+ [为什么JavaScript里函数的arguments只是array-like object?](https://www.zhihu.com/question/50803453/answer/122786182)
+ [为什么不要直接在Object.prototype上定义方法？](https://www.zhihu.com/question/26924011)
+ [回调函数（callback）是什么？](https://www.zhihu.com/question/19801131)
+ [关于JavaScript单线程的一些事](https://github.com/JChehe/blog/blob/master/posts/%E5%85%B3%E4%BA%8EJavaScript%E5%8D%95%E7%BA%BF%E7%A8%8B%E7%9A%84%E4%B8%80%E4%BA%9B%E4%BA%8B.md)
+ [JavaScript 既是单线程又是异步的，请问这二者是否冲突，以及有什么区别？](https://www.zhihu.com/question/20866267)
+ [JavaScript 运行机制详解：再谈Event Loop](http://www.ruanyifeng.com/blog/2014/10/event-loop.html)
+ [Javascript异步编程的4种方法](http://www.ruanyifeng.com/blog/2012/12/asynchronous%EF%BC%BFjavascript.html)
+ [探索Javascript异步编程](http://web.jobbole.com/82291/)
+ [【Javascript设计模式3】-观察者模式](http://www.alloyteam.com/2012/10/commonly-javascript-design-pattern-observer-mode/)
+ [最全面的JavaScript调试技巧总结](http://www.codeceo.com/article/javascript-debug-skills.html)

## JavaScript Quiz

+ [14题](http://perfectionkills.com/javascript-quiz/)
+ [44题](http://javascript-puzzlers.herokuapp.com/)

## ECMAScript2015(ES6)

+ [ECMAScript 6 会重蹈 ECMAScript 4 的覆辙吗？](https://www.zhihu.com/question/24715618/answer/34813745)
    * 这篇文章是2014年的，当时ES6还未发布
+ [ECMAScript 6 入门](http://es6.ruanyifeng.com/)
+ [DrkSephy/es6-cheatsheet](https://github.com/DrkSephy/es6-cheatsheet)

## JSON

+ [JSON在线视图查看器(Online JSON Viewer)](http://www.bejson.com/jsonviewernew/)

## jQuery教程和技巧

+ [jQuery技巧集锦](https://teakki.com/@dongcheng)

## 前端框架

+ [Vue vs React: Javascript 框架之战](http://www.zcfy.cc/article/vue-vs-react-battle-of-the-javascript-frameworks-3310.html)

## 浏览器相关

+ [浏览器的工作原理：新式网络浏览器幕后揭秘](https://www.html5rocks.com/zh/tutorials/internals/howbrowserswork/)

## 有趣的内容

+ [Pure CSS minesweeper（纯CSS实现的扫雷小游戏）](http://codepen.io/bali_balo/pen/BLJONk?utm_source=CSS-Weekly&utm_campaign=Issue-234&utm_medium=email)

## 在线学习

+ [Udacity-优达学城](https://cn.udacity.com/)
+ [FreeCodeCamp-中文版](https://freecodecamp.cn/)
+ [Code School](https://www.codeschool.com/)
+ [Codecademy](https://www.codecademy.com/learn/all)
+ [百度前端技术学院](http://ife.baidu.com/)
+ [慕课网](http://www.imooc.com/)
