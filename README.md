# Ansible CIS Hardening for RHEL 9

A modular, idempotent Ansible playbook and role that automates CIS-style security hardening on Red Hat Enterprise Linux 9. Run it once to remediate drift, or schedule it in CI/CD for continuous compliance.

---

## 🚀 Project Overview

- **What this Ansible playbook does**  
  - Applies Center for Internet Security (CIS) Benchmark controls for RHEL 9.
  - Hardens SSH, firewalld, SELinux, and more via Ansible tasks.
  - Reports each task as **`ok`** (already compliant) or **`changed`** (remediation applied).

- **Why it matters**  
  - Shrinks attack surface by enforcing best practices.
  - Saves time over manual configuration or brittle shell scripts.
  - Provides instant visibility into your security posture.

---

## 📋 Prerequisites

1. **Target system**: RHEL 9 (physical, VM, or container)  
2. **Ansible**: Version ≥ 2.10 installed on the control node  
3. **Sudo access**: Your Ansible user must be able to `become: yes`  
4. **SSH or local connection**: Accessible via SSH key or `ansible_connection=local`

---


