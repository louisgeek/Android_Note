# Android_Note





[Java_Note](https://github.com/louisgeek/Java_Note)

[Kotlin_Note](https://github.com/louisgeek/Kotlin_Note)

- 设计模式

  Android进阶之大话设计模式 http://mobile.51cto.com/android-419145.htm

- Android Studio

  跳过sdk检查更新：在Android Studio\bin\idea.properties中添加disable.android.first.run=true

  最强 Android Studio 使用技巧和快捷键 http://www.open-open.com/lib/view/open1458715872710.html

- Gradle

  版本问题：如果 lib 库有引入高版本的 lib ，那项目里该 lib 会全部替换成新的，即便代码里显示引入低版本也不生效，所以推荐 lib 尽量引入低版本的正式版 这样代码中依赖高、低版本都可以，比较灵活

  e.g. `implementation 'androidx.constraintlayout:constraintlayout:1.1.3'`

- Activity 

  - 主线程 

    ComponentActivity.java 中 post 主线程方法 `new Handler(Looper.getMainLooper()).post(new Runnable()(){});`

- Res

Android selector 选择器 从上往下匹配 匹配到就返回了

- UI

  - Button

     能够让 Button 样式变小,适应 wrap_content

    `//去掉默认的 默认主题中有 android:minHeight 设定 改成  
    android:minHeight="0dp"`

  - ListView

    ArrayIndexOutOfBoundsException问题：http://blog.csdn.net/yak262/article/details/8825409

  - RecyclerView 

    - RecyclerView 封装

      封装那些事-RecyclerView封装实践 http://www.jianshu.com/p/a6f158d1a9c9

      真实项目运用-RecyclerView封装 http://www.jianshu.com/p/2f2996ef2c75

  - 自定义view

  - ~~百分比布局~~ 改用约束布局

  Android UI性能优化详解 http://mrpeak.cn/android/2016/01/11/android-performance-ui

- Material Design

  material配色 https://www.materialpalette.com/

- Demo

  1、google 官方demo https://developer.android.com/samples/index.html

  1、google 架构组件demo https://github.com/android/architecture-components-samples

  3、最值得学习的5个app项目http://www.jianshu.com/p/8180cc105f01

  4、泡在网上的日子里的完整项目   http://www.jcodecraeer.com/plus/list.php?tid=31&codecategory=22000

  http://mobdevgroup.com/platform/android/project

  5、第三方热门开源库
  6、Android系统源码

  心得：http://weaponzhi.online/2017/07/05/%E5%8F%AF%E8%83%BD%E8%BF%99%E5%B0%B1%E6%98%AF%E7%94%9F%E6%B4%BB%E7%9A%84%E4%B8%8D%E5%AE%8C%E7%BE%8E/

  http://weaponzhi.online/2017/06/03/%E6%90%AC%E5%AE%B6%E7%9A%84%E4%BA%8B%E5%84%BF%E5%92%8C%E8%80%81%E7%88%B8%E5%BC%80%E9%A1%BA%E9%A3%8E%E8%BD%A6%E7%9A%84%E9%82%A3%E4%BA%9B%E4%BA%8B%E5%84%BF%E3%80%82/

  http://weaponzhi.online/2017/05/25/%E6%9D%A5%E5%8D%97%E4%BA%AC%E4%B8%80%E5%B9%B4%EF%BC%8C%E6%88%91%E5%B0%B1%E8%A6%81%E6%90%AC%E5%AE%B6%E4%BA%86/

  http://weaponzhi.online/2017/04/27/%E6%88%91%E4%B8%8D%E6%84%BF%E6%84%8F%E5%8E%BB%E8%BE%93/

  http://weaponzhi.online/2017/04/02/%E6%89%BE%E5%B7%A5%E4%BD%9C%E7%AC%AC%E4%B8%89%E5%8D%81%E4%B8%89%E5%A4%A9%EF%BC%8C%E6%88%91%E6%8B%BF%E5%88%B0%E4%BA%86Offer/


  如何看懂源代码--(分析源代码方法)

  http://www.cnblogs.com/ToDoToTry/archive/2009/06/21/1507760.html



------

其他附加知识

- RESTful API 

  RESTful API 设计指南 http://www.androidchina.net/3749.html

- H5

  H5 调用摄像头 

  https://webrtc.github.io/samples/src/content/devices/input-output/

  https://www.jb51.net/html5/722394.html

- 正则表达式

  https://deerchao.net/tutorials/regex/regex.htm
  http://www.runoob.com/regexp/regexp-syntax.html