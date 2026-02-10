---
layout: cv
title: 程刚中文简历
---

# 程 刚（Gang Cheng）

Red Hat 认证架构师（RHCA）｜Red Hat 2024 年度认证专业人士 (RHCP of the Year)｜平台工程师 ｜ 平台架构/治理 ｜ AIOps/Platform Ops ｜ Developer Experience 工程师  

<div id="webaddress">
<a href="https://www.redhat.com/zh-cn/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat 官方页面对程刚的简介</a> |
<a href="https://www.linkedin.com/in/gang-cheng-7170a521/">LinkedIn</a>
</div>

## 概要（Summary）

程刚是一位自驱力极强、长期深耕平台工程与云原生架构的工程师，拥有十余年在欧洲一线企业和科研机构的实战经验。他聚焦 **平台化、可治理与可运营** 的能力建设，擅长以架构视角制定路线图、推进跨团队落地，并带领junior工程师成长，通过大型项目实践、专业认证、技术工作坊与行业合作，不断提升在 **系统架构设计、平台治理、工程化交付与平台运营** 方面的能力。

2024 年，他被授予 **Red Hat Certified Professional of the Year 2024**，这是 Red Hat 面向全球认证工程师颁发的年度最高技术荣誉，当年全球仅此一人。这一奖项高度认可了他在 Red Hat 企业级 Linux、OpenShift、Ansible 自动化、容器与平台工程领域的深度实践与技术影响力。

在技术广度与深度方面，他覆盖 **平台工程、SRE、HPC 与 GPU 基础设施** 等方向，长期从事 **Kubernetes / OpenShift / Rancher、GitOps、基础设施即代码（Terraform / Ansible）、可观测性、安全治理与合规平台设计** 等工作。无论环境是在本地数据中心、公有云还是混合云，他都能围绕业务目标完成从 **平台蓝图、能力建模、治理策略到工程落地与运营优化** 的闭环。


凭借十年以上多样化基础设施环境经验，他持续交付稳定、高性能的平台，为业务方、开发者和科研用户创造价值，并与跨职能团队保持高效协作。他良好的沟通、结构化思维和协作能力，使其能够在复杂工程组织中持续输出有价值的成果。

---

## 工作经历（Employment）

`2025–至今`  
### Senior Platform Engineer — Appear TV（挪威 奥斯陆）

**公司简介**  
Appear TV 是全球领先的视频压缩、媒体处理与分发技术提供商，客户包括全球主要广播机构、电信运营商和大型赛事组织，例如 NBCUniversal、Discovery、NHL、Formula 1、Riot Games 等，对底层基础设施的稳定性、安全性和低时延要求极高。

#### ★ NVIDIA GPU 集群落地与模型服务平台（NVIDIA GPU Cluster & Model Serving Platform）

**职责（Responsibilities）**

- 设计并落地 **NVIDIA GPU 集群平台化能力**，规划 GPU 资源治理与服务化交付路径，协调研发与平台团队推进模型服务上线。  
- 通过 **GPU Operator** 统一管理基础能力，并建立可复用的集群基线。  
- 引入 **Time Slicing** 与 **MPS**，实现 GPU 资源的细粒度共享与多租户并发优化。  
- 将 **GitLab Runner** 的 GPU 资源纳入平台调度体系，设计并优化 GPU Pipeline 作业与资源策略。  
- 部署 VMAF 质量评估推理服务（GPU 加速），集成到 VX 产品测试流程，支持内部 AI/ML 研发与上线。
- 实现基于 GPU 指标的自动扩缩容（HPA），支持弹性负载

---

#### ★ CISO 协作与平台安全治理（CISO Partnership & Platform Security Governance）

**职责（Responsibilities）**

- 构建并落地 **Kyverno Policy-as-Code** 安全治理体系，作为平台级安全控制的核心能力。
- 主导安全治理策略评审与落地路径，推动安全与业务需求对齐并形成可执行规范。  
- 复盘现有基础设施与平台安全基线，识别关键风险与潜在漏洞。  
- 设计与编写 **验证（Validating）与变更（Mutation）策略**，并持续迭代与优化策略库。  
- 以 GitOps 方式交付与部署安全策略，确保策略可审计、可追溯、可回滚。  
- 与 CISO 和安全架构师紧密合作，在 Kubernetes 与 DevOps 环境中落地安全与合规控制，支持公司向 IPO 和 ISO 27001 认证做准备。  
- 交付平台安全加固方案，包括 RBAC / IAM 治理、网络策略、机密与密钥管理、漏洞修复流程、镜像扫描与供应链安全（SBOM / 签名）、审计日志等。  
- 难点不在于写策略文件本身，而在于 **策略必须贴合业务需求**：在安全、效率与简洁之间取得平衡，形成可落地、可维护的安全治理机制。

---

#### ★ 内部 AI / LLM 能力与开发者体验平台（Internal AI & Developer Experience Platform）

为支持工程团队在日志与遥测分析、文档生成、故障说明、代码辅助等场景下更好地使用大模型，需要搭建一个统一的内部 AI / LLM 能力平台，替代零散的个人账号与工具试验，同时满足访问控制与合规要求。

**职责（Responsibilities）**

- 作为这一计划的技术推动者，主导项目从技术选型到落地与推广全过程。  
- 制定阶段性路线图与交付标准，组织评审与技术决策，协调多团队推进实施。  
- 评估多种 LLM 后端与工具（托管 API 与本地推理），重点对比 **延迟、并发特性、Token 成本与生成质量**，包括 OpenAI、RequestyAI 以及本地 Llama 模型等。  
- 设计基于 Kubernetes 的容器化部署模型，集成公司现有 SSO / 开发者工具，形成 **多租户隔离、访问控制与审计** 的平台能力。  
- 建立公司首个 **统一的内部 AI 入口与平台能力层**，将 AI 使用从个人、临时、不可控试验，升级为 **系统化、可治理、可审计的内部能力**。  
- 为未来构建类似“AI Gateway”的多租户路由、成本与可观测性、治理能力提供了坚实平台基础。

---

#### ★ DevOps 平台与云原生基础设施（Cloud-Native Infrastructure Foundation）

- 设计并构建基于 **Rancher + Flatcar 的高可用裸金属 Kubernetes 平台**，提供标准化的平台底座与能力边界。  
- 牵头平台能力规划与演进路线图，推动跨团队对齐平台边界与服务目录。  
- 使用 **GitLab CI、Argo CD、Kustomize** 实现 GitOps 工作流，将交付流程平台化与可审计化。  
- 通过 **Terraform** 标准化基础设施资源的创建与管理，并配合 CI/CD 流水线实现自动化交付与变更治理。  
- 平台化运营关键能力组件：Harbor 镜像仓库、TrueNAS NFS 存储、ExternalDNS、Bind9、MetalLB、Yocto 相关构建环境以及 GitLab Runners 等。  
- 通过设计评审、最佳实践与可复用模板，指导 junior 工程师提升交付效率与一致性。  
- 使用 **Prometheus + Grafana** 构建平台与工作负载的可观测性体系，覆盖集群、应用、流水线与关键业务 SLO。  
- 在敏捷开发模式下工作，参与 Sprint 计划、每日站会和迭代交付；经常使用 Jira 与 Confluence 管理工作与平台变更文档。

---

#### ★ 季度级灾备演练：基于 IaC 的全栈基础设施重建（Quarterly DR & Full Infra Rebuild via IaC）

为验证平台在灾难场景下的可恢复能力，并确保基础设施即代码（IaC）始终真实、完整且可用，团队定期执行破坏性灾备演练：**每季度对基础设施进行“全量销毁 + 从零重建”**。

- 设计并执行季度 DR 演练，完整移除现有的 Kubernetes 集群、虚拟机、网络、存储和各类平台服务。  
- 使用 **Terraform + Ansible + 集群引导脚本** 对整个环境进行自动化重建，验证 IaC 描述的完整性和时效性，确保可直接用于生产级恢复。  
- 确保恢复过程可重复、时间可预测，最大限度降低对手工操作的依赖，提高整体基础设施可靠性。  
- 编写 DR 操作文档，对恢复时间进行度量，为安全与合规提供可审计的 Evidence。
- 建立可被证明、可审计的灾备能力，确认平台可从“零基础设施”状态依赖 IaC 完整恢复。  
- 降低配置漂移风险，增强平台韧性与合规性，为重大故障或灾难恢复提供可靠保障。

---

#### ★ Hub 平台（Azure 全球客户与合作伙伴门户 — 进行中）

Hub 是一个新一代门户平台，用于替代多个历史系统，为全球客户和代工厂提供统一、可信和安全的访问入口，支持：

- 固件与软件版本的发布与下载  
- 已部署设备的 License 与授权管理  
- 在线文档、发布说明与配置指南访问  
- 支持请求、日志与诊断信息上传  
- 合同制造商（CM）的生产相关操作与资源访问等  

**职责（Responsibilities — in progress）**

- 设计并运营 Appear Hub 所依赖的 **Azure 基础设施**，使用 **Azure Container Apps、虚拟机、Azure Container Registry、Blob Storage、Front Door 与 DNS** 等服务。  
- 使用 **Entra ID（Azure AD）** 设计安全的认证与授权模型，通过基于角色的访问控制（RBAC）区分客户、内部用户与代工厂用户。  
- 建立 CI/CD 与 IaC 模式，确保环境可重复、部署可审计、变更可追溯。  
- 使用 **Azure Monitor / Log Analytics / Application Insights** 实现可观测性，关注可用性、延迟、下载成功率与支持请求相关指标。  
- 与产品、支持和制造团队一起沟通需求，将其抽象为稳定、可演进的平台能力。

---

`2022–2025`  
### Senior Infrastructure Engineer — Sopra Steria（挪威）

在 Sopra Steria 任职期间，主要以 DevOps / 基础架构工程师身份为多个大型客户提供咨询与落地服务，主导或参与的项目包括：

#### ★ 搭建高可用 Kubernetes 平台与 GitHub Actions Runner Controller（ARC）（独立负责）

**背景**  
客户原先使用基于虚拟机的 GitHub self-hosted runners，存在扩展性差、资源占用高、隔离性不足以及运维成本较高等问题，难以支撑越来越多的 CI/CD 工作流。

**职责（Responsibilities）**

- 独立设计并实现高可用 Kubernetes 集群，部署 GitHub Actions Runner Controller (ARC) 管理动态 Runner。  
- 将 CI/CD 工作流从 VM Runner 迁移到 Kubernetes 平台，实现按需创建/销毁 Runner 的弹性能力。  
- 设计自动伸缩策略和隔离机制，与开发团队协作重构流水线。  
- 建立监控与告警，确保新平台稳定运行。

**价值（Value Created）**

- 提供安全、可扩展、自动化的 CI/CD Runner 平台，显著降低手工运维工作。  
- 提升构建可靠性与隔离性，提升开发者生产力，并为后续规模化扩展打下基础。

---

#### ★ API Gateway 与 API 管理平台 MVP（OpenShift 上的客户 PoC）

**背景**  
客户需要对内部微服务 API 进行统一治理，包括认证、路由与限流策略，以支持未来更大规模的 API 使用场景。

**职责（Responsibilities）**

- 在 OpenShift 上部署 **Red Hat 3scale API Management**，包括 API Manager 与 APIcast Gateway，使用官方 Operator 与 APIManager CRD。  
- 配置 products、backends、路由规则、API Key 与限流（rate-limit）方案，模拟真实内部 API 的治理流程。  
- 演示开发者门户（Developer Portal）的使用，包括 API 文档、凭证发放与集成示例。  
- 编写可迁移的参考架构文档，为未来使用 Kong / Apigee / AWS API Gateway 等产品时提供指导。

**价值（Value Created）**

- 交付可运行的 PoC，展示如何集中治理 API 流量、认证和访问控制。  
- 虽未进入生产，但为客户后续 API-First 战略提供了清晰的架构方向与决策依据。
- 
---

#### ★ 在 OpenShift 上集成 Ceph 存储（Ceph Storage Integration for OpenShift）

**背景**  
客户需要为 OpenShift 上的有状态业务提供可扩展、高可用的存储后端。

**职责（Responsibilities）**

- 部署并配置 Ceph 集群作为 OpenShift 的存储后端，确保节点间复制与高可用。  
- 通过 StorageClass 与动态 PVC 机制，将 Ceph 集成到 OpenShift，支持数据库、消息队列等有状态服务。  
- 验证读写性能、冗余能力与故障恢复流程。  
- 编写运维文档，包括 OSD 故障恢复、节点替换、监控与容量规划。

**价值（Value Created）**

- 为 OpenShift 工作负载提供生产级存储基础，使有状态服务能够稳定运行。  
- 通过自动故障转移与自愈能力降低存储相关运维风险。

---

#### ★ 基于 MinIO 的 Terraform State 管理后端（S3-Compatible Backend on Kubernetes）

**背景**  
Terraform state 文件原本存放在本地磁盘，缺乏版本管理与协作能力；由于政策限制，无法使用公共云 S3。

**职责（Responsibilities）**

- 在内部 Kubernetes 平台上设计并部署 MinIO，作为兼容 S3 的集中式 Terraform state 后端。  
- 将其集成到 GitHub Actions 流水线中，实现安全、版本化的 Terraform state 存储。  

**价值（Value Created）**

- 构建可靠、集中、可版本化的 Terraform state 后端，提高协作性与审计能力。  
- 在不依赖公有云的前提下，显著提升基础设施管理的稳定性与合规性。

---

#### ★ 使用 Argo CD 实现 GitOps 部署流程（独立负责）

**背景**  
随着开发团队对快速发布和多环境灵活切换的需求提高，需要构建一个基于 Git 的自动化部署平台，实现“代码合并即触发部署”。

**职责（Responsibilities）**

- 使用 Argo CD 设计与实现 GitOps 流程，将 GitHub 分支映射到不同 Kubernetes Namespace，实现自动化部署。  
- 构建基于 Helm 的可复用模板与分层仓库结构，支持动态环境。  
- 实施 RBAC 与项目隔离策略，保障安全性；与开发团队协作设计部署流程。

**价值（Value Created）**

- 建立灵活、自动化的 GitOps 部署管道，支持开发者自助部署到多环境。  
- 提高发布速度、一致性与安全性，显著降低运维负担。

---

#### ★ 大规模 Red Hat 虚拟机补丁治理与自动化平台（独立负责）

在组织内部拥有大量 Red Hat 虚拟机，分布在生产、预生产、测试等不同环境，补丁来源包括 Red Hat 官方仓库、Microsoft 以及多家第三方软件仓库。不同系统对补丁窗口、安全要求、可用性要求均不同，过去依赖人工方式进行补丁管理，费时、易错且缺乏一致性，存在显著的安全风险。

**主要职责**
- 设计并实现基于 Ansible 与 Red Hat Satellite 的 **策略化补丁自动化框架**，支持多类型服务器及多仓库补丁源的动态选择。
- 根据服务器角色（Web、应用、中间件、数据服务、与微软组件集成的节点等）制定 **差异化补丁策略**。
- 处理 Satellite 中来自多个源（Red Hat、Microsoft、第三方）的补丁内容，确保按系统功能精准匹配与选择。
- 构建分阶段补丁流程，包括 dry-run、选择性补丁应用、自动重启流程、验证步骤、失败回滚机制等。
- 与应用负责人协调 **补丁窗口、影响分析、SLA 要求**，确保生产环境变更安全可控。
- 建立补丁状态报告、合规性检查、错误追踪及例外处理机制，形成长期可治理的补丁体系。

**项目价值**
- 将补丁管理从手工操作转变为 **标准化、自动化、可审计的企业级补丁治理平台**。  
- 显著降低人为错误与停机风险，提高系统可用性与安全性。  
- 实现补丁一致性与可追踪性，为合规与审计要求奠定基础。  

---

#### ★ Red Hat Linux 生命周期自动化管理（RHEL7→8 升级 + RHEL9 可用性验证）— 独立负责

随着 RHEL7 进入生命周期末期，需要对大量现网服务器进行升级，同时也必须提前验证 RHEL9 的兼容性、安全性和可运维性，为未来的大规模上线做准备。因此项目分为两个并行方向：自动化升级现有系统，以及对下一代操作系统进行全面测试和生产化准备。

**主要职责**
- 负责规划与实施 **RHEL7→RHEL8 的分阶段升级策略**，包括依赖梳理、兼容性评估、变更窗口安排，以及可回退方案的制定，并与各业务/应用负责人协同推进。
- 使用 Ansible 构建 **自动化升级流程**，实现对多类型服务器的大规模、可重复、低风险升级，减少人为操作误差与停机风险。
- 同步开展 **RHEL9 功能与兼容性验证**，测试其在现有应用体系、内核行为、软件包依赖、网络与存储环境中的表现，并验证其与组织现有工具链的集成情况。
- 制作并验证 **RHEL9 的自定义加固 VMware 模板**，定义系统基线配置、安全策略、运行时依赖等，为后续批量部署建立统一标准。
- 输出详细的迁移文档、最佳实践和生命周期管理指南，为组织未来的 Red Hat 平台建设奠定可持续的基础。

**项目价值**
- 为 RHEL7→8 升级提供了结构化、自动化、合规的迁移流程，大幅降低运维风险。  
- 确保 RHEL9 在正式上线前经过充分验证、加固与标准化，具备生产落地条件。  
- 减少配置漂移与人为错误，显著提升未来系统的部署速度与一致性。
  
---

#### ★ 基于 OpenShift 的企业级 Ansible 自动化平台建设（Ansible Automation Platform）

随着组织内自动化脚本、Playbook、Inventory、Credential 数量不断增长，传统的分散式管理方式无法满足规模化、多团队、多环境的运维需求。AAP on OpenShift 被选为统一的自动化平台，以实现治理、安全、标准化与可审计性。

**主要职责**
- 主导部署 **AAP on Red Hat OpenShift**，包括 Automation Controller、Execution Environments、Private Automation Hub 等核心组件。  
- 设计 **多租户自动化架构**，为不同团队（运维、安全、开发）提供隔离的 Inventory、RBAC、Credential 与执行环境。  
- 基于容器化 Execution Environment 构建可重复、可移植、安全加固的自动化运行环境。   
- 建立自动化治理标准，包括代码审核、验证、测试流程及跨环境促进机制。  
- 配置审计日志、凭证使用追踪、执行记录等 **合规性控制**，满足内部安全要求。  
- 帮助多个团队将历史零散自动化迁移至平台，实现统一治理与可持续维护。

**项目价值**
- 将原本分散的自动化脚本体系升级为 **集中式、可治理、可审计的自动化平台**。  
- 显著提升自动化一致性、安全性与可重复性，减少人为错误并加速交付。  
- 构建可持续扩展的自动化基础架构，使后续团队扩展与新项目落地更高效。  

---

#### ★ CI/CD 流水线故障排查与优化（Troubleshooting & Improving CI/CD Pipelines）

- 针对自托管 Runner 上的流水线错误和不稳定问题，负责问题定位、性能优化与可靠性提升。  
- 与开发团队协作，使其从反复排障中解放出来，专注业务开发。
  
---

`2011–2022`  
### System Engineer — University of Oslo（挪威奥斯陆大学）

在奥斯陆大学（UiO）工作期间，主要负责 NCMM（分子医学中心）科研数据中心的基础设施与高性能计算环境：

- 部署与维护 Linux 计算节点、分布式 HPC 服务器与 NVIDIA GPU 服务器，支撑大规模科学计算。  
- 使用 SCCM、PXE 等工具实现 Windows 客户端的自动化部署与生命周期管理。  
- 管理 Cisco 交换机与路由、VLAN、NAT、私有 DNS / DHCP、基本防火墙策略等网络设施。  
- 安装与维护科研软件栈，支撑生物信息学、分子模拟及大数据分析等复杂应用。  
- 使用 Nagios、Zabbix 等监控系统，保障关键计算与存储系统的可用性。  
- 构建并运维 HPC 集群，包括 Slurm 调度、GPU 节点调度优化、共享存储与集群运维。

这一角色为其后续从事大规模分布式系统、平台工程、GPU 加速基础设施与高可靠性计算打下坚实基础。

---

`2008`  
### Archive Assistant & Logger — Olympic Broadcasting Services (OBS), 北京奥运会

- 在 IBC（国际广播中心）参与赛事内容记录与时间码标注。  
- 与全球制作团队合作处理多场馆实时信号。  
- 管理磁带档案（HDCAM / XD），为后期内容生产提供基础。

---

## 证书（Certificates）

- Red Hat Certified Professional of the Year 2024  
- Red Hat Certified Architect  
- Red Hat Certified Specialist in Containers  
- Red Hat Certified OpenShift Administrator  
- Red Hat Certified Specialist in Managing Automation with Ansible Automation Platform  
- Red Hat Certified Specialist in Deployment and Systems Management  
- Red Hat Certified Engineer  
- Red Hat Certified System Administrator  
- NVIDIA AI Infrastructure and Operations Fundamentals  
- Microsoft Certified: Azure Fundamentals  
- Red Hat Certified Specialist in Containers and Kubernetes  

---

## 会议与活动（Events & Conference）

- Cloud Native Day Oslo 2025  
- Red Hat Summit - Red Hat Ansible Fest  

---

## 文章（Articles）

- [Let´s talk about troubleshooting](https://medium.com/@gcccheng/lets-talk-about-troubleshooting-090ab6cbb95c)  
- [Challenges, tips, and rewards: working as a consultant in Norway](https://medium.com/@gcccheng/challenges-tips-and-rewards-working-as-a-consultant-in-norway-4b6ddce2ff3b)  
- [Cloud Native Day Oslo — From DevOps to DevEx](https://www.linkedin.com/pulse/cloud-native-day-oslo-reflections-highlights-gang-cheng-ripaf/)  

---

## 课程（Courses）

- Google Cloud Fundamentals  
- Nvidia Academy: AI Infrastructure and Operations  
- GenAI for DevOps Practitioners  
- Linux Foundation: Introduction to DevOps and Site Reliability Engineering (Graded and Certified)  
- Linux Foundation: Introduction to Cloud Infrastructure Technologies  
- Microsoft Azure Fundamentals  
- Intrusion Detection and Firewalls  
- Enterprise Networking: Practices and Technologies  
- Research Methods and Data Analysis  
- Mastering Ansible  
- Introduction to programming with scientific applications  
- Red Hat: Fundamentals of Containers, Kubernetes, and Red Hat OpenShift  

---

## 工作坊（Workshops）

- Azure Red Hat OpenShift AI  
- AWS RAG and Fine-tuned AI  
- Using the High Performance Computing cluster for Educloud Research users  
- Cilium Hands-On Workshop & Deep Dive Oslo  
- Manage VM, virtual network, firewall on Azure  
- Deploy AWS EC2 instance with Terraform  
- Python for Scientific Computing  
- Virtualized research architecture using OpenStack  
- AI at UiO  
- Using Environment Modules to initialize shell and modify shell environment  

---

## 其他项目（Other Projects）

- 在 Azure OpenShift 上构建多模型生成式 AI 体验  
- 使用 Terraform 为 Azure Provision VM 并配置 CI/CD 流水线  
- 构建基于 Proxmox 的虚拟化基础设施  
- 构建 Foreman + Ansible + Smart Proxy 平台，为大规模基础设施提供自动化主机部署  
- 将 Linux 集成到 Windows 域环境  
- 使用 OCS Inventory 搭建现代资产管理系统  
- 使用 OpenLDAP 搭建本地目录服务  
- 配置 Windows Server Update Services（WSUS）为实验环境提供补丁分发  
- 使用 Apache Guacamole 构建跨平台远程桌面网关  
- 使用 Snort 与 Munin 实现入侵检测与监控  

---

## 技术栈（Experienced Tech Stacks and Skills）

Kubernetes、Docker、Podman、GitHub Actions、GitHub Actions Runner Controller (ARC)、GitLab、Red Hat Linux、Red Hat Satellite、Red Hat OpenShift、Red Hat Ansible、Atlassian Bitbucket、Confluence、Jira、Grafana、Prometheus、Splunk、Dell PowerEdge、Cisco 交换机、Windows SCCM、Samba、NFS、FirewallD、Active Directory、Terraform、Bash、Perl、Python、Go  

---

## 接触技术栈（Exposure Tech Stacks and Skills）

AWS、阿里云（AliCloud）

---

## 教育背景（Education）

`2010–2012`  
奥斯陆大学（University of Oslo）：网络与系统管理 硕士  

---

## 兴趣（Hobbies）

博客写作、滑雪、徒步  

---

## 语言（Languages）

- 中文：母语  
- 英语：专业工作熟练度  
- 挪威语：专业工作熟练度  
