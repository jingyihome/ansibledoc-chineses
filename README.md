# Ansible官方文档中文版

##官方原文档:

[https://docs.ansible.com/ansible/index.html](https://docs.ansible.com/ansible/index.html)

##原项目地址:

[https://github.com/stanleylst/ansible-tran/](https://github.com/stanleylst/ansible-tran/)

##Build the documentation(Ubuntu OS)
sudo apt-get -y install make

##安装python2.7
sudo apt-get -y install python2.7

##安装pip
sudo apt-get -y install python-pip python-dev dos2unix

##Install sphinx and theme
pip install sphinx==1.4.8 sphinx_rtd_theme

##Build
https://github.com/jingyihome/ansibledoc-chineses.git
cd ansibledoc-chineses
make html
