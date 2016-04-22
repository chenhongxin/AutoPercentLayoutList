<html lang="en"><head>
    <meta charset="UTF-8">
    <title></title>
<style id="system" type="text/css">h1,h2,h3,h4,h5,h6,p,blockquote {    margin: 0;    padding: 0;}body {    font-family: "Helvetica Neue", Helvetica, "Hiragino Sans GB", Arial, sans-serif;    font-size: 13px;    line-height: 18px;    color: #737373;    margin: 10px 13px 10px 13px;}a {    color: #0069d6;}a:hover {    color: #0050a3;    text-decoration: none;}a img {    border: none;}p {    margin-bottom: 9px;}h1,h2,h3,h4,h5,h6 {    color: #404040;    line-height: 36px;}h1 {    margin-bottom: 18px;    font-size: 30px;}h2 {    font-size: 24px;}h3 {    font-size: 18px;}h4 {    font-size: 16px;}h5 {    font-size: 14px;}h6 {    font-size: 13px;}hr {    margin: 0 0 19px;    border: 0;    border-bottom: 1px solid #ccc;}blockquote {    padding: 13px 13px 21px 15px;    margin-bottom: 18px;    font-family:georgia,serif;    font-style: italic;}blockquote:before {    content:"C";    font-size:40px;    margin-left:-10px;    font-family:georgia,serif;    color:#eee;}blockquote p {    font-size: 14px;    font-weight: 300;    line-height: 18px;    margin-bottom: 0;    font-style: italic;}code, pre {    font-family: Monaco, Andale Mono, Courier New, monospace;}code {    background-color: #fee9cc;    color: rgba(0, 0, 0, 0.75);    padding: 1px 3px;    font-size: 12px;    -webkit-border-radius: 3px;    -moz-border-radius: 3px;    border-radius: 3px;}pre {    display: block;    padding: 14px;    margin: 0 0 18px;    line-height: 16px;    font-size: 11px;    border: 1px solid #d9d9d9;    white-space: pre-wrap;    word-wrap: break-word;}pre code {    background-color: #fff;    color:#737373;    font-size: 11px;    padding: 0;}@media screen and (min-width: 768px) {    body {        width: 748px;        margin:10px auto;    }}</style><style id="custom" type="text/css"></style></head>
<body marginheight="0"><h1>AutoPercentLayoutList</h1>
<p>Android屏幕适配方案，直接填写设计图上的像素尺寸即可完成适配。使用该库可以让您：
</p>
<p>1.再也不用拿着设计稿去想这控件的宽高到底取多少dp
2.再也不用去为多个屏幕去写多个dimens
3.再也不用去计算百分比了（如果使用百分比控件完成适配）
4.再也不用去跟UI MM去解释什么是dp了
</p>
<h1>如何使用该库呢？</h1>
<h1>第一步：</h1>
<p>在你的项目的AndroidManifest中注明你的设计稿的尺寸。<br>
</p>
<p>&lt;meta-data android:name="design_width" android:value="768"&gt;
&lt;/meta-data&gt;
</p>
<p>&lt;meta-data android:name="design_height" android:value="1280"&gt;
&lt;/meta-data&gt;
</meta-data></p>
<h1>第二步：</h1>
<p>让你的Activity继承自AutoLayoutActivity.

</p>
<p>如果有什么疑问可以发送邮箱：545381409@qq.com向我提问问题，或者有新的想法可以跟我一起讨论
Edit By <a href="http://mahua.jser.me">MaHua</a></p>
</body></html>