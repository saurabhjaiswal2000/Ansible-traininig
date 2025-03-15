{ Establish Connection to remote Clients }

#####{ Populate the hosts file with IP or FQDN for out clients:}#####
    [labclients] = For grouping 
    192.168.191.137

#####{ Generate SSH keys on the control node and copy over to clients for password less SSH connections}##
* ssh-keygen
*  leave everthing default and enter
*  ssh-copy-id 192.168.191.137
*  sh-copy-id 192.168.191.135
    
####{ Now SSH into the clients to test }###
* ssh 192.168.191.137
