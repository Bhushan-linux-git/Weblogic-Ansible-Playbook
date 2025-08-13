# WebLogic Patch Automation

Ansible playbooks to automate:
- Applying OPatch and binary patches
- Storing patch logs
- Starting Admin Servers

## Prerequisites
- Ansible 2.9+
- WebLogic installed on target servers
- SSH access to target servers

## Playbooks
- `apply_patches.yml` – Apply WebLogic patches and store logs
- `start_admin_servers.yml` – Start Admin Servers if not running

