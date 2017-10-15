share for everyone

CentOS-7-x86_64-NetInstall-1611.iso
http://mirrors.163.com/centos/7/os/x86_64/

$ wget http://mirrors.163.com/.help/CentOS7-Base-163.repo 

$ mv CentOS7-Base-163.repo CentOS7-Base.repo 

$ yum clean all 

$ yum makecache

#git clone https://github.com/ansible/ansible

#cd ansible

#yum install python-dev

#python setup.py install

ansible-doc -l

ansilbe all --list-hosts
