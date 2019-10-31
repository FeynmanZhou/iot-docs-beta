---
title: "产品简介"
keywords: 'kubernetes, docker, helm, jenkins, istio, prometheus'
description: ''
---

[KubeSphere](https://kubesphere.io) 是在目前主流容器调度平台 [Kubernetes](https://kubernetes.io) 之上构建的企业级分布式多租户容器平台，提供简单易用的操作界面以及向导式操作方式，在降低用户使用容器调度平台学习成本的同时，极大减轻开发、测试、运维的日常工作的复杂度，旨在解决 Kubernetes 本身存在的存储、网络、安全和易用性等痛点。除此之外，平台已经整合并优化了多个适用于容器场景的功能模块，以完整的解决方案帮助企业轻松应对敏捷开发与自动化运维、微服务治理、多租户管理、工作负载和集群管理、服务与网络管理、应用编排与管理、镜像仓库管理和存储管理等业务场景。

相比较易捷版，KubeSphere 高级版提供企业级容器应用管理服务，支持更强大的功能和灵活的配置，满足企业复杂的业务需求。比如支持 Master 和 etcd 节点高可用、可视化 CI/CD 流水线、多维度监控告警日志、多租户管理、LDAP 集成、新增支持 HPA (水平自动伸缩) 、容器健康检查以及 Secrets、ConfigMaps 的配置管理等功能，新增微服务治理、灰度发布、s2i、代码质量检查等，后续还将提供和支持多集群管理、大数据、人工智能等更为复杂的业务场景。

KubeSphere 从项目初始阶段就采用开源的方法来进行项目的良性发展，项目相关的源代码和文档都在 [GitHub](https://github.com/kubesphere) 可见。KubeSphere 支持部署和运行在包括**公有云、私有云、VM、BM 和 Kubernetes 等任何基础设施之上**，并且支持**在线安装与离线安装**，目前已在 **阿里云、腾讯云、华为云、青云、AWS、Kubernetes** 上进行过[部署测试](https://github.com/kubesphere/ks-installer/issues/23)。 

## 功能架构

KubeSphere 2.0.2 提供了在生产环境集群部署的全栈化容器部署与管理平台，它的核心功能可以概括在以下的功能架构图中，了解 2.0.2 的具体功能说明，可以在 [产品功能](../features) 进行查看。

![功能架构图](/2.0.0-architecture.svg)

## 产品规划

**Community Edition** （ [社区版](https://kubesphere.qingcloud.com/#category) ）=> **Express Edition** （ [易捷版](https://kubesphere.qingcloud.com/#category) ）=> **Advanced Edition** （ [高级版](https://kubesphere.qingcloud.com/#category) ）

> 说明：KubeSphere **所有版本都 100% 开源免费**，已大规模服务于社区用户，广泛地应用在**以 Docker 和 Kubernetes 为中心**的开发测试及生产环境，大量服务平稳地运行在 KubeSphere 之上。

![](https://pek3b.qingstor.com/kubesphere-docs/png/20190910144241.png)
