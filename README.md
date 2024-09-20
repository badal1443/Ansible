# Ansible
Craeting playbooks and other learning resources on Ansible.

### Ansible is a configuration management tool, Has a center place in Devops. Ansible consists of Playbooks.

Ansible Playbook has plays, within those plays are tasks to be performed which has 1 or more modules. There are more components like Handler and notify.

## Installation of Ansible on Ubuntu
>> $ sudo apt update

>> $ sudo apt install software-properties-common

>> $ sudo apt-add-repository --yes --update ppa:ansible/ansible

>> $ sudo apt install ansible

[check this webpage](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)


# Steps to Run the Playbook
** Install the Azure Collection: Ensure you have the azure.azcollection installed. You can install it using:
ansible-galaxy collection install azure.azcollection

Set Up Azure Credentials: Make sure your Azure credentials are set up. You can authenticate using environment variables or a credentials file. For example, using environment variables:
export AZURE_SUBSCRIPTION_ID=<your_subscription_id>
export AZURE_CLIENT_ID=<your_client_id>
export AZURE_SECRET=<your_secret>
export AZURE_TENANT=<your_tenant_id>

Run the Playbook: Execute the playbook with the following command:
ansible-playbook create_functionapp.yml
