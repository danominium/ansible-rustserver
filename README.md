# SETUP
```bash
dnf install git-core ansible-core
git clone git@github.com:user/repo_name.git
cd repo_name
cp hosts.example hosts
# edit hosts, roles/lgsm_rustserver/files/
ansible-playbook rustserver.yaml
```
