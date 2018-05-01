# RouteTrace 绘途计划
一个涵盖中国铁路线的地标数据库。记录这些钢铁长龙的足迹，用轨迹来丈量每一寸远方。(PreBeta)


## 什么是绘途计划？

绘途计划，旨在提供一个平台让轨道交通爱好者能够上传并共享“轨迹”。所谓轨迹，指的是利用卫星地图生成铁道线路的路径文件，如Google Earth的KML/KMZ文件。

我们发现，不少的交通爱好者热衷于对线路的探访考察，同时也会制作和整理这些线路数据，而卫星地图无疑为此提供了方便。而轨迹的创造者们也希望能够分享交流这些轨迹。无论是贯穿华夏大地的大动脉，还是藏匿于山谷荒草间甚至水下的废弃线路，都值得我们标记下来。

因此，@df7c5117 与 @香茶 共同发起了这个开源项目，希望建立一个涵盖中国铁路线的地标数据库，来记录这些钢铁长龙的足迹，用轨迹来丈量每一寸远方。

* 本计划接受诸如国家铁路、地方铁路、厂矿专用线以及废弃或停建线路的轨迹文件。长大干线可以分段记录，欢迎多名贡献者合作贡献。

## 最新轨迹

### 华南
#### 广东省
* [梅隆铁路](https://github.com/Railidea/RouteTrace/wiki/%E5%B9%BF%E4%B8%9C%E7%9C%81#%E6%A2%85%E9%9A%86%E9%93%81%E8%B7%AF)        贡献者：@香茶
* [广铁全图](https://github.com/Railidea/RouteTrace/wiki/%E5%B9%BF%E4%B8%9C%E7%9C%81#%E5%B9%BF%E5%B7%9E%E9%93%81%E8%B7%AF%E9%9B%86%E5%9B%A2%E5%85%A8%E5%9B%BE)        贡献者：@香茶 等
* [乳源森林铁路](#)     贡献者：@香茶【待上传】
-------------------

## 如何使用轨迹？

在Google Earth中，依次单击 **文件-打开**，选取KMZ/KML文件。

KMZ/KML可能是线路的走向，也可能是一个地标（如车站）。

当信息点加载完毕，就可以尽情探索了。你可以右键点击路径获取地形高度分布，对话框下方的“播放游览”甚至可以以俯视视角观测地形变化。

## 如何参与贡献？


如果您会使用Git，您可以使用它来维护此项目，或者只需制作好轨迹并用邮件提供给我们。

### 制作轨迹

你可以在Google Earth的菜单栏上点击 **添加-路径** 或 **添加-地标**，通过在地图上勾勒来创建轨迹，轨迹一般将保存在左侧栏的“位置”中。请右键这些项目，选择 **“将位置另存为…”** 保存为KMZ文件。轨迹的样式可以参阅已有的轨迹文件。

### 上传共享

#### 使用Git……

* 复刻（Fork）本项目到自己的仓库，并克隆（Clone）您自己的分支到本地。
* 将创建好的轨迹放入以所在省份的全称的文件夹中（例如：四川省），建立一个以线路名为名的文件夹，再附上txt格式的线路简介（readme.txt），并执行Git三连：

`git add * `//添加文件

`git commit -m "提交的说明" `//提交文件

`git push origin master `//上传到自己的分支

* 向项目主分支提交Pull Request，耐心等待审核与合并。

#### 或者……
* 将创建好的轨迹放入以所在省份的全称的文件夹中（例如：四川省），建立一个以线路名为名的文件夹，再附上txt格式的线路简介（readme.txt），打包成Zip文件。

* 将文件发送至 `1411121236@qq.com` ，在主题和正文中注明“共享轨迹”并对你所绘制线路进行必要的描述介绍。

* 耐心等待审核与合并。

#### 由于需要人工审核，数据的更新可能较慢。


### 隐私与版权

#### 隐私保护
我们不收集贡献者的个人信息及地理坐标，同时贡献者提供的轨迹文件及其说明中不会含有也不应含有个人的敏感信息。

#### 版权声明
贡献者提供的轨迹文件，一切权利归原始贡献者所有，包括且不限于著作权、署名权等。贡献者与用户应了解以共享名义发布的轨迹文件不以获利为目的。Toocheer仅履行提供免费共享平台的义务。用户可以自由使用共享的数据，包括但不限于以学术研究、收藏等目的，但不能在未经原作者许可的情况下以营利为目的私自交易这些数据。使用者不得抹除原始作者的个人版权信息及原始说明。
本项目遵循CC-BY-NC-SA 4.0（知识共享署名-非商业性使用-相同方式共享 4.0 国际许可协议）进行许可，详情请见 https://creativecommons.org/licenses/by-nc-sa/4.0/

©2018 A LJR Project Under the MIT licence 

![](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)



