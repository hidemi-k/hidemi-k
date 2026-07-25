# Hi there 👋, I'm hidemi-k

### OSS R&D Engineer | Autonomous Networking & Multi-Agent Systems
Building autonomous networking systems. Focused on eBPF, Containerlab PoCs, NETCONF automation, and A2A (Agent-to-Agent) workflows.

---

## 🌐 Autonomous Multi-Vendor Network Automation & A2A Ecosystem

Welcome to the open architecture of the **A2A Protocol**—a multi-agent framework designed for standardized network operations, security, and governance across multi-vendor environments.

## 🧩 A2A Architecture Overview
The A2A ecosystem is structured into three layers:
- Platform Layer
- Vendor Core Layer
- Integration Layer

### 🏛️ Detailed Architecture Map

```mermaid
graph TD

    subgraph Integrations ["Integration Layer - Public / Private"]
        Splunk["a2a-splunk<br> (A2A bridge)"]
    end

    subgraph A2A_Vendor_Cores ["Vendor Core Layer - Public / Private"]
        Ceos["a2a-ceos-core"]
        Junos["a2a-junos-core"]
        IOSXR["a2a-iosxr-core"]
        SRLinux["a2a-srlinux-core"]
    end

    subgraph A2A_Suite ["Platform Layer - Public / Private"]
        Gov["a2a-governance"]
        Contain["a2a-containment-core"]
        SASE["maf-ebpf-sase"]
    end
```
> **Note:** Each layer is designed to expand over time.  
> As the A2A ecosystem evolves, new vendor-specific cores and integration modules will be continuously added.



