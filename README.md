# AutoPercentLayoutList
#Android屏幕适配方案，直接填写设计图上的像素尺寸即可完成适配。
#使用该库可以让您：
#1.再也不用拿着设计稿去想这控件的宽高到底取多少dp
#2.再也不用去为多个屏幕去写多个dimens
#3.再也不用去计算百分比了（如果使用百分比控件完成适配）
#4.再也不用去跟UI MM去解释什么是dp了
#如何使用该库呢？
#第一步：
在你的项目的AndroidManifest中注明你的设计稿的尺寸。
#<meta-data android:name="design_width" android:value="768">
#</meta-data>
#<meta-data android:name="design_height" android:value="1280">
#</meta-data>
#第二步：

让你的Activity继承自AutoLayoutActivity.

如果有什么疑问可以发送邮箱：545381409@qq.com向我提问问题，或者有新的想法可以跟我一起讨论