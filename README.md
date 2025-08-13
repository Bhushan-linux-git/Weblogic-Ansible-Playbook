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

2. Update inventory
Edit inventory/hosts.yml with your server names.

3. Apply patches
ansible-playbook -i inventory/hosts.yml playbooks/apply_patches.yml

4. Start Admin Servers
ansible-playbook -i inventory/hosts.yml playbooks/start_admin_servers.yml


