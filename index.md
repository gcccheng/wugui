---
layout: cv
title: 程刚中文简历
---

# 程 刚（Gang Cheng）

Red Hat 认证架构师（RHCA）｜Red Hat 2024年度认证专业人士(RHCP)｜基础架构工程师 ｜ DevOps 工程师 ｜ 平台工程师 ｜ Developer Experience 工程师  

<div id="webaddress">
<a href="https://www.redhat.com/zh-cn/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat 官方页面对程刚的简介</a> |
<a href="https://www.linkedin.com/in/gang-cheng-7170a521/">LinkedIn</a>
</div>

## 概要（Summary）

程刚是一位深耕基础架构、云原生与 DevOps 领域的资深人士，开源拥趸，拥有十年以上欧洲一线企业与科研机构的实战经验，曾在媒体科技、金融技术服务、大型政府 IT 部门以及高性能科研计算环境中承担核心平台建设工作。他在 Kubernetes 平台、DevOps 体系化建设、基础设施自动化、可观测性和云平台架构方面具有扎实的工程能力与丰富的落地经验，并在职业早期参与建设和运维高性能计算（HPC）集群，处理分布式计算节点、NVIDIA GPU 服务器、Slurm 调度与并行计算环境。

2024 年，程刚荣获 **Red Hat Certified Professional of the Year** ——
这是 Red Hat 面向全球红帽认证工程师授予的最高级别技术奖项，
每年在全球仅选出一位获奖者。他不仅是 全球年度唯一获奖者，同时，他也是该奖项设立以来首位来自中国的获奖工程师。
这一荣誉代表了业界对他在 Red Hat、容器平台、自动化、OpenShift、Ansible 以及企业级基础架构设计与实施方面的高度认可，也表明他的技术实践能力与思考方式达到了国际顶级水准。

除了在平台工程与自动化方面的深厚积累外，程刚长期与安全负责人密切合作，负责在 Kubernetes 和 DevOps 环境中落地实际可运行的安全与合规控制，包括访问权限治理、供应链安全、网络与配置基线、日志审计与漏洞修复等实际工程工作。他也参与审计准备流程，确保系统在满足业务需求的同时符合现代安全与合规要求。无论团队规模、组织架构或岗位头衔如何变化，他始终能够根据业务目标快速适应，承担关键平台职责，推动稳定性、可靠性与合规性的持续提升。

在多个岗位中，他担任平台核心负责人角色，具备带领小型工程团队推进复杂基础设施项目落地的经验，能够独立完成架构设计、项目拆解、跨团队协作以及工程落地。他重视工程质量、可维护性与可扩展性，擅长以工程方式解决复杂问题，并推动系统性、长期价值的建设。

作为极具自驱力的工程师，他持续投入学习并主动吸收新技术，具备从 0 到 1 搭建平台体系的能力，也能够在现有架构中识别瓶颈、推动优化，帮助组织构建更稳定、更安全、更高效的基础设施能力。

## 工作经历（Employment）

`2025–至今`  
### **Senior Platform Engineer（平台技术负责人） — Appear TV（挪威·全球领先的视频编解码与分发技术提供商）**

**公司简介**  
Appear TV 是欧洲领先的视频传输、编解码和媒体分发技术公司，北欧上市企业，客户涵盖全球一线广播机构、通信运营商与大型媒体集团。公司产品广泛应用于奥运会、世界杯等高并发、高稳定性场景，对底层基础设施的可靠性要求极高。

**岗位定位**  
作为平台技术负责人，负责公司底层基础设施架构规划、云原生平台建设与 DevOps 体系升级，同时带领小型技术团队（协作性质），支撑核心研发团队的高性能研发体系。

**核心工作与成果**

- **从 0 到 1 搭建裸金属 Kubernetes 平台**  
  - 主导设计与落地基于 Rancher + Flatcar 的多节点高可用 Kubernetes 集群  
  - 使内部多语言研发体系（Rust/C++/Python/Yocto）统一使用容器化环境

- **建设 GitOps 体系（GitLab + ArgoCD + Kustomize）**  
  - 推动研发团队从手工部署迁移到 GitOps 流程  
  - 实现代码提交到自动发布的全链路自动化  

- **基础设施自动化（Terraform + Ansible）**  
  - 统一 IaC 标准，所有基础设施资源实现版本化与自动化  
  - 发布效率显著提升

- **平台核心组件管理**  
  - 负责 Harbor、TrueNAS NFS、ExternalDNS、Bind9、MetalLB 等基础组件  
  - 构建平台级监控体系（Prometheus + Grafana）

- **与 首席信息安全官CISO 合作推进全链路安全合规**  
  - 覆盖 RBAC、供应链安全、镜像扫描、网络隔离策略  
  - 确保平台满足欧洲行业安全要求

---

#### ★ 项目：构建公司内部 AI 应用平台（AI 能力体系化建设）

**项目背景（Project Background）**  
随着生成式 AI 在媒体与视频技术行业快速发展，Appear 需要构建统一的内部 AI 能力平台，以支持代码分析、文档生成、日志解释与研发辅助等核心场景。现有工具分散且缺乏企业级访问控制，需要一个统一且可扩展的平台。  
OpenWebUI 是当前最受工程团队欢迎的轻量级企业级 LLM 平台，支持模型管理、插件生态、多工具链扩展，适合企业内部构建 AI 能力中心。

**个人角色与贡献（Contribution）**  
- 项目技术 Owner，从 0 到 1 设计并落地 Appear 内部 AI 平台  
- 评估 OpenWebUI、Ollama、LM Studio 等主流 LLM 平台并主导最终选型  
- 设计平台整体架构，包括容器化部署、模型管理、pipeline功能、rag功能等  
- 为内部研发团队提供**统一 AI能力入口（AI Portal）** ，带领 2–3 人小组完成部署、调优与持续改进  
- 推动 AI 能力融入公司研发流程，建立内部 AI 使用规范，并让AI的使用变得可控可管理，符合安全标准
- 为 RAG、代码库索引、文档自动生成等未来 AI 能力奠定平台基础  
- 强化公司在欧洲媒体技术领域的创新能力

---

#### ★ 项目：Appear Hub（Azure 客户交付平台）

**项目背景（Project Background）**  
为全球客户提供固件、文档、License 统一下载门户，需要一个高可用、全球访问优化、可审计的交付系统。

**个人角色与贡献（Contribution）**  
- 主导整体架构设计，使用 **Azure Container Apps + Front Door + Blob Storage**  
- 构建自动化交付流水线（GitLab CI/CD），从打包、构建到部署全链路  
- 提供全球加速、高可用、安全访问策略

**项目价值（Value Created）**  
- 客户访问体验显著提升  
- 提高文档/固件交付流程自动化率
- 客户支持类工单减少大量重复性问题


`2022–2025`  
### **Senior Infrastructure Engineer（核心基础设施架构师） — Sopra Steria（欧洲前5咨询公司）**

**公司简介**  
Sopra Steria 是欧洲 Top 5 的大型咨询与 IT 服务集团，为政府、金融、电信、能源等领域客户提供关键 IT 基础设施与数字化服务。项目规模大、合规要求重、交付周期长，是锻炼工程实践能力的典型环境。

**岗位定位**  
作为基础设施核心工程师 & 技术主力，负责客户云原生平台建设、CI/CD 能力提升、自动化体系搭建，同时承担小团队技术带教工作。

**核心工作与成果**

- **主导构建企业级 Kubernetes + GitHub ARC（关键里程碑项目）**  
  - 解决原 VM Runner 不稳定、扩展性不足问题  
  - 实现 CI/CD 动态扩缩容，每次构建自动创建/销毁  
  - 构建效率提升 **数倍**，故障率显著下降

- **设计并落地内部 S3（MinIO）作为 Terraform State 后端**  
  - 完全替代本地 state 文件  
  - 实现版本化、加密与团队协作  
  - 基础设施管理合规化、可审计化

- **搭建 GitOps 体系（ArgoCD + Helm + Kustomize + GitHub）**  
  - 让开发团队可以“提交即部署”  
  - 发布效率显著提升，环境出错率降低 

- **建设统一可观测平台（Prometheus + Grafana）**  
  - 从零构建 VM + 容器 + 应用级指标体系  
  - 让 SRE 和基础架构团队可实时感知系统状态

- **CI/CD 流水线深度优化**  
  - 重构底层构建镜像与 pipeline   
  - 故障排查难度降低 
  - 提升开发团队交付体验（DevEx）
- **Red Hat 虚拟机补丁自动化（独立负责）**
  - 大规模 Red Hat 环境人工补丁耗时长、易出错，需要构建更高效、可审计的自动化补丁方案。
  - 基于 Ansible 与 Red Hat Satellite 设计并实现补丁自动化工作流，替代传统手工流程。
  - 显著提升补丁效率、减少操作错误、增强系统安全性并提升整体正常运行时间（uptime）。

- **主导 RHEL7→RHEL8 自动化迁移项目**  
  - 使用 Ansible 实现大规模Red Hat批量升级  
  - 合规性和维护性全面提升

- **Ansible Automation Platform（AAP）在 OpenShift 上的部署负责人**
  - 设计，安装，部署AAP
  - 迁移大规模Ansible工作流到AAP平台

这一阶段使我具备了高复杂度基础设施项目的落地能力，也具备带领小组、推动跨团队协作的能力。

`2011–2022`  
### **System Engineer（系统工程师） — University of Oslo（挪威顶尖科研机构）**

**公司简介**  
挪威奥斯陆大学（UiO）是北欧顶尖研究型大学，其科研计算环境对稳定性、性能、数据安全性要求极高。

**岗位定位**  
负责科研数据中心的核心基础设施运维、HPC 支持、虚拟化平台管理，是实验室研发活动的重要技术支撑角色。

**核心工作与成果**

- 参与奥斯陆大学科研数据中心的高性能计算（HPC）平台建设与运维，分布式计算节点、NVIDIA GPU 节点的部署、调试与稳定性保障，支持研究人员运行基于 Slurm 的并行计算任务。
- 搭建并维护 RAID、Samba、NFS、Nagios 监控系统，以及内部网络、私有 DNS/DHCP 域，确保科研环境的高可用与数据安全。
- 管理 VMware 与 KVM 虚拟化集群，支撑多实验室、多学科的科学计算与数据密集型任务。
- 配置与维护 Cisco 网络设备、NAT、防火墙策略，为 HPC 集群和科研系统提供稳定的网络基础。
- 使用 SCCM + PXE 自动化部署 Linux/Windows 系统，实现批量节点装机与环境一致性。
- 为 HPC 用户提供运行环境调优、GPU 故障排查与依赖软件配置支持，解决科研软件环境复杂难复现的问题，提高科研团队计算效率。

通过这些工作，我在职业生涯早期建立了坚实的 Linux 系统、网络、存储、虚拟化和高性能计算（HPC/分布式系统）基础，为后续在企业级平台工程、云原生和稳定性架构方向奠定了核心能力。


这是我职业生涯的基础阶段，使我打下了坚实的 Linux、网络、虚拟化、存储和高性能计算的底层基础。

`2008`
### **Archive Assistant & Logger（转播资料记录与内容标注） — Olympic Broadcasting Services（国际奥委会·奥运转播机构）**

**公司简介**  
Olympic Broadcasting Services（OBS）是国际奥委会直属机构，负责奥运会全球电视信号（Host Broadcast）的制作与分发，是全球体育转播技术最前沿的组织之一。其在 IBC（国际广播中心）运营的多源采集、内容标注、元数据管理与信号分发流程，是整个全球奥运转播体系的核心。

**岗位定位**  
作为北京奥运会 IBC 的 Archive Assistant & Logger，参与奥林匹克赛事影像资料的采集、事件标注与档案管理工作，为世界各地转播商提供可检索、可索引的结构化内容。该岗位是全球体育内容处理链路中极为关键的基础环节。

**核心工作与成果**

- **负责赛事精彩瞬间（SOG）标注与时间码记录**  
  - 根据转播画面实时记录关键事件，以时间码（timestamp）形式建立索引  
  - 这些结构化元数据为后期编辑、国际转播商制作内容包（highlight packages）提供基础

- **参与早期“半自动化内容标注流程”**  
  - 2008 年的标注方式已初具 AI 训练数据雏形（结构化标签 + 时间线序列数据）  
  - 多语种、多场馆海量内容在 IBC 汇聚，需人工严格保证准确性和一致性

- **协作管理赛事档案系统**  
  - 所有素材均以磁带（传统 HDCAM / XD formats）记录并存档  
  - 这些档案目前由 IOC 存放于瑞士，为多年后媒体使用提供珍贵历史资产

- **在国际团队环境中工作**  
  - 与来自欧洲、北美、亚太的制作、编辑、技术人员协作  
  - 深入理解国际媒体行业链路（采集 → 标注 → 内容包 → 转播）

**项目价值（Value Created）**

- 参与了历史上最成功、最复杂、最具技术突破性的奥运转播工作之一  
- 建立了对 **直播信号处理、内容索引、媒体元数据与大规模分发链路** 的早期理解  
- 该经历为后来进入媒体技术领域（Appear）带来强关联性  
- 对“视频传输”“低延时分发”“转播链路稳定性”等概念拥有**早于行业的第一手经验**  

## 证书（Certificates）

- Red Hat 2024 年度认证专业人士（Red Hat Certified Professional of the Year 2024）
- Red Hat 认证架构师（Red Hat Certified Architect）
- Red Hat 容器认证专家（Red Hat Certified Specialist in Containers）
- Red Hat OpenShift 管理员认证（Red Hat Certified OpenShift Administrator）
- Red Hat Ansible 自动化平台管理认证专家（Red Hat Certified Specialist in Managing Automation with Ansible Automation Platform）
- Red Hat 系统部署与管理认证专家（Red Hat Certified Specialist in Deployment and Systems Management）
- Red Hat 认证工程师（Red Hat Certified Engineer，RHCE）
- Red Hat 认证系统管理员（Red Hat Certified System Administrator，RHCSA）
- Red Hat 容器与 Kubernetes 认证专家（Red Hat Certified Specialist in Containers and Kubernetes）
- 英伟达AI基础设施与运维基础认证（NVIDIA AI Infrastructure and Operations Fundamentals）
- 微软 Azure 基础认证（Microsoft Certified: Azure Fundamentals）

## 会议与活动（Events & Conference）

- Cloud Native Day Oslo 2025  
- Red Hat Summit & Ansible Fest

## 其他项目（Other Projects）

- Build multi-model Generative AI experiences on Azure Openshift
- Provision VM using Terraform and Configuring CI/CD pipeline on Azure
- Build Proxmox virtual infrastructure for complex IT system
- Build Foreman+Ansible+Smart Proxy and provision hosts for large infrastructure
- Integrate Linux to Windows Domain
- Build modern inventory system with OCS inventory
- Set up local directory service with OpenLDAP
- Set up Windows Server Update Services for lab network
- Using Apache Guacamole as free and open-source cross-platform Remote Desktop Gateway
- Intrusion detection and monitoring with Snort and Munin

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

## 技术栈（Experienced Tech Stacks and Skills）

- Kubernetes、Docker、Podman, GitHub Actions、GitHub Actions Runner Controller (ARC) , Red Hat Linux、Red Hat Satellite、Red Hat OpenShift、Red Hat Ansible, Atlassian Bitbucket、Confluence、Jira, Grafana、Prometheus、Splunk, Dell PowerEdge、Cisco, Windows SCCM, Samba、NFS、FirewallD、Active Directory, Terraform, Bash, Perl, Python, Go 

## 其他接触技能（Exposure Tech Stacks and Skills）

AWS， AliCloud

## 教育背景（Education）

`2010–2012` **奥斯陆大学 — 网络与系统管理 - 硕士**

`2006–2010` **中国传媒大学 - 计算机技术 - 学士**

## 兴趣（Hobbies）

博客写作、滑雪、徒步  

## 语言（Languages）

- 英语：专业工作熟练度  
- 挪威语：专业工作熟练度  
- 中文：母语  
