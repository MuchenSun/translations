# Docker Document(1): Configure Networking

## Overview
One of the reasons Docker containers and services are so powerful is that you can connect them together, or connect them to non-Docker workloads. Docker containers and services do not even need to be aware that they deployed on Docker, or whether their peers are also Docker workloads or not. Whether your Docker hosts run Linux, Windows, or a mix of the two, you can use Docker to manage them in a platform-agnostic way.

Docker的容器服务之所以这么强大的原因之一就是你可以将它们连接在一起，或者将它们与非Docker环境相连接。Docker的容器甚至都不必了解到它们是否被部署在Docker环境里或者它们的对面是否是Docker环境。无论你的Docker主机运行的是Linux、Windows或者二者都有，你都可以通过一种屏蔽平台的方式来管理它们。

This topic defines some basic Docker networking concepts and prepares you to design and deploy your applications to take full advantage of these capabilities.

这一章将会一些有关Docker网络的概念，并且帮助你准备如何使用Docker的这些功能来更好地部署你的应用。

Most of this content applies to all Docker installations. However, a few advanced features are only available to Docker EE customers.

这一章大部分的内容适用于所有的Docker版本。但是，有一小部分的高级功能只对企业版用户开放。
