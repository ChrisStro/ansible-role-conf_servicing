# Ansible Role: conf_servicing

Ansible role for initial configuration of machines managed by Ansible

## Role Variables

For available variables see `defaults/main.yml`
```yaml
conf_servicing_service_user_name: ansible

# If you wish to create additionaly sudo accounts
conf_servicing_sudo_accounts:
  - name: sudo1
    pwd: password-for-sudo2 # Pls encrypt !!!
    ssh_key_public: https://github.com/GITHUBUSER.keys
  - name: sudo2
    pwd: password-for-sudo2
    ssh_key_public: ssh-rsa AAAA....
```
