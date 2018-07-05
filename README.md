# reverse
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://github.com/IceWee/reverse/blob/master/LICENSE)
[![OpenTracing Badge](https://img.shields.io/badge/OpenTracing-enabled-blue.svg)](http://opentracing.io)

## 简介
>Java model及Hibernate hbm逆向工程工具，用来简化手工编写Model及Hbm文件工作，借助codehaus的hibernate3-maven-plugin插件实现。
该项目属于私人学习项目，如果发现有任何不能接受的行为，请发邮件至[icewee@126.com](mailto:icewee@126.com?subject=kaoqin Feedback)。

## 下载
>项目源码需要使用[GIT克隆](https://github.com/IceWee/reverse.git)到你的本地。

## 构建

#### 1.克隆项目到本地
```shell
git clone https://github.com/IceWee/reverse.git
```
#### 2.修改配置文件
```shell
根据文件内注释依次修改hibernate.cfg.xml、hibernate.reveng.xml和pom.xml三个文件
```
#### 3.MAVEN运行
```shell
mvn hibernate3:hbm2hbmxml hibernate3:hbm2java
```

## 版权
>MIT © 2017 `IceWee` `Bing` `长公子冰`
