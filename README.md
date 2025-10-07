# Ansible Playbook instructions
An Ansible playbook repository that contains playbooks related to agent workstations setup and installations.

### Installation/Uninstallation of Google Chrome
# Install
```
ansible-playbook -i servers --limit <server host> software_install.yml --tags=install_chrome
```
# Uninstall
```
ansible-playbook -i servers --limit <server host> software_install.yml --tags=uninstall_chrome
```

### Installation/Uninstallation of Sogou Pinyin
# Install
```
ansible-playbook -i servers --limit <server host> software_install.yml --tags=install_sogoupinyin
```
# Uninstall
```
ansible-playbook -i servers --limit <server host> software_install.yml --tags=uninstall_sogoupinyin
```

### Installation/Uninstallation of Team Viewer
# Install
```
ansible-playbook -i servers --limit <server host> software_install.yml --tags=install_teamviewer
```
# Uninstall
```
ansible-playbook -i servers --limit <server host> software_install.yml --tags=uninstall_teamviewer
```