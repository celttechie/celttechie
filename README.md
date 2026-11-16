# Brian Jarrett
**Staff Platform Engineer & Systems SRE | Software Engineering, Virtualization & FedRAMP ATO**

[Portfolio](https://celttechie.github.io/) · [Resume (PDF)](https://celttechie.github.io/resume.pdf) · [LinkedIn](https://www.linkedin.com/in/bjarrett) · [Technical Execution & Learning](https://celttechie.github.io/articles/technical_execution_and_rapid_learning/)

I build software, automation, and virtualization platforms for regulated environments—most recently leading reliability and FedRAMP ATO compliance across **6,000+ nodes at Cisco** and contributing upstream to **CNCF KubeVirt CDI**. Nearly 30 years across hardware diagnostics (USAF AWACS), pre-Sysprep Windows disk cloning (`ImageCast IC3`), commercial PHP/Python software engineering (`Centre/SIS`), distributed storage (`Ceph`), and Linux/cloud-native infrastructure.

### Featured Engineering & Open Source
| Project | Focus | Highlights |
| :--- | :--- | :--- |
| [**uds-vm-operator**](https://github.com/celttechie/uds-vm-operator) & [**KubeVirt CDI #4340**](https://github.com/kubevirt/containerized-data-importer/pull/4340) | KubeVirt / Zarf / Lula | Air-gap Kubernetes VM operator & CLI (`Python kopf` → `Go controller-runtime`) with NIST 800-53 OSCAL validation, plus upstream CDI upload checksum validation |
| [**openshift-ai-infrastructure**](https://github.com/celttechie/openshift-ai-infrastructure) & [**openshift-sno-lab**](https://github.com/celttechie/openshift-sno-lab) | OpenShift / VFIO / vLLM | OpenTofu SNO (`<10ms` etcd fsync), PCIe VFIO GPU passthrough, NVIDIA CDI & vLLM Day-2 runbooks |
| [**tactical-edge-gateway**](https://github.com/celttechie/tactical-edge-gateway) & [**tactical-edge-sdn**](https://github.com/celttechie/tactical-edge-sdn) | Edge / DDIL / Netlink | Async Python MAVLink/ROS2 → TAK/CoT gateway & WireGuard/FRRouting/Netlink SD-WAN with Zarf/Lula |
| [**FROGlib**](https://github.com/FROG3160/FROGLib) *(Team 3160)* | Robotics / Python | 10+ years mentoring FIRST Robotics; swerve kinematics, AprilTags vision & CTRE Phoenix 6 motor simulation |

### Background Highlights
* **Cisco Systems (`2016–2026`):** Technical Leader & Senior SRE across **6,000+ FedRAMP Moderate nodes**; directed **Log4j** zero-day response, built a **Flask / Plotly Dash / PostgreSQL / TabPy** SRE Error Budget platform (**~10x** remediation throughput), automated **DISA STIG XCCDF** & **80,000-record ConMon** pipelines, and resolved a **Windows Sysprep `specialize` / `cloudbase-init`** race condition via `SetupComplete.cmd`.
* **ALS (`2014–2016`):** Architected **Ceph RBD** distributed storage for VMware ESXi (validated 2-of-3 node failure tolerance) and **Python/SQLAlchemy** data-integrity migrations.
* **Foundational Software, Infra & QA (`1997–2014`):** 8 years contract Software Engineer for **Glenn Abbey Software** on **Centre/SIS** (PHP `CalcGPA.php`, SQL migrations, Python `APSCN` ETL); **Garfield County SD 16** (Flask/SQLAlchemy AD sync **-97%** tickets, XenServer); **StorageSoft `ImageCast IC3`** (solved duplicate Windows NT **Machine SIDs** in the registry before Microsoft Sysprep existed).
* **U.S. Air Force (`1991–1995`):** E-3 Sentry (AWACS) radar specialist — **Honor Graduate (99% avg)** & **Senior Airman Below-the-Zone**. U.S. Citizen, clearance-eligible.

**Production Core:** Python (Flask, Plotly Dash, Pandas, SQLAlchemy) · PHP · PostgreSQL · Linux (RHEL/Ubuntu) · KVM/Libvirt · VMware ESXi · OpenStack · Ansible · Ceph  
**Active Lab & Open Source:** Go · KubeVirt / CDI · OpenShift / Kubernetes · OpenTofu · Zarf / Lula (OSCAL)
