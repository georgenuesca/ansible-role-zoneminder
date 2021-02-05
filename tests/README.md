ansible-playbook  -i ansible_role_linux_server/tests/hosts  ansible_role_linux_server/tests/site.yml  -t packages


ansible-playbook  -b -K --become-method su  -i ansible_role_linux_server/tests/hosts  ansible_role_linux_server/tests/site.yml  -t packages
ansible-playbook  -b -K -i ansible_role_linux_server/tests/inventory  ansible_role_linux_server/tests/site.yml  -t packages


ansible-playbook  -i ansible_role_linux_server/tests/inventory  ansible_role_linux_server/tests/site.yml  -t nvidia
