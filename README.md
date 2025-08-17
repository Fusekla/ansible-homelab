# ansible-homelab

Ansible experiments and practice playbooks for my personal homelab.  
This repository is used for refreshing skills (EX294 renewal prep) and testing Ansible features locally.

---

## 📂 Structure
- `inventories/` — inventory files (e.g., `localhost`).
- `playbooks/` — individual playbooks.
- `roles/` — reusable roles (to be added later).
- `docs/` — notes, progress logs, and references.

---

## 🚀 Quickstart

### Requirements
- [Ansible](https://docs.ansible.com/) installed locally  
  ```bash
  ansible --version
  ```

### Run a playbook

Example with the basic ping play:
```bash
ansible-playbook -i inventories/localhost playbooks/ping.yml
```

See docs/ for more detailed progress logs.

## ⚠️ Disclaimer

This repo is for lab use only. Playbooks may not follow production best practices.