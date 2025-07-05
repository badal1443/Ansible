# Docs
[ansible.readthedocs](https://ansible.readthedocs.io/projects/navigator/settings/)

# Config file order of precedence

## For Ansible file on controller nodes

## For Ansible navigator

# Some of the usefl commands
- Version of ansible:  
  `ansible --version`
  | 
- Version of ansible navigator
  `ansible-navigator --version`
- Ccheck config dump of ansible-navigator and look for HOST_LIST directive.
  `ansible-navigator config dump -m stdout'
- Run ansible playbook using ansible navigator non-interatively.
  `ansible-navigator run -m stdout <playbook.yml>

#Best Practices
  - Simplicity
  - Non Ambigous
