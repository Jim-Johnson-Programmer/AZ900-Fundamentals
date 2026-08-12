**Azure NSG (Network Security Group)** is one of the core security controls in Azure, used to **allow or deny network traffic** to resources inside a **Virtual Network (VNet)**. It acts like a lightweight, distributed firewall at the **subnet** or **network interface (NIC)** level.

---

### ⭐ **What an Azure NSG Does**

An NSG filters **inbound** and **outbound** traffic using security rules.  
Each rule defines:

- Source
- Destination
- Port
- Protocol
- Priority

Traffic is allowed or denied based on these rules. Lower priority numbers are evaluated first. Once a rule matches, processing stops. [Microsoft Learn](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview)

---

### 🔧 **Where You Can Apply an NSG**

You can attach an NSG to:

- **Subnets**
- **Network interfaces (NICs)** on VMs

You can reuse the same NSG across multiple subnets or NICs. [Microsoft Learn](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-group-how-it-works)

---

### 🔄 **How Azure Processes NSG Rules**

Azure evaluates NSGs in a specific order:

1. **Inbound traffic:**
   - Subnet NSG → NIC NSG
2. **Outbound traffic:**
   - NIC NSG → Subnet NSG
3. **Intra‑subnet traffic:**
   - Same order as inbound (Subnet NSG first)

Example:  
If a VM has an NSG on both its subnet and NIC, **both must allow the traffic** for it to pass. [Microsoft Learn](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-group-how-it-works)

---

### 📦 **Default Rules**

Azure includes built‑in rules such as:

- Allow VNet inbound/outbound
- Allow Azure Load Balancer inbound
- Deny all inbound
- Deny all outbound

These defaults have **lowest priority**, so your custom rules override them. [Microsoft Learn](https://learn.microsoft.com/en-us/azure/virtual-network/network-security-groups-overview)

---

### 🧩 **Related Concepts**

- **Application Security Groups (ASGs):**  
  Logical groups of NICs you can reference in NSG rules instead of IPs — useful for scaling environments. [Microsoft Learn](https://learn.microsoft.com/en-us/azure/networking/design-guide/network-application-security-groups)

- **Service Tags:**  
  Predefined labels for Azure services (e.g., `Storage`, `AzureCloud`) so you don’t need to maintain IP ranges manually. [Microsoft Learn](https://learn.microsoft.com/en-us/azure/networking/design-guide/network-application-security-groups)

---

### 🛡️ **When to Use NSGs**

Use NSGs when you need:

- Subnet‑level or VM‑level traffic control
- Basic segmentation inside a VNet
- Lightweight firewalling without deploying Azure Firewall

They are essential for almost any workload running inside a VNet.

---

If you want, I can also show:

- A sample NSG rule set
- How NSGs appear on the AZ‑900 exam
- How NSGs compare to Azure Firewall and NVA firewalls
