---
layout: cv
title: 程刚中文简历
---
# 程 刚（Gang Cheng）

Red Hat 认证架构师（RHCA）｜基础架构工程师 / DevOps 工程师 / 平台工程师 / Developer Experience 工程师  

2024 年 Red Hat Certified Professional of the Year（挪威年度唯一获奖者）  

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat 简介</a> |
<a href="https://www.linkedin.com/in/gang-cheng-7170a521/">LinkedIn</a>
</div>

---

# 🎯 概要（Summary）

程刚是一位自我驱动、持续成长的工程师，坚信持续学习和快速掌握新技术是 IT 工程师的核心能力。他长期主动构建现代基础架构与平台工程能力，通过持续的项目实践、认证、会议、课程以及与行业同行学习，不断强化自身技术广度与深度。

2024 年，他荣获 **Red Hat Certified Professional of the Year** —— 这是 Red Hat 对个人技术能力的全球性认可，他也是当年挪威唯一获奖者。

在他的职业生涯中，他担任过系统管理员、基础设施工程师、DevOps 工程师、开发者体验（DevEx）工程师、平台工程师或多角色融合的岗位。他在团队中始终以“解决问题、创造价值”为目标。

凭借十年以上在不同规模与行业的基础设施环境中的经验，他成功为客户交付解决方案，创造价值，并与开发团队、研究团队保持紧密合作。他的沟通能力强，善于跨团队协作与推动落地。

---

# 💼 Employment（工作经历）

---

# ⭐ 2025–至今  
# **Senior Platform Engineer｜Appear TV（挪威）**

负责建设与维护现代化、高可用、高性能的基础设施平台，支持公司内部开发流程与产品交付。

---

## 🔹 **构建和维护现代化、可扩展的基础设施，为开发者生产力和高性能应用提供支撑**

### 使用的关键技术栈

- 裸金属 Kubernetes 集群（由 Rancher 管理）
- Flatcar（不可变式操作系统）
- GitOps：GitLab、ArgoCD、Kustomize
- Terraform 自动化（GitLab CI 触发 Terraform apply）
- TrueNAS NFS 存储
- Harbor 内部镜像仓库
- VMware 虚拟机管理
- 其他基础组件：ExternalDNS、Bind9、MetalLB、Replicator、GitLab Runners
- 监控体系：Prometheus + Grafana
- 与 CISO 协作确保 CI/CD 与平台全生命周期的安全与合规

---

## 🔹 **项目：部署 Appear Hub 于 Azure（客户固件/文档/License 下载平台）**

### 描述（Description）

构建一个面向客户的软件交付平台，用于固件、文档、许可文件的安全下载。平台需要高可用、全球访问、安全控制与自动化交付能力。

### 贡献（Contribution）

- 使用 **Azure Container Apps** 部署后端服务，支持弹性扩缩容
- 使用 **Azure Front Door** 提供全球路由、SSL、WAF、安全访问控制
- 使用 **Azure Blob Storage** 存储固件、文档和许可证
- GitLab CI 负责构建镜像、推送和自动部署
- 使用 Azure Monitor 进行日志与监控
- 确保系统满足企业安全与访问控制标准

### 价值（Value Created）

- 提升客户下载体验  
- 提供现代化交付体系  
- 显著降低运维成本  
- 系统安全性与可审计性增强  

---

# ⭐ 2022–2025  
# **Senior Infrastructure Engineer｜Sopra Steria（挪威）**

担任 DevOps/基础设施工程师，负责多个关键基础设施项目。以下为英文原文的逐条完整翻译：

---

## 🔹 **项目：构建高可用 Kubernetes + GitHub Actions Runner Controller（ARC）平台（独立负责）**

### 描述

原基于 VM 的 Runner 存在扩展性差、竞争条件、隔离性不足等问题，需要迁移到 Kubernetes。

### 贡献

- 独自设计并实现高可用 Kubernetes 集群与 ARC 控制器
- 构建动态 Runner，任务结束即销毁
- 将所有 VM Runner 迁移到 Kubernetes
- 重构 pipeline 并定义新部署流程
- 建立监控、日志和日常运维体系

### 价值

- 实现弹性扩容和更高效率的 CI/CD 平台  
- 显著提升可靠性、隔离性和可维护性  

---

## 🔹 **项目：MinIO S3 Terraform 状态后端（独立负责）**

### 描述

Terraform 状态文件原本存储在本地磁盘，不支持协作、版本控制或审计。

### 贡献

- 在 Kubernetes 上部署 MinIO 并实现 S3 接口  
- 将其整合至 GitHub Actions pipeline  
- 配置访问控制、加密、版本化  
- 将所有 Terraform 项目迁移至 MinIO 后端

### 价值

- 实现状态文件集中化、版本控制、安全管理  
- 无需依赖公共云，完全满足合规要求  

---

## 🔹 **项目：构建 GitOps 工作流（Argo CD）**

### 描述

开发团队需要一种自动化、统一的部署方式，可通过分支管理不同部署环境。

### 贡献

- 设计 GitOps 架构：GitHub → ArgoCD → Kubernetes  
- 构建 Helm 可复用模板  
- 使用 Kustomize 管理环境差异  
- 设置项目 RBAC 与隔离策略  
- 与开发团队一起重新设计部署生命周期

### 价值

- 部署自动化、可审计  
- 显著降低开发者认知负担与运维工作量  
- 部署更快速、更可靠  

---

## 🔹 **项目：基础设施监控体系（Prometheus + Grafana）**

### 描述

随着 VM 与容器规模增长，需要统一监控平台。

### 贡献

- 在 Kubernetes 上部署 Prometheus 和 Grafana  
- 定义告警规则  
- 创建 VM、集群、应用的健康仪表板  
- 联合团队定义监控策略

### 价值

- 提升系统透明度  
- 更快定位性能瓶颈  
- 提升可靠性  

---

## 🔹 **项目：CI/CD 流水线故障排查与优化**

### 描述

开发团队面临 pipeline 错误、执行缓慢、行为不稳定等问题。

### 贡献

- 分析 pipeline 日志，定位错误根源  
- 优化 Runner 配置、缓存、构建逻辑  
- 清理与重构不稳定任务
- 标准化流水线结构并改善开发者体验

### 价值

- 大幅提升 pipeline 稳定性  
- 减少开发者排查时间  
- 提高交付效率  

---

## 🔹 **项目：基础设施标准化与自动化**

### 描述

基础环境存在不一致性，手动配置较多。

### 贡献

- 标准化操作系统版本、VM 模板、配置文件  
- 编写自动化安装脚本和初始化流程  
- 为生产环境建立统一准入规范

### 价值

- 提升一致性  
- 降低运维成本  
- 提升安全性  

---

## 🔹 **项目：自动化升级 RHEL7 → RHEL8**

### 描述

RHEL7 即将 EOL，需要对大量服务器执行升级。

### 贡献

- 使用 Ansible 自动化升级流程  
- 与应用团队合作进行兼容性验证  
- 优化升级流程以减少停机时间

### 价值

- 满足安全与合规要求  
- 降低人工升级成本  

---

## 🔹 **项目：在 OpenShift 上部署 Ansible Automation Platform（AAP）**

### 描述

随着 Ansible Playbook 和 Inventory 增长，需要中央管理平台。

### 贡献

- 在 OpenShift 上部署 AAP  
- 配置 Playbook、Inventory、Secrets  
- 定义 RBAC 权限体系

### 价值

- 降低人为错误  
- 提升自动化能力  

---

## 🔹 **项目：部署 RHEL9 到生产**

### 描述

需要测试与部署 RHEL9，使其满足生产要求。

### 贡献

- 使用 Ansible 自动部署  
- 制作 RHEL9 VMware 模板  
- 集成 AD，确保兼容性

### 价值

- 为新系统提供可复用、可扩展的部署方式  

---

## 🔹 **项目：Red Hat 虚拟机补丁自动化系统**

### 描述

手工补丁管理成本高、风险大。

### 贡献

- 使用 Satellite + Ansible 构建自动补丁流程  
- 自动检测缺失补丁与执行升级  
- 建立补丁基线和回滚策略

### 价值

- 提升安全性  
- 降低维护开销  

---

## 🔹 **项目：自动化部署 Red Hat VM（VMware）**

### 描述

规模化 VM 部署需要自动化能力。

### 贡献

- 使用 Ansible 完成自动化部署  
- 包含网络、用户、包管理等完整流程  
- 支持集群级部署

### 价值

- 提升部署速度与服务器一致性  

---

## 🔹 **项目：部署关键应用（独立负责）**

### 描述

部署关键业务应用到基础设施环境。

### 贡献

- 负责安装、配置、调试  
- 处理兼容性问题  
- 确保应用满足组织政策与安全标准

### 价值

- 保证关键业务平台稳定运行  

---

## 🔹 **项目：Splunk 实施（日志与指标平台）**

### 描述

需要统一日志收集与分析平台。

### 贡献

- 部署 Splunk Enterprise  
- 配置日志索引与采集规则  
- 构建基础设施健康监控 Dashboard  
- 支持事件追踪与故障定位

### 价值

- 大幅提升可观测性  
- 降低 MTTR（平均恢复时间）  

---

# ⭐ 2012–2022  
# **System Engineer｜University of Oslo（挪威）**

以下为逐条完整翻译：

---

## 🔹 **服务器与数据中心管理**

- 采购、安装、配置与维护 Dell、HP、Red Hat 等企业服务器  
- 管理科学计算、虚拟化（VMware / KVM）、数据库、Web 服务  
- 管理 RAID、Samba、NFS 等存储系统  
- 为科学研究提供高可靠、高性能计算环境  

---

## 🔹 **Windows 设备部署与管理（SCCM）**

- 使用 PXE 自动化部署 Windows  
- 使用 Microsoft SCCM 管理客户端生命周期  
- 自动化软件分发、补丁管理、安全策略

---

## 🔹 **网络管理（Cisco）**

- 负责私有实验室网络和公共网络  
- 使用 Cisco 交换机与路由器  
- NAT、网络隔离、端口管理  
- 维护数据中心网络安全与稳定性  

---

## 🔹 **科研软件与复杂依赖管理**

- 部署、配置复杂科研软件  
- 解决软件依赖不明确、版本冲突等问题  
- 与研究人员合作优化计算环境  

---

## 🔹 **高性能计算（HPC）支持**

- 提供 HPC 集群用户培训  
- 支持作业提交、并行计算优化  
- 协助研究数据处理与集群调优  

---

# 📜 Certificates（证书）

（按英文原文完整翻译、顺序一致）

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

---

# 📚 Events & Conference（会议与活动）

- Cloud Native Day Oslo 2025  
- Red Hat Summit & Ansible Fest  

---

# ✍ Articles（文章）

- 《Let’s talk about troubleshooting》  
- 《Challenges, tips, and rewards: working as a consultant in Norway》  
- 《Cloud Native Day Oslo — From DevOps to DevEx》  

---

# 🎓 Courses（课程）

（全量翻译）

- Google Cloud Fundamentals  
- NVIDIA：AI Infrastructure and Operations  
- GenAI for DevOps Practitioners  
- Linux Foundation：Introduction to DevOps and SRE  
- Linux Foundation：Cloud Infrastructure Technologies  
- Microsoft Azure Fundamentals  
- Intrusion Detection and Firewalls  
- Enterprise Networking  
- Research Methods and Data Analysis  
- Mastering Ansible  
- Introduction to programming with scientific applications  
- Red Hat：Containers, Kubernetes & OpenShift Fundamentals

---

# 🧪 Workshops（工作坊）

- Azure Red Hat OpenShift AI  
- AWS RAG & Fine-tuning  
- HPC hands-on workshops  
- Cilium Deep Dive  
- Git 版本控制  
- Cryptography & SSH  
- Python Scientific Computing  
- OpenStack 虚拟化架构  
- UiO AI Hub  

---

# 🔧 技术栈（Experienced Tech Stacks）

- Kubernetes、Docker、Podman  
- GitHub Actions、GitHub ARC  
- Red Hat Linux、Satellite、OpenShift、Ansible  
- Bitbucket、Confluence、Jira  
- Grafana、Prometheus  
- Dell PowerEdge、Cisco  
- Windows Server、SCCM  
- Samba、NFS、FirewallD、AD  

---

# 🌱 Exposure Skills（其他接触技能）

- AWS  
- Azure  
- OpenStack  
- Vagrant  

---

# 🎓 教育背景（Education）

**University of Oslo（2010–2012）**  
硕士：Network and System Administration

---

# 🧗 兴趣（Hobbies）

博客写作、滑雪、徒步旅行

---

# 🌐 语言（Languages）

- 英语：专业工作熟练度  
- 挪威语：专业工作熟练度  
- 中文：母语  

