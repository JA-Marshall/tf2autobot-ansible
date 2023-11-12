# tf2autobot-ansible
An ansible scirpt I wrote for installing and running tf2autobot.

Useful because it lets you hop between different cloud providers using their free tiers with little effort :D 

Configure the hosts file using the server ip you want to connect to, the user on the server you've set up and the path on your local machine to your ecosystem.json file.

Then run the playbook with 

ansible-playbook -i hosts install_autobot.yaml

It will install tf2autobot and start running it. 



