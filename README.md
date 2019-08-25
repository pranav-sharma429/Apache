# Apache configuration using Ansible Playbooks

1. Set the rules for apache and iptables
2. Manages and install required packages and dependencies
3. Sets OS specific variables
4. Ensures all packages are installed and services are running and enables them at boot
5. Deploys required files and templates to web server
6. Set SSL engine and required properties for openssl and mod_ssl
7. Creates a  virtualhost on webserver and adds configuration using jinja template
8. Customizes the Webpage with extra variable marquee line.


Steps:

```
git clone https://github.com/pranav-sharma429/Apache.git
```

```
cd Apache
```

```
ansible-playbook -i hosts --extra-vars "ans=Welcome to my Jungle"
```


