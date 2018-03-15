![Weex](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1521117262556&di=4175ece9c0542dfc36ee1d2c9e9b07f1&imgtype=0&src=http%3A%2F%2Fimg.mukewang.com%2F5a0fa3d20001a6c213000716.png)


> 众所周知传统的原生App开发发布成本高，需要通过AppStore审核，导致更新缓慢，一个App同时需要维持多个版本、多个系统（ios和Android），而且必须做兼容，大大提升了开发难度和发布周期。大多数开发心里估计都这样想过：如果能写一份代码同时运行在不同系统上就好了。别急，有Weex。


## Weex是什么？
官网上是这么介绍的：
> Weex 是一个使用 Web 开发体验来开发高性能原生应用的框架。

Weex 致力于使开发者能基于当代先进的 Web 开发技术，使用同一套代码来构建 Android、iOS 和 Web 应用。具体来讲，在集成了WeexSDK之后，你可以使用JavaScript和现代流行的前端框架来开发移动应用。

想要清楚Weex是什么，就必须了解[App常用的开发模式](http://naotu.baidu.com/file/6af15fcbb72f89926043779811b1ea44?token=df0378691ecdcef2)

简单来说，Weex就是一个可以使用Web语法编写移动App的框架，并且编写出来的App是横跨Web、Android和ios三个平台的，就像其官网上所说的：「Write Once, Run Everywhere」。
## 为什么是Weex？
自打16年阿里手淘团队开源Weex以来，Weex就免不了和FaceBook开源的React-Native一决高下的命运。React-Native宣称「Learn Once, Write Anywhere」，而 Weex 宣称「Write Once, Run Everywhere」。虽然两个框架效果相似，但是在我看来，两者还是有很多不同的。

* Weex支持三端（Web、Android、ios）而RN更纯粹的支持移动端（Android和ios）
* Weex的目标是实现代码共用，三端使用一套代码，而RN更注重独立性，其代码需要针对ios和Android平台编写，代码无法完全共用
* Weex使用开源的Vue.js，使得其对于前端人员来说，可以直接上手使用，而RN使用React模板，采用JSX语法，学习曲线较Weex陡峭许多
* Weex给我的感觉更倾向于在已有的项目中嵌入Weex页面，所以官网在介绍完Weex是什么后，就直奔 集成Weex到已有应用 上去了，而RN则更倾向于开发整个App


![集成weex到已有应用](https://pic4.zhimg.com/80/v2-229835210cf8cd8606239e237599cb6f_hd.jpg)
## 我与Weex的爱恨情仇
>这是一个有故事的文章，来自一个初学Weex的小菜鸡

![闭嘴，别瞎说，我们两个很相爱](https://pic1.zhimg.com/80/v2-97a5d4c66677086ed7881f61d5ff16ff_hd.jpg)

> weex是阿里巴巴开发团队在RN的成功案例上，重新设计出的一套开发模式，站在了巨人肩膀上并有淘宝团队项目做养料，广受关注，2016年4月正式开源，并在v2.0版本官方支持Vue.js，与RN分庭抗礼。

虽然Weex背景深厚，但架不住开源时间短，社区活跃程度低，导致到处都是坑，并且这些坑往往踩了就很难出来。

![催人泪下的孙子时光](https://pic4.zhimg.com/80/v2-2d446d2d04ee8e5eb4b5d6ddb100ae28_hd.jpg)
