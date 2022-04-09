# Ansible playbook for setting up my Raspberry Pi fleet

Run the playbook:

    ansible-playbook -i hosts.ini -e "@secrets.yml" site.yml
