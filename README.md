# Ansible-traininig

Ansible required python3 package for running it.

Benefits of Ansible
* Agentless
* Open-source
* Avoid human errors
* saves time by automating repetitive or tedious tasks
* Increase productivity
* Easy to use
* Simple (human readable text files)
* Flexible
* Secure(over SSH)
* Provide pre-written modules
* Easy to learn
* Great product for Orchestration
* Ansible can be used not only for systems but also for networks, storage, cloud etc.
* Provide approx. 1300 modules out of the box and about 4000 modules on galaxy
* Huge online Ansible resources

#######################{ Terminologies in Ansible }####################
* Control node or Ansible server: server which runs Ansible application
* Modules: it is a command meant to be executed on the client-side
* Task: Task is a section that consists of single procedure to be completed. A task can have multiple modules.
* Playbook: Automation file with step-by-step execution of multiple tasks
* YAML: A Playbook written in YAML language
* Inventory: File that has information about remote clients where tasks are executed
* Tag: A references or alias to a specific task
* Variable: Variables are like containers that holds the defined value which can be used repetitively
* Role: Splitting of playbook into smaller groups. Roles let us automatically load related vars, files, tasks, handlers and other ansible 
  artifacts based on a known file structure. After we group our content in roles, we can easily reuse them and share them with other users.

#####################{ Ansible Configuration files }####################
* /etc/ansible/ansible.cfg
* /etc/ansible/hosts
* /etc/ansible/roles

#####################{ Ansible installation on ubuntu }################
* sudo apt update
* sudo apt install software-properties-common
* sudo add-apt-repository --yes --update ppa:ansible/ansible
* sudo apt install ansible ansible-doc

####################{ To run ansible playbook }##################
* ansible-playbook "exact playbook location" 


