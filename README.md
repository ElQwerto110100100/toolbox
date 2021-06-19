# toolbox
example playbook linux setup run 
ansible-playbook --extra-vars "host=localhost" main.yml
ansible-playbook  --extra-vars "host=1.1.1.1" main.yml -i 1.1.1.1, -kK
ansible-playbook  --extra-vars "host=192.168.0.17" main.yml -i 192.168.0.17, -i ~/.ssh/id_rsa -K
make sure server can be ssh'd into
sudo apt install openssh-server
