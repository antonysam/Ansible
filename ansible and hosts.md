Create a folder name ANSIBLE and keep ansible.cfg and hosts

# ansible
```
[defaults]
inventory = ./hosts
deprecation_warnings = False
private_key_file = ~/.ssh/ansible.pem
host_key_checking = False
retry_files_enabled = False
```
# hosts
```
[webservers]
webserver1-RedHat ansible_host=<"Private IP"> ansible_user=<"username">
```
