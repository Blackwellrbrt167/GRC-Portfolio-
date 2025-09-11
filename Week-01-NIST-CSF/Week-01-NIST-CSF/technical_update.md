# CVE-2025-22224 – VMware Workstation/Fusion TOCTOU Vulnerability

**Summary:**  
A time-of-check-to-time-of-use (TOCTOU) vulnerability in VMware Workstation and Fusion allows an attacker with admin privileges in a guest VM to execute code on the host. This results in a sandbox escape and potential full compromise of the underlying system.

**Impact:**  
- Attacker can move from virtual machine to host.  
- Breaks isolation boundaries in virtualization software.  
- Could be chained with other exploits for persistence or lateral movement.  

**Severity:** CVSS 8.0 (High)  
**Affected Products:** VMware Workstation Pro, VMware Fusion (various versions prior to patch).  

