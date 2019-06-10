## Flutter学习资源汇总持续更新中......

- [Flutter官方网站](https://flutter.dev/)
- [Flutter中文网](https://flutterchina.club/)
- wendux的[Flutter实战](https://book.flutterchina.club/)
- Flutter官方example[flutter_gallery](https://github.com/flutter/flutter/tree/master/examples/flutter_gallery)
- [阿里巴巴咸鱼团队系列文章](https://www.yuque.com/xytech/flutter)
- [阿里巴巴flutter-go](https://github.com/alibaba/flutter-go)，flutter 开发者帮助 APP，包含 flutter 常用 140+ 组件的demo 演示与中文文档
- [awesome-flutter](https://github.com/Solido/awesome-flutter)包含居多优秀的Flutter库，工具，教程，文章等
- [玩Android跨平台项目](https://www.wanandroid.com/project/list/1?cid=402)
- 非常有用的[Json转Model插件](https://github.com/neverwoodsS/idea_dart_json_format)
- [Flutter-Notebook](https://github.com/OpenFlutter/Flutter-Notebook),提供了很多优秀样例和Demo
- [Flutter-plugins](https://github.com/flutter/plugins),flutter官方插件，提供了众多优秀插件
- 掘金作者[真丶深红骑士系列文章](https://juejin.im/user/597247ad5188255aed1fbba6/posts)

## 环境搭建

- 根据[Flutter中文网](https://flutterchina.club/get-started/install)搭建开发环境，使用Android Studio安装Flutter插件，点击pubspec.yaml的package get，然后运行

## App目录结构
>- |--lib
>    - |-- main (入口类)
>    - |-- loading (启动页)
>    - |-- splash_screen (引导页)
>    - |-- util (工具类)
>    - |-- base (基类，封装基类BaseWidget和BaseWidgetState)
>    - |-- http (网络请求相关类)
>    - |-- common (常用类)
>    - |-- event (事件类)
>    - |-- model (实体类)
>    - |-- ui (界面相关)
>    - |-- util (工具类)

## 功能介绍

#### V1.5版本

- 常用网站增加数据库[sqflite](https://pub.flutter-io.cn/packages/sqflite)功能
- 修复注册登录按钮颜色与主题色不一致的问题

#### V1.4版本

- 增加切换主题
- 封装基类BaseWidget和BaseWidgetState
- 显示隐藏AppBar
- 增加状态页切换（数据加载中，数据加载失败，空数据）

#### V1.3版本

- 新增搜索和搜索结果列表
- 新增页面正在加载...
- 整个界面UI风格修改

#### V1.2版本

- 新增福利，妹子图，使用[photo_view](https://pub.flutter-io.cn/packages/photo_view)，你懂得
- 新增分享[share](https://pub.flutter-io.cn/packages/share)
- 新增常用网站
- 新增关于作者，退出登录

#### V1.1版本

- 新增引导页[flutter-intro-slider](https://github.com/duytq94/flutter-intro-slider)
- 列表页悬浮FloatingActionButton,点击迅速回到顶部
- 新增注册、登录、我的收藏，增加侧滑抽屉，详见截图

#### V1.0版本
- 项目首页、知识体系、公众号、导航、项目、各个页面，和详情页面
- 主要的UI包括首页轮播图和列表，体系流式布局，公众号导航TabBar,以及下拉刷新和加载更多
- 轮播图使用的是开源库[flutter_swiper](https://github.com/best-flutter/flutter_swiper)
- 网络请求使用的是开源库[dio](https://github.com/flutterchina/dio)

## 我的主页
 - [掘金](https://juejin.im/user/5b319afee51d455e2c32fb5b/posts)
 - [CSDN](https://blog.csdn.net/zw2008224044)

##  感谢

1. 特别感谢github开源作者[shijiacheng](https://github.com/shijiacheng/wanandroid_flutter)
2. 感谢鸿洋大神及[玩Android官网](http://www.wanandroid.com/)提供的[开放API](http://www.wanandroid.com/blog/show/2)
3. 感谢[干货集中营 API](http://gank.io/api)

## 使用开源库

- [shared_preferences](https://pub.dartlang.org/packages/shared_preferences)
- [fluttertoast](https://pub.dartlang.org/packages/fluttertoast)
- [share](https://pub.flutter-io.cn/packages/share)
- [flutter_swiper](https://pub.flutter-io.cn/packages/flutter_swiper)
- [cupertino_icons](https://pub.flutter-io.cn/packages/cupertino_icons)
- [flutter_webview_plugin](https://pub.flutter-io.cn/packages/flutter_webview_plugin)
- [dio](https://pub.flutter-io.cn/packages/dio)
- [flutter-intro-slider](https://github.com/duytq94/flutter-intro-slider)
- [photo_view](https://pub.flutter-io.cn/packages/photo_view)
- [sqflite](https://pub.flutter-io.cn/packages/sqflite)
- [path_provider ](https://pub.flutter-io.cn/packages/path_provider#-installing-tab-)
