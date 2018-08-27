# 谷歌代码高亮插件

##用法：
- 将prettify.css和prrttify.js静态文件引入到需要代码高亮的页面，在script中加上
$(window).load(function () {
    $("pre").addClass("prettyprint linenums");
    prettyPrint(); 
});
