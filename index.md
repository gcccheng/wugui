---
layout: cv
title: 程刚中文简历
---

# 程 刚（Gang Cheng）

Red Hat 认证架构师（RHCA）｜Red Hat 2024唯一年度人物(RHCP)｜基础架构工程师 / DevOps 工程师 / 平台工程师 / Developer Experience 工程师  

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat 简介</a> |
<a href="https://www.linkedin.com/in/gang-cheng-7170a521/">LinkedIn</a>
</div>

## 概要（Summary）

程刚是一位深耕基础架构、云原生与 DevOps 领域的资深工程师，拥有十年以上欧洲一线企业与科研机构的实战经验，曾在媒体科技、金融技术服务、大型政府 IT 与高性能科研计算环境中承担核心平台建设工作。他在 Kubernetes 平台、DevOps 体系化建设、基础设施自动化、可观测性和云平台架构方面具有扎实的工程能力与丰富的落地经验。

2024 年，程刚荣获 **Red Hat Certified Professional of the Year** ——  
这是 Red Hat 面向全球用户授予的最高级别技术奖项，  
每年在全球仅选出一位获奖者。  

他不仅是 **全球年度唯一获奖者**，  
更是 **该奖项历史上第一位获奖的来自中国的工程师**。  

这一荣誉代表了业界对他在 Red Hat、容器平台、自动化、OpenShift、Ansible 以及企业级基础架构设计与实施方面的高度认可，也表明他的技术实践能力与思考方式达到了国际顶级水准。

除深厚的技术背景外，程刚在多个岗位中承担平台核心负责人角色，具备带领小型团队推进复杂基础设施项目落地的经验，能够独立完成架构设计、标准制定、项目拆解、跨团队协作以及工程落地。他重视工程质量、可维护性与可扩展性，擅长以工程方式解决复杂问题，并推动系统性、长期价值的建设。

作为极具自驱力的工程师，他持续投入学习并主动吸收新技术，具备从 0 到 1 搭建平台体系的能力，同时也能在现有体系中发现问题、推动优化，帮助组织构建更稳定、更安全、更高效的基础设施能力。


## 工作经历（Employment）

`2025–至今`  
### **Senior Platform Engineer（平台技术负责人） — Appear TV（挪威·全球领先的视频编解码与分发技术提供商）**

**公司简介**  
Appear TV 是欧洲领先的视频传输、编解码和媒体分发技术公司，北欧上市企业，客户涵盖全球一线广播机构、通信运营商与大型媒体集团。公司产品广泛应用于奥运会、世界杯等高并发、高稳定性场景，对底层基础设施的可靠性要求极高。

**岗位定位**  
作为平台技术负责人，负责公司底层基础设施架构规划、云原生平台建设与 DevOps 体系升级，同时带领团队（含内部协作性质），支撑数百名名研发工程师的高性能研发体系。

**核心工作与成果**

- **从 0 到 1 搭建裸金属 Kubernetes 平台**  
  - 主导设计与落地基于 Rancher + Flatcar 的多节点高可用 Kubernetes 集群  
  - 使内部多语言研发体系（Rust/C++/Python/Yocto）统一使用容器化环境  

- **建设 GitOps 体系（GitLab + ArgoCD + Kustomize）**  
  - 推动研发团队从手工部署迁移到 GitOps 流程  
  - 实现代码提交到自动发布全链路自动化  
  - 环境一致性问题减少 **80%**

- **基础设施自动化（Terraform + GitLab CI）**  
  - 统一公司 IaC 标准，所有基础设施资源实现版本化与自动化  
  - 发布效率显著提升 

- **核心存储与内部平台组件管理**  
  - 负责 Harbor、TrueNAS NFS、ExternalDNS、Bind9、MetalLB 等关键组件  
  - 构建平台级监控体系：Prometheus + Grafana

- **与 CISO（首席安全官）合作推进全链路安全合规**  
  - 包含 RBAC、供应链安全、镜像安全检查、网络隔离策略  
  - 保障公司产品线满足欧洲行业安全要求

#### ★ 项目：Appear Hub（Azure 客户交付平台）  
负责公司面向全球客户的固件、文档与 License 分发生态的云化改造。

- 主导设计基于 **Azure Container Apps + Front Door + Blob Storage** 的架构  
- 交付高可用、可全球访问的下载门户  
- 自动化部署（GitLab CI/CD）让交付流程基本实现 **无人值守**  

`2022–2025`  
### **Senior Infrastructure Engineer（核心基础设施架构师） — Sopra Steria（欧洲前十咨询公司）**

**公司简介**  
Sopra Steria 是欧洲 Top 10 的大型咨询与 IT 服务集团，为政府、金融、电信、能源等领域客户提供关键 IT 基础设施与数字化服务。项目规模大、合规要求重、交付周期长，是锻炼工程实践能力的典型环境。

**岗位定位**  
作为基础设施核心工程师 & 技术主力，负责云原生平台建设、CI/CD 能力提升、自动化体系搭建，同时承担小团队技术带教工作。

**核心工作与成果**

- **主导构建企业级 Kubernetes + GitHub ARC（关键里程碑项目）**  
  - 解决原 VM Runner 不稳定、扩展性不足问题  
  - 实现 CI/CD 动态扩缩容，每次构建自动创建/销毁  
  - 构建效率提升 **数倍**，故障率显著下降

- **设计并落地内部 S3（MinIO）作为 Terraform State 后端**  
  - 完全替代本地 state 文件  
  - 实现版本化、加密与团队协作  
  - 基础设施管理合规化、可审计化

- **搭建 GitOps 体系（ArgoCD + Helm + Kustomize）**  
  - 让开发团队可以“提交即部署”  
  - 发布效率显著提升，环境出错率降低 

- **建设统一监控平台（Prometheus + Grafana）**  
  - 从零构建 VM + 容器 + 应用级指标体系  
  - 让 SRE 和基础架构团队可实时感知系统状态

- **CI/CD 流水线深度优化**  
  - 重构底层构建镜像与 pipeline DSL  
  - 故障排查难度降低 
  - 提升开发团队交付体验（DevEx）

- **主导 RHEL7→RHEL8 自动化迁移项目**  
  - 使用 Ansible 实现批量升级  
  - 合规性和维护性全面提升

- **Ansible Automation Platform（AAP）在 OpenShift 上的部署负责人**
  - 设计，安装，部署AAP
  - 迁移自动化Ansible工作流到AAP

这一阶段使我具备了高复杂度基础设施项目的落地能力，也具备带领小组、推动跨团队协作的能力。

`2012–2022`  
### **System Engineer（系统工程师） — University of Oslo（挪威顶尖科研机构）**

**公司简介**  
挪威奥斯陆大学（UiO）是北欧顶尖研究型大学，其科研计算环境对稳定性、性能、数据安全性要求极高。

**岗位定位**  
负责科研数据中心的核心基础设施运维、HPC 支持、虚拟化平台管理，是实验室研发活动的重要技术支撑角色。

**核心工作与成果**

- 负责 Dell/HP/RedHat 等服务器的部署、运维与生命周期管理  
- 管理 VMware 与 KVM 虚拟化集群，支撑科研计算任务  
- 搭建并维护 RAID、Samba、NFS 存储系统  
- 管理 Cisco 网络设备、NAT、防火墙规则  
- 使用 SCCM + PXE 自动化部署 Linux和Windows 平台  
- 为 HPC 用户提供作业调优与运行环境支持  
- 解决科研软件依赖复杂、环境难复现等问题，为研究团队提升效率

这是我职业生涯的基础阶段，使我打下了坚实的 Linux、网络、虚拟化、存储和高性能计算的底层基础。


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
