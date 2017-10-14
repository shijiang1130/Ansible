share for everyone

CentOS-7-x86_64-NetInstall-1611.iso
http://mirrors.163.com/centos/7/os/x86_64/

git clone https://github.com/ansible/ansible

cd ansible
yum install python-dev
python setup.py install
ansible-doc -l

ansilbe all --list-hosts
