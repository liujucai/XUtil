# XUtil


一个方便实用的Android工具类库

------------------------------------


## 特点

* 收录了Android开发过程中常用的工具类，并进行简单的分类，易于查询使用。

* 工具类被分为xutil-core和xutil-sub两个，防止xutil工具类过于臃肿。

* 收录了常用的[代码混淆配置](./xutil-core/base-proguard-rules.pro)。

* 收录了常用的Android Gradle脚本：[bintrayUpload.gradle](./bintrayUpload.gradle)、[JitPackUpload.gradle](./JitPackUpload.gradle)、[localRepositoryUpload.gradle](./localRepositoryUpload.gradle)、[versions.gradle](./versions.gradle)。


## 如何使用

### 添加Gradle依赖

1.先在项目根目录的 build.gradle 的 repositories 添加:
```
allprojects {
    repositories {
        ...
        maven { url "https://jitpack.io" }
    }
}
```

2.然后在dependencies添加:

以下是版本说明，选择一个即可。

* androidx版本：2.0.0及以上


```
//基础功能的工具类
implementation 'com.github.liujucai.XUtil:xutil-core:2.0.0'
//附加功能的工具类
implementation 'com.github.liujucai.XUtil:xutil-sub:2.0.0'
```

* support版本：1.1.8及以下

```
//基础功能的工具类
implementation 'com.github.liujucai.XUtil:xutil-core:1.1.8'
//附加功能的工具类
implementation 'com.github.liujucai.XUtil:xutil-sub:1.1.8'
```
------------------------------------

## 文档

### 基础工具类内容(xutil-core)

[点击查看](./xutil-core/README.md)

### 附加工具类内容(xutil-sub)

[点击查看](./xutil-sub/README.md)


