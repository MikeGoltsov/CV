## Mikhail Goltsov
Berlin, Germany  
Tel: +49 (159) 0174-32-33  
E-mail: mike.goltsov@gmail.com


## DevOps / Infrastructure / Platform Engineer · SRE

Infrastructure engineer with 15+ years designing, building, and operating reliable server, cloud, and network infrastructure — the last 6+ years focused on DevOps/SRE and platform engineering. 
Strong across the full lifecycle: architecture, Infrastructure as Code, CI/CD, observability, and incident response. 
Hands-on experience operating bare-metal Kubernetes clusters (1000+ nodes) and integrating them with data center networking (BGP, EVPN/VXLAN), combined with background in Linux kernel-level performance tuning.
Interested in advancing towards next-generation data center networking (SRv6, programmable data planes) and HPC-oriented workloads, building on existing experience with GPU-enabled Kubernetes environments.

### Key Strengths

**Bare-metal Kubernetes at scale:** design, provisioning, and operation across multi-DC environments  

**Deep networking expertise:** Linux network stack (eBPF, IRQ/RSS tuning, packet flow), CNI internals, and DC fabric integration  

**Kubernetes ↔ network integration:** BGP-based routing, service/pod traffic flow, latency and packet path optimization  

**Performance engineering:** latency reduction, bottleneck analysis, efficient resource utilization  

**End-to-end ownership:** from physical infrastructure and routing to platform and cloud layers  

**Infrastructure as Code:** reproducibility, disaster recovery, and cost control  

## Core Technologies

**Cloud & IaC:** AWS, Hetzner, Yandex Cloud, Terraform, Ansible, Jsonnet/QBEC  

**Automation & tooling:** Bash, Python, Go  

**Containers & Platform:** Kubernetes, k3s · Docker, containerd, cri-o · Helm · CNI (Calico, Cilium, Multus), CSI · NGINX ingress  

**CI/CD:** GitLab CI/CD, GitHub Actions, CircleCI  

**Observability:** Prometheus, VictoriaMetrics/Logs, Thanos · Grafana, Loki, ELK/OpenSearch, Vector · Tempo, Jaeger, OpenTelemetry · Zabbix  

**Linux & Virtualization:** Linux internals — namespaces/cgroups, isolation, eBPF, perf · CentOS/RHEL, Ubuntu · KVM, Proxmox, VMware ESXi/vCenter, oVirt  

**Networking & Kernel — end to end, from fabric to pod:**  
- **Linux network stack (deep):** Linux networking subsystem, NIC tuning (queues, RSS/RPS, IRQ affinity), interrupt handling, eBPF/XDP  
- **Kubernetes networking:** CNI internals (Calico, Cilium, Multus), pod/service routing, network policy, ingress  
- **Fabric integration:** BGP route exchange between nodes and a CLOS spine-leaf fabric, VXLAN/EVPN overlays, SDN (Cumulus Linux)  
- **Routing & switching (8+ yrs enterprise/DC):** BGP/MP-BGP, OSPF, ISIS, MPLS, VRF · Cisco, Juniper, Arista, Mikrotik · VPN: IPSec, DMVPN, L2VPN/L3VPN  

**Data & Messaging:** PostgreSQL, ClickHouse, ScyllaDB, Redis/KeyDB · etcd, ZooKeeper · Kafka, NATS, NSQ · Ceph, MinIO, GlusterFS, NVMe-oF  

## Professional Experience

**Vay Technology GmbH** — Berlin, Germany
*Senior / Principal DevOps Engineer · SRE · Tech Lead* · 08.2022 – present

- Design and operate reliable on-site and multi-region AWS infrastructure across a fleet of 300+ physical hosts, sustaining a 99.9% SLA under high automotive reliability standards
- Drove company-wide adoption of Infrastructure as Code, achieving fully reproducible infrastructure and cutting disaster-recovery deployment time by ~60%
- Migrated infrastructure services into Kubernetes, improving operability and reducing cloud/CI costs by ~30%
- Built an observability platform from scratch (VictoriaMetrics, Grafana, Loki, Alertmanager), delivering metrics, logging, and alerting across the fleet and backend services, improving incident detection and response time
- Owned a fleet of ~600 business-critical Peplink SD-WAN routers providing vehicle connectivity, covering configuration, troubleshooting, and lifecycle operations
- Built and maintained an internal provisioning/configuration service (Python prototype later rewritten in Go) that automated router onboarding and configuration via the vendor API, including modem, tunnel, and system setup
- Modernized SSH access management by migrating from FreeIPA to Vault-based OIDC/Google Workspace auth, codifying role-based access in Terraform and separating production/staging permissions
- Owned AWS infrastructure (VPC, IPv6, Security Groups, networking), diagnosing and resolving performance bottlenecks and hardening access controls
- Acted as technical lead for infrastructure and platform decisions

**OZON.ru** — Saint Petersburg, Russia
*Senior DevOps Engineer* · 11.2020 – 08.2022

- Owned lifecycle of large-scale bare-metal Kubernetes clusters (1000+ nodes across 3 data centers) serving the company's commercial workload
- Built automated provisioning pipeline (bare metal → production-ready node) including OS, networking, and cluster integration
- Designed and operated multi-DC fault-tolerant clusters, handling cross-DC traffic and failure scenarios
- Improved network performance by modifying kernel/IPVS behavior, reducing P99 latency by ~50% and improving overall resource efficiency (~5%)
- Performed low-level performance tuning (IRQ affinity, queue tuning, packet processing path) to optimize throughput and latency
- Deployed GPU-enabled Kubernetes clusters for test/ML workloads
- Applied Infrastructure as Code across environments; managed cloud infrastructure (Yandex Cloud) and partnered with engineering teams on platform-wide issues

**STC Ltd.** — Saint Petersburg, Russia
*Network Engineer → Senior DevOps / Infrastructure Engineer* · 06.2019 – 11.2020

- Designed and built a data center from the ground up — hardware selection and procurement, network and cluster architecture, deployment, and customer handover/training
- Designed and automated deployment and operations for Kubernetes, ScyllaDB, and Ceph clusters
- Managed cloud infrastructure (Selectel) and facilitated dev/ops collaboration
- Worked across compute and network layers, bridging traditional networking and platform engineering

**General Radio Frequency Management Centre** — Khabarovsk, Russia
*Network Engineer → Senior Network Engineer → Team Lead* · 11.2014 – 05.2019

- Deployed and maintained a country-wide enterprise network and its monitoring infrastructure
- Led routing/switching architecture, troubleshooting, and monitoring systems; designed and implemented DMZ infrastructure
- Performed in-depth network troubleshooting and upgrades 
- Planned and deployed Cisco VoIP solution (CUCM) with Active Directory integration

**Honda Motor Co. Ltd** — Khabarovsk, Russia
*System Engineer* · 10.2005 – 11.2014

- Provided full-stack infrastructure support (systems, networking, virtualization)
- Configured Cisco routing/switching, structured cabling, and WLAN deployments; deployed and maintained VPN solutions
- Administered Windows Server and FreeBSD on Dell/HP hardware; managed Hyper-V and VMware virtualization

## Education & Certifications

- **Cisco ROUTE 2.0** — Softline Education, Moscow, 2015
- **VMware vSphere: Install, Configure, Manage** — Softline Education, Khabarovsk, 2011
- **Computer Science, Engineer (Specialist)** — Khabarovsk State Technical University, 2005

## Languages
Russian (native) · English (working proficiency)