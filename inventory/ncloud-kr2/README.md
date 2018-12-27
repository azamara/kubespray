ncloud-sg1
===


```bash 
$ export LC_ALL="en_US.UTF-8"; export LC_CTYPE="en_US.UTF-8"
$ cd kubespray
$ pip install -r requirements.txt
$ ansible-playbook -i inventory/ncloud-kr2/hosts.ini cluster.yml
```