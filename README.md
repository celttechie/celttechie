# Brian Jarrett
### Solutions Architecture & Technical Leadership | Systems Automation, Robotics Design & Subsystem Testing

<p align="left">
  <a href="https://celttechie.github.io/"><img src="https://img.shields.io/badge/Portfolio-celttechie.github.io-0284c7?style=flat-square&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/bjarrett"><img src="https://img.shields.io/badge/LinkedIn-bjarrett-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://celttechie.github.io/articles/technical_execution_and_rapid_learning/"><img src="https://img.shields.io/badge/Article-Rapid%20Learning%20&%20Execution-4f46e5?style=flat-square&logo=markdown&logoColor=white" alt="Technical Execution" /></a>
  <a href="https://celttechie.github.io/articles/from_bare_metal_to_vllm_openshift_ai/"><img src="https://img.shields.io/badge/Deep%20Dive-Bare%20Metal%20to%20vLLM-e11d48?style=flat-square&logo=readme&logoColor=white" alt="Bare Metal to vLLM" /></a>
</p>

<p align="left">
  <a href="https://github.com/celttechie/FROGlib"><img src="https://img.shields.io/badge/FROGlib-Swerve%20Kinematics%20&%20Vision-22c55e?style=flat-square&logo=python&logoColor=white" alt="FROGlib" /></a>
  <a href="https://github.com/celttechie/openshift-ai-infrastructure"><img src="https://img.shields.io/badge/OpenShift%20AI-Bare%20Metal%20VFIO%20%7C%20vLLM-ee0000?style=flat-square&logo=redhatopenshift&logoColor=white" alt="OpenShift AI" /></a>
  <a href="https://github.com/celttechie/tactical-edge-gateway"><img src="https://img.shields.io/badge/Tactical%20Gateway-MAVLink%20%2F%20ROS2%20→%20TAK%20CoT-f59e0b?style=flat-square&logo=ros&logoColor=white" alt="Tactical Gateway" /></a>
  <a href="https://github.com/celttechie/openshift-sno-lab"><img src="https://img.shields.io/badge/SNO%20Substrate-OpenTofu%20%7C%20%3C10ms%20etcd-6366f1?style=flat-square&logo=opentofu&logoColor=white" alt="SNO Lab" /></a>
  <a href="https://github.com/celttechie/tactical-edge-sdn"><img src="https://img.shields.io/badge/Tactical%20SDN-Netlink%20Dynamic%20Routing-0284c7?style=flat-square&logo=linux&logoColor=black" alt="Tactical SDN" /></a>
  <a href="https://github.com/celttechie/zarf-uds-lula-datalakehouse"><img src="https://img.shields.io/badge/cATO-Lula%20(OSCAL)%20%7C%20Zarf-10b981?style=flat-square" alt="Compliance as Code" /></a>
</p>

---

### 🔭 The Core Differentiator: Mastering Unfamiliar Technology

I am a hands-on Systems Architect and Technical Leader with a 30-year foundation spanning enterprise compute, Linux systems administration, and federal compliance, alongside **over a decade designing competitive robotic systems and authoring real-time Python software controlling swerve drive kinematics, articulated mechanisms, and vision targeting**.

My defining strength is the ability to **step into unfamiliar technologies, deconstruct them from first principles, and rapidly turn complex problems into reliable, working solutions**—whether that means fabricating and wiring a real-time embedded robot, defending a 6,000-node federal ATO, or standing up sovereign AI infrastructure from bare metal.

> *"Understand deeply from the ground up, approach platforms with rigorous testing and automation discipline, and turn unfamiliar complexity into clean, deterministic execution."*

---

### 🤖 Robotics Design, Mechanism Automation & Subsystem Testing (2016 – Present)

A decade-long proof point of mastering unfamiliar domains across both physical hardware and real-time software:

* **End-to-End System Design & Mechanism Automation:** 10+ years mentoring and engineering in FIRST Robotics (Team 3160). Designing complete mechanical, pneumatic, and electrical subsystems, CAN bus architectures, sensor integration, and high-torque motor control loops.
* **Production Python Software:** Authored robot control architectures in Python (RobotPy, NumPy), implementing swerve drive kinematics, closed-loop PID control, state machines, and camera-based computer vision (AprilTag fiducials and machine learning object detection).
* **Hardware-in-the-Loop (HIL) Subsystem Testing:** Executed hardware-in-the-loop (HIL) testing on physical robot subsystems (actuators, motor controllers, and sensor arrays) to validate edge software behavior and control loops before full robot integration.
* **Open-Source Modularity ([`FROGlib`](https://github.com/celttechie/FROGlib)):** Created and maintain an installable Python hardware abstraction library (`pyproject.toml`) that modularizes swerve kinematics, motor controller wrappers, and vision targeting across competition seasons.
* **High-Pressure Tournament Diagnostics:** Rapid, methodical root-cause debugging under tight tournament timeframes—isolating complex electrical noise, CAN bus faults, sensor drift, and code regressions in minutes.

---

### 🧪 Applied Research & Rapid Learning (The Innovation Lab)

> [!NOTE]
> The projects below represent intensive hands-on research and prototyping undertaken over the past several months. Rather than claiming decades of specialization in AI or Kubernetes, these labs demonstrate **how quickly I can enter an unfamiliar technology ecosystem, evaluate its core mechanics, author Architecture Decision Records (ADRs), and build verifiable, production-style reference platforms.**

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🧠 <a href="https://github.com/celttechie/openshift-ai-infrastructure">openshift-ai-infrastructure</a></h3>
      <p><b>Applied research exploring bare-metal GPU acceleration & Kubernetes AI serving.</b></p>
      <ul>
        <li><b>Hardware to Pod:</b> Prototyped PCIe VFIO driver binding and IOMMU group isolation on bare-metal workstations.</li>
        <li><b>Operator & Serving:</b> Deployed NVIDIA GPU Operator via CRI-O Container Device Interface (CDI) and benchmarked vLLM serving (PagedAttention, continuous batching).</li>
        <li><b>SRE & Diagnostics:</b> Formulated Day-2 failure runbooks (PCIe bus reset, node drain) and DCGM/Prometheus alerting for KV-cache saturation.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Research_Lab-AI_Infra-3B82F6?style=flat-square" />
        <img src="https://img.shields.io/badge/OpenShift-EE0000?style=flat-square&logo=redhatopenshift&logoColor=white" />
        <img src="https://img.shields.io/badge/vLLM-3B82F6?style=flat-square" />
        <img src="https://img.shields.io/badge/NVIDIA_CDI-76B900?style=flat-square&logo=nvidia&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/celttechie/tactical-edge-gateway">tactical-edge-gateway</a></h3>
      <p><b>Prototyping air-gapped telemetry translation and situational awareness.</b></p>
      <ul>
        <li><b>Protocol Bridging:</b> Bridged autonomous robotics telemetry (<b>MAVLink & ROS2/DDS</b>) to military C2 (<b>Cursor on Target / TAK Server</b>) over simulated contested links.</li>
        <li><b>Air-Gapped Delivery:</b> Packaged services as zero-dependency <b>Defense Unicorns Zarf</b> OCI bundles.</li>
        <li><b>Compliance-as-Code:</b> Evaluated continuous automated compliance validation against NIST SP 800-53 controls using <b>Lula (OSCAL)</b>.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Research_Lab-Edge_Tactical-10B981?style=flat-square" />
        <img src="https://img.shields.io/badge/Zarf-0F172A?style=flat-square" />
        <img src="https://img.shields.io/badge/Lula_OSCAL-10B981?style=flat-square" />
        <img src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white" />
        <img src="https://img.shields.io/badge/TAK_CoT-F59E0B?style=flat-square" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>☸️ <a href="https://github.com/celttechie/openshift-sno-lab">openshift-sno-lab</a></h3>
      <p><b>Automated platform substrate deploying Single Node OpenShift (SNO 4.16+).</b></p>
      <ul>
        <li><b>Declarative IaC:</b> Engineered reproducible SNO provisioning via <b>OpenTofu</b> on KVM/libvirt with deterministic Ed25519 key pinning.</li>
        <li><b>Storage Performance:</b> Isolated bridge network with HAProxy ingress; tuned NVMe PCIe storage pools to guarantee sub-10ms etcd fsync latency.</li>
        <li><b>Kernel Tuning:</b> Authored declarative RHCOS MachineConfigs for boot-time 1GB HugePages and kernel IOMMU passthrough.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/OpenTofu-FFDA63?style=flat-square&logo=opentofu&logoColor=black" />
        <img src="https://img.shields.io/badge/KVM%2FLibvirt-F1502F?style=flat-square" />
        <img src="https://img.shields.io/badge/RHCOS-EE0000?style=flat-square&logo=redhat&logoColor=white" />
        <img src="https://img.shields.io/badge/HAProxy-00A4E4?style=flat-square&logo=haproxy&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📡 <a href="https://github.com/celttechie/tactical-edge-sdn">tactical-edge-sdn</a></h3>
      <p><b>Exploring dynamic routing & software-defined networking for contested environments.</b></p>
      <ul>
        <li><b>Dynamic Route Evaluation:</b> Prototyped a Python/C++ SD-WAN controller that monitors latency and packet loss across simulated radio links.</li>
        <li><b>Kernel Manipulation:</b> Tested hitless route mutation directly via Linux Netlink sockets with zero dropped active sessions.</li>
        <li><b>Modern Edge Stack:</b> Containerized FRRouting (BGP/OSPF), WireGuard tunnels, and Zarf packaging for edge deployment.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Linux_Netlink-FCC624?style=flat-square&logo=linux&logoColor=black" />
        <img src="https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white" />
        <img src="https://img.shields.io/badge/FRRouting-00599C?style=flat-square" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🔒 <a href="https://github.com/celttechie/talos-k8s-platform">talos-k8s-platform</a></h3>
      <p><b>Evaluating declarative, immutable Kubernetes on bare metal.</b></p>
      <ul>
        <li><b>Immutability:</b> Explored Talos Linux API-managed OS with read-only rootfs and zero-SSH host access to eliminate configuration drift.</li>
        <li><b>eBPF Networking:</b> Implemented <b>Cilium eBPF</b> socket routing, network security policies, and L2 BGP load balancing.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Talos_Linux-1E293B?style=flat-square" />
        <img src="https://img.shields.io/badge/Cilium_eBPF-F46800?style=flat-square&logo=cilium&logoColor=white" />
        <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>📦 <a href="https://github.com/celttechie/zarf-uds-lula-datalakehouse">zarf-uds-lula-datalakehouse</a></h3>
      <p><b>Prototyping air-gapped delivery & continuous compliance (cATO).</b></p>
      <ul>
        <li><b>Air-Gapped Enclaves:</b> Evaluated Defense Unicorns UDS for packaging complex data platform workloads into disconnected environments.</li>
        <li><b>Compliance Validation:</b> Tested continuous OSCAL mapping to validate live cluster state directly against NIST SP 800-53 controls.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Defense_Unicorns-111827?style=flat-square" />
        <img src="https://img.shields.io/badge/Air--Gapped-059669?style=flat-square" />
        <img src="https://img.shields.io/badge/OSCAL-6366F1?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### 🏛️ 30-Year Enterprise Systems Foundation

- **Enterprise FedRAMP ATO Governance (Cisco Systems):** Directed technical response defending HHS PMO FedRAMP Moderate Authorization to Operate across 6,000+ nodes during enterprise zero-day incidents (Log4j).
- **Vulnerability Data Platform Architecture:** Architected custom PostgreSQL, FastAPI, and Tableau data pipelines to automate compliance extraction across heterogeneous fleets, replacing manual audits.
- **Enterprise Compute & Linux:** Decades administering enterprise compute (Cisco UCS, x86 bare-metal), virtualization (KVM/Libvirt, ESXi), configuration management (Ansible, SaltStack), and identity (FreeIPA/HBAC).
- **QA Department Leadership & Systems Integration (StorageSoft / Phoenix Tech):** Managed QA testing and technical support departments, designed heterogeneous multi-platform test labs, and acted as systems integration engineer ensuring interoperability with enterprise suites (Microsoft SMS, CA Unicenter).
- **Foundational Systems Engineering:** Rooted in airborne radar systems maintenance in the U.S. Air Force (AWACS), low-level disk diagnostic engineering, and mission-critical uptime.

---

### 🛠️ Capabilities & Technical Toolchain

```
Robotics Design & Subsystem Testing (2016 – Present)
────────────────────────────────────────────────────────────────────────────────
Control & Software       ── Python (RobotPy, NumPy) • FROGlib Kinematics • Mechanism Automation • PID Loops • HIL Testing
Vision & Sensors         ── AprilTag Vision • ML Object Detection Models • IMU Sensor Fusion • CAN Bus Networks • Pneumatics
Mechanical & Electrical  ── Swerve Drive Kinematics • Motor Controllers • Circuit Wiring • Rapid Failure Isolation

Enterprise Foundation (30 Years)
────────────────────────────────────────────────────────────────────────────────
Systems Engineering      ── Bare-Metal Compute • Linux Systems Administration (RHEL, Ubuntu) • KVM/Libvirt • Cisco UCS
DevSecOps & Compliance   ── FedRAMP Moderate Governance • DISA STIG Automation • Qualys API • FreeIPA / HBAC
Automation & Data        ── Python (FastAPI, Pandas, SQLAlchemy) • PostgreSQL • Bash Automation • Ansible • SaltStack
Methodology & Quality    ── Systems Architecture • Root-Cause Diagnostics • Failure Mode Analysis • QA Automation • Team Leadership

Applied R&D & Rapid Technology Immersion (Recent Research)
────────────────────────────────────────────────────────────────────────────────
Cloud-Native Substrates  ── OpenShift (SNO 4.16+) • Talos Linux • Kubernetes • OpenTofu • Cilium (eBPF)
Air-Gapped & Sovereign   ── Defense Unicorns Zarf • UDS Bundles • Lula (OSCAL Continuous Compliance)
AI Workload Exploration  ── NVIDIA GPU Operator (CDI) • VFIO Passthrough • vLLM Inference Serving • LiteLLM
Edge SDN & Telemetry     ── Netlink Dynamic Routing • WireGuard • FRRouting • MAVLink • ROS2 / DDS • Low-SWaP (OrangePi 5)
```

---

<p align="center">
  <b>Explore architecture deep dives, verified milestone matrices, and comprehensive resume:</b><br/>
  <a href="https://celttechie.github.io/"><b>celttechie.github.io</b></a> • 
  <a href="https://www.linkedin.com/in/bjarrett"><b>LinkedIn</b></a>
</p>
