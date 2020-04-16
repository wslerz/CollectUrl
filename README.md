# CollectUtil


## 网页链接

[Markdown: Basics （快速入门）](https://www.appinn.com/markdown/)

[谈谈我的理解-组件化/模块化](https://www.jianshu.com/p/79e4df63f31f)


## 常用的库

### 第三方

[Android智能下拉刷新框架  ：SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)

[EventBus](https://github.com/greenrobot/EventBus)

[强大、可定制、易扩展的 ViewPager 指示器框架 ： MagicIndicator](https://github.com/hackware1993/MagicIndica)

[时间选择器、省市区三级联动  ：Android-PickerView](https://github.com/Bigkoo/Android-PickerView)

[侧滑  ：EasySwipeMenuLayout](https://github.com/anzaizai/EasySwipeMenuLayout)

[RecyclerView Adapter ： BaseRecyclerViewAdapterHelpe](https://github.com/CymChad/BaseRecyclerViewAdapterHelper)

[沉浸式状态栏和沉浸式导航栏管理 ：ImmersionBar](https://github.com/gyf-dev/ImmersionBar)

[Retrofit](https://github.com/square/retrofit)

[AndroidUtilCode](https://github.com/Blankj/AndroidUtilCode)

[Android 屏幕适配方案：AndroidAutoSize](https://github.com/JessYanCoding/AndroidAutoSize)

[glide](https://github.com/bumptech/glide)

[RxJava](https://github.com/ReactiveX/RxJava)


### 原生
~~~
android = [
            "targetSdkVersion"      : 29,
            "compileSdkVersion"     : 29,
            "buildToolsVersion"     : '29.0.2',
            "minSdkVersion"         : 22,
            "versionCode"           : 1,
            "versionName"           : '1.0',
            "javaVersion"           : '1.8',
            "applicationId"         : 'com.**.**',
    ]

    androidVersion = [
            "supportLibraryVersion": "28.0.0",
            "appcompat"            : "1.1.0",
            "constraint_layout"    : "1.1.3",
            "kotlin_version"       : '1.3.61',
    ]
~~~
~~~
  supportDependencies = [
            "design"                 : "com.android.support:design:${androidVersion.supportLibraryVersion}",
            "appcompat"              : "androidx.appcompat:appcompat:${androidVersion.appcompat}",
            "core"                   : "androidx.core:core:${androidVersion.appcompat}",
            "material"               : "com.google.android.material:material:${androidVersion.appcompat}",
            "recyclerView"           : "androidx.recyclerview:recyclerview:${androidVersion.appcompat}",
            "cardview_v7"            : "com.android.support:cardview-v7:${androidVersion.supportLibraryVersion}",
            "palette"                : "com.android.support:palette-v7:${androidVersion.supportLibraryVersion}",
            "constraint_layout"      : 'androidx.constraintlayout:constraintlayout:1.1.3',
            "multidex"               : "com.android.support:multidex:1.0.0",
            "kotlin-stdlib-jdk7"     : "org.jetbrains.kotlin:kotlin-stdlib-jdk7:${androidVersion.kotlin_version}",
            "kotlinx-coroutines-core": "com.android.support:multidex:1.3.3",
            "corektx"                : 'androidx.core:core-ktx:1.2.0',

            "navigation-fragment"    : 'androidx.navigation:navigation-fragment:2.2.1',
            "navigation-ui"          : 'androidx.navigation:navigation-ui:2.2.1',

            "navigation-fragment-ktx": 'androidx.navigation:navigation-fragment-ktx:2.2.1',
            "navigation-ui-ktx"      : 'androidx.navigation:navigation-ui-ktx:2.2.1',

            // Koin for Android
            "koin-android"           : "org.koin:koin-android:2.0.1",
            // or Koin for Lifecycle scoping
            "koin-androidx-scope"    : "org.koin:koin-androidx-scope:2.0.1",
            // or Koin for Android Architecture ViewModel
            "koin-androidx-viewmodel": "org.koin:koin-androidx-viewmodel:2.0.1",

            "room"                   : "android.arch.persistence.room:runtime:1.1.1"
            "lifecycleextensions"  : 'androidx.lifecycle:lifecycle-extensions:2.2.0',
            "lifecycleviewmodelktx": 'androidx.lifecycle:lifecycle-viewmodel-ktx:2.2.0'
  ]
~~~















