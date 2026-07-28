# SUSTech 校友地图

这是一个由南方科技大学（SUSTech）校友组成的地图。

该项目托管于 GitHub，任何人都可以添加自己的地图信息。♥ 欢迎加入我们！

👉 __https://sustech-application.github.io/SUSTech-Alumni-Map/__

![截图](icons/SUSTech-Alumni-Map.png)

上面的截图展示了用户添加的信息在地图中的展示效果。

每个用户添加的条目都会生成一个独立的 URL，方便分享和访问，非常方便！

e.g.，这是一个指向 SUSTech 的链接：
[SUSTech](https://sustech-application.github.io/SUSTech-Alumni-Map/#home)。

## 如何添加和管理你的信息？

你可以在地图上添加自己的标记，并自行管理你的数据。

请查看 [3 种管理个人条目的方式](https://github.com/SUSTech-Application/SUSTech-Alumni-Map/tree/master/_directory)！🚀

或者直接联系我们：
[jimzhouzzy@gmail.com](jimzhouzzy@gmail.com)

## 这个地图面向谁？

该地图面向所有 SUSTech 学生和教职员工：

包括本科生、研究生以及其他成员。

它旨在可视化展示 SUSTech 校友的全球分布情况。

如果你是 SUSTech 的一员，这个地图就是为你准备的！

## 这个地图是如何工作的？

其实并不复杂：

GitHub 可以从代码仓库生成静态网站。

我们使用了 [Jekyll](https://jekyllrb.com)，这是一个基于 Ruby 的静态网站生成器。

Jekyll 自带 [Liquid](https://shopify.github.io/liquid/) 模板系统，
它帮助我们将所有地图条目信息以 JSON 的形式注入到 HTML 页面底部。

JavaScript 会读取这些数据，然后使用 [Leaflet](http://leafletjs.com)
创建一个漂亮的交互式地图。

地图瓦片由 [CARTO](https://carto.com/location-data-services/basemaps/)
提供。

——嗯，就这么简单。¯\\\_(ツ)_/¯

## 如何改进这个网站？

我们建议你先下载整个仓库的 zip 文件，
然后在本地运行起来。

具体步骤请参考：
[SETUP.md](https://github.com/SUSTech-Application/SUSTech-Alumni-Map/blob/master/SETUP.md)。

如果过程中遇到困难，我们很乐意提供帮助：

[jimzhouzzy@gmail.com](jimzhouzzy@gmail.com)

## 如何在本地运行地图？

请参考：
[SETUP.md](https://github.com/SUSTech-Application/SUSTech-Alumni-Map/blob/master/SETUP.md)
中的说明。

## 🛠️ 维护者

<div>
  <a href="https://github.com/jimzhouzzy">
    <img src="https://github.com/jimzhouzzy.png?s=460" width="100" alt="jimzhouzzy" style="border-radius: 50%;">
  </a>
</div>
