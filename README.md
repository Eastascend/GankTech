# GankTech
# 简洁易用的gank客户端
**介绍**
---------
一款基于GankIo开发的练习项目。项目采用  MVP+Dagger2+Retrofit + RxJava开发。

**应用截图**
-----------

![image](https://github.com/Eastascend/GankTech/blob/master/ScreenShoots/main.jpg)
![image](https://github.com/Eastascend/GankTech/blob/master/ScreenShoots/fuli.jpg)
![image](https://github.com/Eastascend/GankTech/blob/master/ScreenShoots/mine.jpg)
![image](https://github.com/Eastascend/GankTech/blob/master/ScreenShoots/night.jpg)



**特性**
-----------
* 基本遵循MD风格
* MVP+dagger2架构模式的项目应用
* Retrofit+RxJava配合使用
* Rxbus组件间通讯
* Greendao实现本地收藏功能
* 日夜模式平滑切换
* Flexbox流式布局的使用
* ViewPager+Fragment栏目动态切换
* 共享元素和扩散效果

**使用到的开源库**
-----------

* 网络请求：Retrofit2
* RxJava2
* 依赖注入：Dagger2
* 数据库：Greendao3
* 图片加载：Glide
* Butterknife
* 上拉加载下拉刷新：[TwinklingRefreshLayout](https://github.com/lcodecorex/TwinklingRefreshLayout) 
* 流式布局：Flexbox-layout 
* 底部导航：[PagerBottomTabStrip](https://github.com/tyzlmjj/PagerBottomTabStrip)

**参考**
-----------
* 架构部分参考项目 [mvp-architecture](https://github.com/MindorksOpenSource/android-mvp-architecture) 以及文章
[Android MVP 架构必要知识：第二部分](https://juejin.im/entry/58a5992961ff4b006c4455e3?utm_source=gold-miner&utm_medium=readme&utm_campaign=github)
如果不了解dagger2，理解起来有些困难。但整体架构思路非常清晰，model层次划分非常细致。

* 日夜切换参考了[ZhihuDaily](https://github.com/hefuyicoder/ZhihuDaily) 项目以及 [知乎和简书的夜间模式实现套路](http://www.jianshu.com/p/3b55e84742e5)这篇文章。效果很好



/**
 * Copyright (C) 2017 KevinWong Inc. All rights reserved.
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *     http://www.apache.org/licenses/LICENSE-2.0
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */
