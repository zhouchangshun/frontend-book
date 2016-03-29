# 频繁触发事件的性能问题
我们经常遇到由于事件频繁的调用方法，因而导致频繁操作 DOM、加载资源等大量的计算，从而导致 UI 卡顿甚至是浏览器崩溃的现象。主要场景如下
* 浏览器滚动时绑定了事件（onscroll）；
* 浏览器大小改变时绑定了事件（onresize）;
* 