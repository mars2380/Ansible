### Install SSH Keys for admin accounts
	
	ansible-playbook -i hosts -u ubuntu -l tag_environment_server01 developeraccounts.yml

### Trouble Shooting

Ping all the EC2 instances

    ansible -i hosts -u ubuntu all -m ping
