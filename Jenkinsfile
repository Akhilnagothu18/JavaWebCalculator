pipeline{
    agent none
    stages {
        stage("Ansible-deploy"){
	  agent { label 'node1' }
            steps{
		 
                 echo 'Ansibleplaybook'
	          ansiblePlaybook become: true, installation: 'ansible', inventory: 'hosts', playbook: 'tomcat_install_ansible.yml'
            }
        }
       
        }
}
