Pre
 - ansible
 - python (elasticserch host)
 - ssl ceritftate 
 
 1. clone the repo
  
  git clone https://github.com/rameshkalirawana/task1.git
  
 then put server details in the inventory.yaml and also update the ssl ceritfacte 
 
then downlod the elasticserch role throguh ansible galaxy

 ansible-galaxy install elastic.elasticsearch,v7.10.1
 
ansible-playbook main.yaml -i inventory.yaml

More customize and other details 

https://github.com/elastic/ansible-elasticsearch
