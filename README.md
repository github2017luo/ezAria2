# ezAria2
一个ARIA2的windows GUI项目，完全基于.net，而非web ui加壳。

## 开发进度

* 180311 现在允许添加一个HTTP/HTTPS的下载地址，能够正确将下载任务添加到ARIA2，并且实时更新下载进度和速度等信息。
* 180312 更新了一些显示元素
* 180314 实现了主页面的第二个按钮功能，选择一个任务后点击可以暂停/重新开始该任务
* 180314 修正了两个会导致程序崩溃的逻辑错误
* 180321 由于工作失误，丢失了最近一周的工作进度。
* 180322 修复多个错误.
* 180421 修复多个错误，实现历史任务列表功能
* 180422 更新主页面的控件，修复一些脑洞大开的错误，增加系统托盘菜单
## 预期功能

1. 使用GUI实现aria2的所有命令
2. 完成对aria2 Notice的解析
3. ~~通过其他开源库，完成对ed2k协议的支持（有生之年系列，求推荐些简单易懂的emule开源库）~~基于Ed2k协议的本质思想是共享而非下载，因此无法在不伤害Ed2k社区的前提下实现轻量级的Ed2k下载

## 许可和引用

* 依照GPL V2许可发布
* [Arthas的WPF开源控件类库](https://github.com/1217950746/Arthas-WPFUI)MIT许可
* [Websocket-Sharp](https://github.com/sta/websocket-sharp)MIT许可
