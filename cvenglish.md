---
layout: cv
title: Gang Cheng's CV
---
# Gang Cheng 

Red Hat Certified Architect, Red Hat Certified Professional of the Year, Infrastructure/DevOps/DevEx/Platform Engineer

<div id="webaddress">
<a href="https://www.redhat.com/en/blog/announcing-2024-red-hat-certified-professional-year-gang-cheng">Red Hat Bio</a> | <a href="https://www.linkedin.com/in/gang-cheng-7170a521/">Linkedin page</a>
</div>

## Summary

Gang is self-motivated professional who believes that continuous learning and the ability to rapidly adopt new technologies are essential qualities of a modern infrastructure professional. Throughout his career, he has proactively built expertise in designing and operating large-scale systems through hands-on projects, professional certifications, technical workshops, conferences, courses, and collaboration with industry peers. His dedication and technical depth were formally recognized when he was named the **Red Hat Certified Professional of the Year 2024**, the sole global recipient of the award.

Beyond his foundation in Red Hat technologies, Gang has expanded his skills across DevOps engineering, cloud-native platform engineering, site reliability engineering, on-premises data center, and high-performance computing environments, regardless of title and environment, Gang adapts to what the business require. He has also worked closely with security leaders to ensure that platforms meet modern security and compliance expectations, gaining hands-on experience with implementing practical security controls and supporting audit readiness efforts. 
 
With over a decade of hands-on experience across diverse IT infrastructure environments, he has successfully delivered stable, high-performance platforms, created value for stakeholders, and collaborated closely with developers, researchers, and cross-functional teams. His strong communication skills, structured thinking, and collaborative mindset continue to enable him to drive meaningful contributions in complex engineering organizations.

## Employment
`2025–Present`
### Senior Platform Engineer — Appear TV, Oslo, Norway  
Appear TV is a leading European provider of video compression, media processing and distribution technology, widely used by global broadcasters, telecom operators and major live event organizations, including BCUniversal、Warner Bros. Discovery、NHL、Formula 1、Riot Games. Reliability, low latency and system stability are core to its products.

**Responsibilities & Achievements**

##### ★ Internal AI Platform (AI Capability Enablement)
Designed and delivered Appear’s internal AI platform based on OpenWebUI to support engineering use-cases such as log analysis, documentation generation, error explanation and code assistance.

- Served as project technical owner; led the full architecture and implementation.
- Evaluated OpenWebUI, Ollama, LM Studio and other LLM tooling; drove final platform selection.
- Designed containerized deployment, model management workflow, plugin system and multi-team access control.
- Led a 2–3 person initiative for rollout, optimization and knowledge base integration.
- Promoted AI-assisted engineering practices across R&D teams.

**Impact**
- Established the company’s first unified AI portal, greatly lowering adoption barriers.
- Engineering teams’ AI usage increased substantially, shifting from ad-hoc to systematic use.
- Formed the foundation for future RAG, code indexing and AI-driven DevEx automation.

---

#### ★ DevOps Platform (Cloud-Native Infrastructure Foundation)
- Designed and built a highly available bare-metal Kubernetes platform using Rancher and Flatcar.
- Unified development environments across Rust, C++, Python, Yocto and TypeScript teams.
- Implemented GitOps workflows with GitLab CI, Argo CD and Kustomize, enabling consistent and auditable deployments.
- Standardized infrastructure provisioning with Terraform and automated CI/CD pipelines.
- Maintained key platform components: Harbor registry, TrueNAS NFS, ExternalDNS, Bind9, MetalLB, Yocto and GitLab Runners.
- Built observability using Prometheus + Grafana for clusters, workloads and pipelines.
- Worked closely with the CISO and security architects to implement security and compliance controls across Kubernetes and DevOps environments, supporting the company’s efforts toward ISO 27001 / SOC 2 certification readiness.
- Delivered platform-level security hardening, including RBAC/IAM governance, network policies, secrets management, vulnerability remediation, image scanning, supply-chain security (SBOM/signing), and audit logging.
- Worked effectively within Agile and Scrum teams, participating in sprint planning, stand-ups, and iterative delivery workflows.
- Regularly used Jira and Confluence to track engineering work, document platform changes, and collaborate with cross-functional teams.


`2022-2025`
### Senior Infrastructure Engineer at Sopra Steria

During past years, Gang has been worked as DevOps/infrastructure engineer and led/contributed to a variety of projects for customers, including:

`project`

**Building High Availability Kubernetes and Github Actions Runner Controller(ARC)(sole role)**

Description: The existing use of GitHub self-hosted runners on virtual machines (VMs) led to significant scalability issues, race conditions, and lack of workload isolation. As the number of CI/CD workflows grew, VM-based runners could no longer provide a flexible and manageable solution. To address this, a container orchestration platform was required to dynamically provision and scale runners on demand, ensuring standardized, isolated, and scalable infrastructure for GitHub Actions workflows.

Contribution: Took sole role in designing and implementing a high-availability Kubernetes cluster with GitHub Actions Runner Controller (ARC) to manage dynamic runner provisioning. Migrated CI/CD workflows from VM-based runners to Kubernetes, implemented automated scaling and isolation, and collaborated with developers to refactor pipelines. Established platform monitoring and ongoing maintenance processes.

Value Created: Delivered a secure, scalable, and automated CI/CD runner platform, reducing manual overhead and improving isolation, reliability, and developer productivity. Standardized the CI/CD pipeline infrastructure for consistency and scalability, while enabling on-demand scaling to meet workload peaks.


`project`

**Implementing Local S3-Compatible Backend for Terraform State Management using MinIO on Kubernetes(sole role)**

Description: Terraform state files were previously stored on local disks, causing issues like lack of version control and collaboration challenges. Public cloud storage (e.g., AWS S3) was not an option due to policy constraints.

Contribution: Designed and deployed a MinIO-based S3-compatible backend on an internal Kubernetes platform. Integrated it with GitHub Actions pipelines to enable secure and versioned Terraform state storage within the CI/CD workflow.

Value Created: Established a reliable, centralized, and versioned Terraform state backend, improving collaboration, auditability, and infrastructure stability—without relying on public cloud services.

`project`

**Implementing GitOps Deployment Workflow with Argo CD (sole role)**

Description: With increasing demands from developers for faster and more flexible deployments, there was a growing need for a platform that allows developers to dynamically choose which environment to deploy their code to. The goal was to create an automated workflow where a code merge in GitHub would automatically trigger deployment of a new version in Kubernetes — enabling self-service, reducing manual operations, and aligning with modern DevOps practices.

Contribution: Designed and implemented GitOps workflows using Argo CD, connecting GitHub branches to Kubernetes namespaces for automated deployments. Built Helm-based reusable templates and structured repositories for dynamic environments, and implemented RBAC and project isolation for security. Worked with development teams to define deployment flows and ensure smooth integration.

Value Created: Established a flexible and automated deployment pipeline aligned with GitOps, enabling developers to deploy code seamlessly across environments. Improved deployment speed, consistency, and security, and reduced operational overhead by shifting to self-service workflows.

`project`

**Building Infrastructure Monitoring System(sole role)**

Description: With the increasing number of containers and virtual machines, it became critical to have a unified platform to monitor the entire infrastructure.

Contribution: Building Prometheus and Grafana on an existing Kubernetes platform to monitor both containers and VMs, integrating alerting and visualization.

Value Created: Provided real-time infrastructure visibility, automated alerting, and improved platform stability.
 
`project`

**Troubleshooting and Improving CI/CD Pipelines**

Description: The development team encountered various errors and instability when running pipelines on self-hosted runners.

Contribution: Troubleshot pipeline errors, optimized performance, improved reliability, and worked closely with developers to maintain organized workflows.

Value Created: Freed developers from troubleshooting, allowing them to focus on development and improving overall pipeline efficiency.

`project`

**Infrastructure Standardization and Automation(sole role)**

Description: The current infrastructure management was manual, inconsistent, and lacked standardization, leading to inefficiencies and errors across different environments.

Contribution: Standardized operating systems, simplified and automated VM provisioning and management process.

Value Created: Improve infrastructure consistency, reduce manual errors, enhance security, and significantly speed up deployment times through automation.


`project`

**Automating Upgrading RHEL7 to RHEL8 (sole role)**

Description: RHEL7 was approaching the end of support, so upgrading hundreds of RHEL7 was a high priority.

Contribution: Designed upgrading plan with application owners and automated upgrading job with Ansible.

Value Created: Ensure systems are aligned with security compliance standards.


`project`

**Ansible Automation Platform on Openshift**

Description: With an ever-increasing number of playbooks, inventories, and workflows, manually managing them is challenging. A central platform is required to orchestrate all the elements related to Ansible.

Contribution: Collaborated with teams on deploying the Ansible Automation Platform on Openshift.

Value Created: Reduced manual tasks and errors while managing playbooks, inventories, and secrets, improved operational efficiency, and enhanced security


`project`

**Deploying Red Hat 9 to Production Infrastructure (sole role)**

Description: Need to test RHEL9 and make it ready for production use.

Contribution: Deployed Red Hat 9 using Ansible, created a customized Red Hat image template for VMware, and integrated the system with Windows AD.

Value Created: Enable seamless deployment, ensure system compatibility, and make new OS ready for production environment.


`project`

**Automating Patching of Red Hat VM (sole role)**

Description: The manual patching process for a large-scale Red Hat environment was time-consuming and prone to errors, requiring a more efficient automated solution.

Contribution: Designed and implemented an Ansible-based workflow with Red Hat Satellite to automate patching.

Value Created: Streamlined patching, reduced errors, and improved system uptime and security across the infrastructure.

`project`

**Automating the Provisioning of Red Hat VM on VMWare Private Cloud Platform**

Description: The manual work of provisioning large-scale Red Hat VM was just impossible.

Contribution: Designed and implemented an Ansible-based workflow that automated the process of provisioning VM into the production environment.

Value Created: Streamlined installation, configuration, and management of VM.


`project`

**Deploying critical application to infrastructure(sole role)**

Description: A critical cloud-based application must be deployed, configured, and tested across the entire platform.
Contribution: Solo responsibility for installing, configuring, and troubleshooting applications.

Value Created: Ensure that the system is aligned with organization policies.

`project`

**Splunk Implementation**

Description: Implemented Splunk to monitor and analyze logs and metrics across infrastructure. The project involved centralized log collection, efficient indexing, and actionable insights to enhance system observability and operational efficiency.

Contribution: Deployed and configured Splunk Enterprise for centralized log aggregation and real-time monitoring. Developed custom dashboards for infrastructure health monitoring, including CPU usage, memory consumption, disk I/O, and application performance metrics.

Value Created: Enhanced system reliability and performance by proactively identifying incidents.


`2011-2022`
### System Engineer at University of Oslo

At the University of Oslo, Gang played a key role in managing and operating a local data center dedicated to delivering robust and reliable scientific computing infrastructure for researchers at the Centre for Molecular Medicine Norway (NCMM). His responsibilities spanned core IT operations, distributed systems engineering, and close collaboration with scientific researchers. Key activities included:

Server & Infrastructure Management: Installed, configured, and maintained compute systems for scientific workloads, including Linux-based compute nodes, distributed HPC servers, and NVIDIA GPU-accelerated machines. Built and operated foundational components of the university’s high-performance computing environment, ensuring system reliability, performance, and scalability across research workloads.

Windows Deployment and Administration: Automated provisioning and lifecycle management of Windows clients using PXE and SCCM (System Center Configuration Manager). Streamlined software distribution, security patching, and policy compliance for stable operation.

Network Operations: Administered public and private research networks using Cisco switches and routers, including NAT, VLAN segmentation, private dns domain and dhcp zone, firewall rules, port assignments, and connectivity troubleshooting to support secure, high-availability access to computing resources.

Scientific Software & Distributed Computing Environment: Installed and maintained complex scientific software stacks with unstable dependencies. Optimized computational environments for bioinformatics, molecular modeling, and large-scale data analysis, providing technical guidance for advanced distributed workloads.

Daily IT Operations: Performed daily responsibilities including user provisioning, access control, storage management, system monitoring (Nagios, Zabbix), and incident troubleshooting, minimizing downtime for critical research systems.

High-Performance Computing (HPC) Engineering & Parallel Workload Support: Contributed to the build-out and ongoing operation of the university’s HPC cluster, including configuration of distributed compute nodes with NVIDIA GPU nodes, shared storage, and Slurm scheduling services. Supported researchers in running parallel and GPU-accelerated jobs, optimized workload performance, and troubleshot issues across multi-node and high-throughput workflows.

This role formed the foundation for Gang’s later specialization in large-scale distributed systems, platform engineering, GPU-accelerated infrastructure, and high-reliability computing environments.


`2008`
### Archive Assistant & Logger — Olympic Broadcasting Services (OBS), Beijing Olympics  
OBS is the International Olympic Committee’s broadcast organization responsible for host broadcasting for the Olympic Games.

- Logged event highlights (SOG) with timestamps for indexing and editing workflows.
- Worked at the International Broadcast Center (IBC) with global production teams handling multi-venue live feeds.
- Assisted in managing tape-based archival media (HDCAM/XD) preserved by the IOC.
- Gained foundational experience in media signal processing long before transitioning into professional media infrastructure engineering.


## Certificate
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
- 
## Events & Conference

<a href="https://cloud-native-day-oslo-2025.sessionize.com/schedule"> Cloud Native Day Oslo 2025 </a>

<a href="https://www.redhat.com/en/summit?sc_cid=7013a000003SgNoAAK&gad_source=1&gclid=Cj0KCQjwkN--BhDkARIsAD_mnIrWsK8FpcovhjhNkmFLjS6y1CHJ86KXi1ZhIma1cS59K3BK2zOzx9QaAp_EEALw_wcB&gclsrc=aw.ds"> Red Hat Summit - Red Hat Ansible Fest </a>

## Articles

<a href="https://medium.com/@gcccheng/lets-talk-about-troubleshooting-090ab6cbb95c"> Let´s talk about troubleshooting </a>

<a href="https://medium.com/@gcccheng/challenges-tips-and-rewards-working-as-a-consultant-in-norway-4b6ddce2ff3b"> Challenges, tips, and rewards: working as a consultant in Norway </a>

<a href="https://www.linkedin.com/pulse/cloud-native-day-oslo-reflections-highlights-gang-cheng-ripaf/?trackingId=rpGDQr2us8CpWZiuR3Sx%2FA%3D%3D"> Cloud Native Day Oslo — From DevOps to DevEx </a>

## Courses

<a href="https://www.coursera.org/learn/gcp-fundamentals"> Google Cloud Foundamentals </a>

<a href="https://www.nvidia.com/en-us/learn/certification/ai-infrastructure-operations-associate/"> Nvidia Academy: AI Infrastructure and Operations
 </a>

<a href="https://www.coursera.org/learn/genai-for-devops-practitioners"> GenAI for DevOps Practitioners </a>

<a href="https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS162x+3T2019/home"> Linux Foundation: Introduction to DevOps and Site Reliability Engineering(Graded and Certified)</a>

<a href="https://learning.edx.org/course/course-v1:LinuxFoundationX+LFS151.x+2T2020/home"> Linux Foundation: Introduction to Cloud Infrastructure Technologies

 
<a href="https://docs.microsoft.com/en-us/learn/certifications/azure-fundamentals/"> MicroSoft Azure Foundamentals </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF5004NSA/index.html"> Intrusion detection and firewalls </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF4018NSA/index.html"> Enterprise Networking: Practices and Technologies </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF5100NSA/index.html"> Research Methods and Data Analysis </a>

<a href="https://www.udemy.com/course/mastering-ansible/?gclid=Cj0KCQiAhMOMBhDhARIsAPVml-HCo3Nm7AYmD15j425Ld7FLtLZOYQ9vTev6CMsi5-DeO7ST9exGqw0aAuX3EALw_wcB&matchtype=e&utm_campaign=LongTail_la.EN_cc.ROW&utm_content=deal4584&utm_medium=udemyads&utm_source=adwords&utm_term=_._ag_80675493522_._ad_535700245675_._kw_ansible+course_._de_c_._dm__._pl__._ti_kwd-822946965094_._li_1010826_._pd__._"> Ansible For System Automation </a>

<a href="https://www.uio.no/studier/emner/matnat/ifi/INF1100/index-eng.html">Introduction to programming with scientific applications</a>

<a href="https://www.edx.org/course/fundamentals-of-containers-kubernetes-and-red-hat">Red Hat: Fundamentals of Containers, Kubernetes, and Red Hat OpenShift</a>

## Workshops
<a href="https://events.redhat.com/profile/form/index.cfm?PKformID=0x11991670001">Azure Red Hat OpenShift AI</a>

<a href="https://aws-experience.com/emea/north/e/ddd34/aws-immersion-day-generative-ai"> AWS RAG and Fine-tuned AI</a>
            
<a href="https://www.uio.no/english/services/it/research/hpc/fox/index.html"> Using the High Performance Computing cluster for Educloud Research users </a>
    
<a href="https://isovalent.com/isovalent-hands-on-workshop-oslo/"> Cilium Hands-On Workshop & Deep Dive Oslo </a>

Manage vm, virtul network, firewall on Azure
  
<a href="http://modules.sourceforge.net/">Using Environment Modules to initialize shell and modify shell environment</a>
  
Deploy AWS EC2 instance with terraform
  
<a href="https://www.ub.uio.no/english/courses-events/courses/other/coderefinery/Python%20for%20Scientific%20Computing%20%28internediate%29"> Python for Scientific Computing</a>

<a href="https://arnsteio.github.io/UH-IaaS-mini-workshop/"> Virtualized research architecture using openstack</a>
  
<a href="https://www.uio.no/tjenester/it/forskning/kompetansehuber/uio-ai-hub-node-project/it-resources/"> AI at UiO </a>

## Other Projects

Build multi-model Generative AI experiences on Azure Openshift

Provision VM using Terraform and Configuring CI/CD pipeline on Azure

Build Proxmox virtual infrastructure for complex IT system
  
Build Foreman+Ansible+Smart Proxy and provision hosts for large infrastructure
  
Integrate Linux to Windows Domain

Build modern inventory system with OCS inventory
  
Set up local directory service with OpenLDAP
  
<a href="https://docs.microsoft.com/en-us/windows-server/administration/windows-server-update-services/get-started/windows-server-update-services-wsus"> Set up Windows Server Update Services for lab network </a>

<a href="https://guacamole.apache.org/">Using Apache Guacamole as free and open-source cross-platform Remote Desktop Gateway</a>
  
Intrusion detection and monitoring with Snort and Munin

## Experienced Tech Stacks and Skills
Kubernetes, Docker, Podman, GitHub Actions, GitHub Actions Runner Controller(ARC), GitLab, Red Hat Linux, Red Hat Satellite, Red Hat Openshift, Red Hat Ansible,  Atlassian Bitbucket, Atlassian Confluence, Atlassian Jira, Grafana, Prometheus, Dell PowerEdge, Cisco SWitch, Windows SCCM, Samba, NFS, FirewallD, Active Directory, Terrafform, Bash, Perl, Python, Go 

## Exposure Tech Stacks and Skills
AWS, AliCloud

## Education
`2010-2012`
University of Oslo: Master in Network and System Administration

  
## Hobbies 
Blog writing, Skiing, and hiking
  
## Languages 

Chinese: Native 

English: Full Professional Working Proficiency
  
Norwegian: Professional Working Proficiency




  

<!-- ### Footer

Last updated: May 2013 -->

