# Basic VLAN Trunking - Cisco Packet Tracer Project

## 📚 Project Overview
This project simulates **VLAN trunking** between two Cisco switches using **Cisco Packet Tracer**. The objective is to allow devices in the same VLAN (but connected to different switches) to communicate through a trunk link.

---

## 🔧 Files in the Repository
| File                    | Description |
|------------------|----------------|
| `basic-trunking.pkt` | Cisco Packet Tracer file with the full topology. |
| `vlan_config.txt` | All configuration commands applied on both switches. |
| `README.md` | Full project documentation. |

---

## 🚀 How to Use
1. Open `basic-trunking.pkt` in Cisco Packet Tracer.
2. Review the `vlan_config.txt` to understand the switch configurations.
3. Use these commands in Packet Tracer to check:
    - `show vlan brief`
    - `show interfaces trunk`
4. Test **ping** between devices in the same VLAN (across the two switches) to confirm successful trunking.
5. The **native VLAN** is set to VLAN 99 to demonstrate how to change the default.

---

## 🛠️ Key Concepts Covered
- Creating VLANs on both switches
- Assigning ports to VLANs
- Configuring **trunk ports** between switches
- Setting and verifying **native VLAN**
- Allowing only specific VLANs on trunk

---

## 📌 Commands Covered
- `vlan` creation and naming
- `switchport mode access`
- `switchport access vlan`
- `switchport mode trunk`
- `switchport trunk native vlan`
- `switchport trunk allowed vlan`
- `show vlan brief`
- `show interfaces trunk`
- `wr` (save config)

---

## 📷 Topology Snapshot
*(You can add a screenshot here if you want)*

---

## ✅ Ideal For
- Networking students
- Beginners learning VLAN trunking
- CCNA preparation

---

## ✨ Author
- **Your Name** (Add your GitHub profile link if you want)
- Created as part of Cisco practical networking studies.

---

