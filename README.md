# nginx-auto-ssl
Ansible script to that configures remote client for SSL and dynamically creates certificate based on hostname

* This ansible package has been modified as a collection of roles with tags to increase efficiency
* Roles can currently be executed using the following command:
* ansible-playbook -v playbook1 -t run_playbook
* custom tags:
* - install_powershell  (Installs ps on the ansible controller; will use for added features)
  - remove_powershell
  - install_nginx_ssl
  - remove_nginx_ssl
