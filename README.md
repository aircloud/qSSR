该项目还未发布

# qSSR

qSSR 是一个快速的 react 服务端渲染库，主要设计目的是给现有的非服务端渲染的网站通过最小的成本接入服务端渲染的能力。

其他设计要素：

* 基于同构的项目，拥有服务端渲染在出错的情况下平稳降级到客户端渲染的能力。
* 在使用本库提供的服务端渲染能力前，可以基于约定和构建工具快速将非服务端渲染的项目整理代码至同构版本，方可接入服务端渲染。
* 基于node提供的沙盒机制完成关键步骤运行，拥有支持高并发的能力。


设计目标：

* 平稳降级切换到客户端渲染的能力
* 支持react-router，渲染子路由页面
* 最小化当前改动


