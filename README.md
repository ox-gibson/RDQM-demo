# rdqm

This will be a project for installing rdqm using ansible

1. Install ansible to all servers
2. Update hosts file with correct host names/ip addresses
3. Copy hosts file to all servers

Syntax:
To install: ansible-playbook provisionRDQM.yanl -e varHosts=servers
To uninstall: ansible-playbook uninstallRDQM.yaml -e varHosts=servers
