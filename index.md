---
layout: cv
title: 程刚中文简历
---

# 程 刚（Gang Cheng）

Red Hat 认证架构师（RHCA）｜基础架构工程师 / DevOps 工程师 / 平台工程师 / Developer Experience 工程师  

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat 简介</a> |
<a href="https://www.linkedin.com/in/gang-cheng-7170a521/">LinkedIn</a>
</div>

## 概要（Summary）

程刚是一位自我驱动、持续成长的工程师，坚信持续学习和快速掌握新技术是 IT 工程师的核心能力。他长期主动构建现代基础架构与平台工程能力，通过持续的项目实践、认证、会议、课程以及与行业同行学习，不断强化自身技术广度与深度。

2024 年，他荣获 Red Hat Certified Professional of the Year，这是 Red Hat 对个人技术能力的全球性认可，他也是当年挪威唯一获奖者。

他在职业生涯中担任过系统管理员、基础设施工程师、DevOps 工程师、开发者体验（DevEx）工程师、平台工程师等角色。凭借十年以上在不同规模与行业的基础设施环境中的经验，他成功为客户交付解决方案，创造价值，并与开发团队、研究团队保持紧密合作，善于跨团队协作与推动落地。

## 工作经历（Employment）

`2025–至今`  
**Senior Platform Engineer — Appear TV, Oslo**

- 构建并维护基于裸金属的 **Kubernetes 集群**，通过 Rancher 进行集中管理，运行在 Flatcar 不可变操作系统之上，支持内部 R&D 团队（Rust、C++、Python、Yocto、TypeScript）。
- 设计端到端 **GitOps 工作流**：使用 GitLab CI + Argo CD + Kustomize，实现应用自动化部署、多环境配置管理和可审计变更。
- 使用 **Terraform** 管理基础设施，通过 GitLab pipeline 触发 `terraform apply`，实现版本化、可回滚的基础设施即代码（IaC）。
- 集成并维护 **TrueNAS NFS**、Harbor 镜像仓库、VMware、ExternalDNS、Bind9、MetalLB、Replicator、GitLab Runners 等平台组件。
- 搭建 **Prometheus + Grafana** 监控体系，为集群、应用和 CI/CD 提供指标、仪表盘和告警。
- 与 CISO 紧密合作，从 RBAC、网络策略、镜像安全、流水线权限等方面提升平台的安全性与合规性。

**项目：在 Azure 部署 Appear Hub（客户固件/文档/License 下载平台）**

- 设计并实现面向客户的交付平台，用于固件、产品文档及 License 文件的安全分发。  
- 使用 **Azure Container Apps** 承载后端服务，实现弹性伸缩与容器化部署。  
- 使用 **Azure Front Door** 实现全球路由、SSL 终止、WAF 防护及访问控制。  
- 利用 **Azure Blob Storage** 存储固件、文档和许可证，支持高并发访问。  
- 基于 **GitLab CI/CD** 实现自动构建、推送镜像和部署，集成基础设施配置。  
- 通过 **Azure Monitor** 收集日志和指标，构建运行可观测性。  

`2022–2025`  
**Senior Infrastructure Engineer — Sopra Steria, Oslo**

- 作为 DevOps / 基础设施工程师，为大型客户设计与实施现代基础设施平台。  
- 独立设计并部署高可用 **Kubernetes + GitHub Actions Runner Controller (ARC)** 平台，将自托管 Runner 从 VM 迁移到容器化 Runner，支持动态创建与自动回收。
- 在 Kubernetes 上部署 **MinIO S3 后端** 作为 Terraform 状态存储，解决本地状态文件缺乏协作与版本控制的问题，在不依赖公有云的前提下提供集中化、可审计的 state backend。
- 使用 **Argo CD + Helm + Kustomize** 构建 GitOps 部署流，允许开发团队通过 Git 分支选择部署环境，实现自助化、自动化发布。
- 在 Kubernetes 上部署 **Prometheus + Grafana**，统一监控容器与 VM，定义告警规则和基础设施健康仪表盘。
- 深入排查和优化 CI/CD 流水线，改善 pipeline 稳定性与执行效率，减少开发团队在流水线问题上的时间消耗。
- 对大规模 **RHEL7→RHEL8** 升级进行规划与 Ansible 自动化，实现合规升级与可控停机。
- 在 OpenShift 上部署 **Ansible Automation Platform (AAP)**，集中管理 Playbook、Inventory 与机密信息，构建自动化运维平台。
- 使用 Ansible 和 Red Hat Satellite 自动化补丁与 VM 部署，标准化基础设施，降低人为错误和维护成本。
- 独立部署关键业务应用到生产环境，负责安装、配置、故障排查与合规性验证。
- 部署并维护 **Splunk** 日志平台，集中收集基础设施日志和性能数据，构建可观测性，缩短故障定位时间。

`2012–2022`  
**System Engineer — University of Oslo, Oslo**

- 管理本地数据中心，为分子医学研究中心（NCMM）的科研人员提供可靠的科学计算基础设施。  
- 采购、安装、配置和维护 Dell、HP、Red Hat 等企业级服务器，管理科学计算、虚拟化（VMware/KVM）、数据库、Web 服务以及 RAID / Samba / NFS 等存储系统。
- 使用 **SCCM** 和 PXE 部署 Windows 客户端，负责软件分发、补丁更新和安全策略实施。
- 管理实验室内网和公共网络，使用 Cisco 交换机和路由器，实现 NAT、网络隔离、端口管理和日常故障排查。
- 安装和维护复杂科研软件，处理依赖不清晰、版本冲突等问题，协助研究人员优化计算环境。
- 使用 Nagios、Zabbix 等工具进行日常监控和告警，处理访问控制、存储管理和安全评估。
- 为使用 HPC 集群的科研人员提供支持与培训，协助作业提交、并行计算优化和数据密集型工作流。

## 证书（Certificates）

- Red Hat Certified Professional of the Year 2024  
- Red Hat Certified Architect  
- Red Hat Certified Specialist in Containers  
- Red Hat Certified OpenShift Administrator  
- Red Hat Certified Specialist in Managing Automation with Ansible Automation Platform  
- Red Hat Certified Specialist in Deployment and Systems Management  
- Red Hat Certified Engineer  
- Red Hat Certified System Administrator  
- Microsoft Certified: Azure Fundamentals  
- Red Hat Certified Specialist in Containers and Kubernetes  

## 会议与活动（Events & Conference）

- Cloud Native Day Oslo 2025  
- Red Hat Summit & Ansible Fest  

## 文章（Articles）

- 《Let’s talk about troubleshooting》  
- 《Challenges, tips, and rewards: working as a consultant in Norway》  
- 《Cloud Native Day Oslo — From DevOps to DevEx》  

## 课程（Courses）

- Google Cloud Fundamentals  
- NVIDIA：AI Infrastructure and Operations  
- GenAI for DevOps Practitioners  
- Linux Foundation：Introduction to DevOps and Site Reliability Engineering  
- Linux Foundation：Introduction to Cloud Infrastructure Technologies  
- Microsoft Azure Fundamentals  
- Intrusion Detection and Firewalls  
- Enterprise Networking: Practices and Technologies  
- Research Methods and Data Analysis  
- Mastering Ansible  
- Introduction to programming with scientific applications  
- Red Hat: Fundamentals of Containers, Kubernetes, and Red Hat OpenShift  

## 工作坊（Workshops）

- Azure Red Hat OpenShift AI  
- AWS RAG and Fine-tuned AI  
- Using the High Performance Computing cluster for Educloud Research users  
- Cilium Hands-On Workshop & Deep Dive Oslo  
- Version Control with Git  
- Cryptography and SSH remote logins  
- Python for Scientific Computing  
- Virtualized research architecture using OpenStack  
- AI at UiO  

## 技术栈（Experienced Tech Stacks）

- Kubernetes、Docker、Podman  
- GitHub Actions、GitHub Actions Runner Controller (ARC)  
- Red Hat Linux、Red Hat Satellite、Red Hat OpenShift、Red Hat Ansible  
- Atlassian Bitbucket、Confluence、Jira  
- Grafana、Prometheus、Splunk  
- Dell PowerEdge、Cisco 交换设备  
- Windows Server、SCCM  
- Samba、NFS、FirewallD、Active Directory  

## 其他接触技能（Exposure Skills）

- AWS  
- Microsoft Azure  
- OpenStack  
- Vagrant  

## 教育背景（Education）

`2010–2012`  
**University of Oslo — Master in Network and System Administration**

## 兴趣（Hobbies）

博客写作、滑雪、徒步  

## 语言（Languages）

- 英语：专业工作熟练度  
- 挪威语：专业工作熟练度  
- 中文：母语  
