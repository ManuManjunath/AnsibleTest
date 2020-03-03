# AnsibleTest

Testing simple playbooks - 

### To install ###
Debian system --     `$ sudo apt-get install ansible`

Centos system --     `$ sudo yum install epel-release` and `$ sudo yum install ansible`

Using PIP  --        `$ sudo pip install ansible`


Next steps - test with module parametrers, include, register, tempates, when condition

To run - 
`absible-playbook playbooks/sample.yml`

To run a single module without playbook - 
`ansible <server> -i <inventory_file> -u <user> -m <module> -k <prompt for password> -v`

i --> inventory file, m --> module, u --> username, k --> prompt for password, v --> verbose debug (vv / vvv --> debug level 2/3)
