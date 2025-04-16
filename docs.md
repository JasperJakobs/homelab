

Nginx Proxy manager:

Install:
    ansible-playbook ./ansible/playbooks/proxy/install.yml -i ./ansible/inventory.yml --ask-vault-pass -e "tailscale_authkey=%AUTHKEY%"

Sync:
    ansible-playbook ./ansible/playbooks/proxy/sync.yml -i ./ansible/inventory.yml --ask-vault-pass
