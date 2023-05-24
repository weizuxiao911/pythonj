# 1
## Node.js简介
## 什么是Node.js
Node.js发布于2009年5月，由Ryan Dahl开发，是一个基于Chrome V8引擎的JavaScript运行环境，使用了一个事件驱动、非阻塞式I/O模型， 让JavaScript 运行在服务端的开发平台，它让JavaScript成为与PHP、Python、Perl、Ruby等服务端语言平起平坐的脚本语言。\
``
官网：https://nodejs.org/en
``{{'https://nodejs.org/en'}}
# 2
## Node.js运行环境
Node作为一个新兴的前端框架，后台语言，有很多吸引人的地方：RESTful API，单线程。
# 3
#d Node.js功能
Node使用Module模块去划分不同的功能，以简化应用的开发。Modules模块有点像C++语言中的类库。每一个Node的类库都包含了十分丰富的各类函数，比如http模块就包含了和http功能相关的很多函数，可以帮助开发者很容易地对比如http,tcp/udp等进行操作，还可以很容易的创建http和tcp/udp的服务器。
# 4
#d Node.js安装
### Linux下安装Node
下面介绍下Node的安装，首先在nodejs的网站上根据操作系统下载相关的安装包，对于Ubuntu(linux)下的安装，可以如下进行：
```
sudo apt-get update
```{{exec}}
```
sudo apt-get install node
```{{copy ls}}
或者
```
sudo apt update
```{{exec}}
```
sudo apt install node
```{{exec}}
### Windows下安装Node
官网现已提供安装包（最新的长期支持版本: 10.16.0）、编译器和相应的API 文档
``
https://nodejs.org/en
``{{'https://nodejs.org/en'}}
# 5
#d 区别LTS版本和Current版本的不同
Node.js 中 LTS 和 Current 的区别和如何选择合适的版本，在实际开发中，并不需要及时更新到最新版本，我们完全可以按照项目技术栈依赖的最低 Node.js 版本决定是否升级，如果条件允许，还是建议至少把大版本升级到最新的 LTS 版本。
#### 查看自己安装的版本号
```
node -v
```{{exec 'node -v'}}