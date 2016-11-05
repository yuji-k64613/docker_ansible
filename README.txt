#
# Ansibleインストール
#
git clone git://github.com/ansible/ansible.git --recursive
cd ansible/
source ./hacking/env-setup

#
# Ansible実行
#
ansible-playbook site.yml
