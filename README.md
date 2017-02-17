# ansible_roles
Repository that contains Ansible roles to use them independently

### httpd rol: Install Apache web server in CentOS/Ubuntu
- Config file in *roles/httpd/templates/httpd.j2*. Configure previously var **listen_port** in *roles/httpd/vars/main.yml* (80 by default)
- Replace default web and use index.html, which is in *roles/httpd/files/index.html*
