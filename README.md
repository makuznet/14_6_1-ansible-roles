# Ansible roles
> This repo comprises an example of Ansible roles.
Installing vsftpd, changing its conf file via a j2 template and starting a serice.

## Usage
Running Ansible manually:
```bash
ansible-playbook -i terraform-ya/inventory.yml main.yml
```
## Installation
### Ansible (MacOS)
```bash
https://www.python.org/ftp/python/3.9.5/python-3.9.5-macosx10.9.pkg
python get-pip.py
pip install ansible
```
## Acknowledgments
This repo was inspired by [skillfactory.ru](https://skillfactory.ru/devops#syllabus) team

## See also 
- [Ansible Tags](https://docs.ansible.com/ansible/latest/user_guide/playbooks_tags.html#selectively-running-tagged-tasks-in-re-usable-files)

## License
Follow all involved parties licenses terms and conditions.