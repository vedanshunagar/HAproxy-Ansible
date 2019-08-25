# HAproxy-Ansible
Download this role and deploy haproxy on all the servers


######  to use this roles you just have to follow the following steps:  #########

1. download this folder in zip format and extract it

2. upload this folder on your ansile controller node

3. there is a file named "inventory", open this file using vim or vi etc

4. there is 2 type of groups : first is for web server deployment named [web] group
                               second is for haproxy deployment name [lb]
   put all the ip addresses where you want to setup webserver in [web] group and put all the ip addresses where you want to setup haproxy    server in [lb] group
   
5. just it, now run site.yml file
   # ansible-playbook  site.yml
   
   #####################
