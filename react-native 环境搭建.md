# react-native 环境搭建

**大部分看中文网，这里补充一些细节**

+ react 中文网 环境搭建  

  https://reactnative.cn/docs/getting-started.html 

## Node

>  Node 的版本必须⾼于 8.3， 

```javascript
npm config set registry https://registry.npm.taobao.org --global
npm config set disturl https://npm.taobao.org/dist --globa
```



## 安装及搭建python环境

>  Python 的版本必须为 2.x（不⽀持 3.x） 

 https://www.runoob.com/python/python-install.html 

## 安装jdk及搭建java环境

>  JDK 的版本必须是 1.8（⽬前不⽀持 1.9 及更⾼版本） 

+  下载 https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html 
+ 配置环境变量 https://blog.csdn.net/qq_26631651/article/details/82666336 

##  Yarn、React Native 的命令⾏⼯具（react-native-cli） 

arn](http://yarnpkg.com/)是 Facebook 提供的替代 npm 的工具，可以加速 node 模块的下载。React Native 的命令行工具用于执行创建、初始化、更新项目、运行打包服务（packager）等任务。

```javascript
npm install -g yarn react-native-cli
```

安装完 yarn 后同理也要设置镜像源：

```javascript
yarn config set registry https://registry.npm.taobao.org --global
yarn config set disturl https://npm.taobao.org/dist --global
```

安装完 yarn 之后就可以用 yarn 代替 npm 了，例如用`yarn`代替`npm install`命令，用`yarn add 某第三方库名`代替`npm install 某第三方库名`。

## 搭建android 环境

+ 下载工具及sdk等等的网站

   https://www.androiddevtools.cn/ 

> 谷歌访问助手里面有个ant压缩包，可以翻墙

1. 从上面的网址下载 Android Studio
2. 打开翻墙软件
3. 安装 Android Studio
4. 如果出现了Android SDK add-on list d额错误，点击取消无视他
5. 然后去下载各种react-native 需要的东西（中文网上有说明）



