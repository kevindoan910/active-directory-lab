# Active Directory Lab in VirtualBox

This lab sets up a simulated enterprise network using Oracle VirtualBox, featuring:
- A **Server 2019** domain controller
- A **Windows 10** domain-joined client
- DHCP, DNS, and NAT configuration
- Automated creation of 1,000 AD users with PowerShell

## 🧰 Tools Used
- Oracle VirtualBox
- Windows Server 2019 ISO
- Windows 10 ISO
- PowerShell

## 🛠️ Lab Tasks
1. **Install VirtualBox**
2. **Create two VMs**:
   - `DC1` (domain controller) with two NICs: one NAT (internet) and one Host-Only (internal)
   - `Client1` with Host-Only adapter only
3. **Install Server 2019** on `DC1` and configure:
   - Static IP for Host-Only NIC
   - Domain services (AD DS)
   - DNS & DHCP roles
   - Routing and Remote Access (RRAS) for NAT
4. **Install Windows 10** on `Client1`
5. **Join `Client1` to the domain**
6. **Use PowerShell to create 1,000 users**

