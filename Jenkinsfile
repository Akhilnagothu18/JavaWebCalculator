pipeline{
    agent none
    stages {
        stage("Ansible-deploy"){
	  agent { label 'node1' }
            steps{
		 dir('deployment')
                  echo 'Ansibleplaybook'
	          sh 'ansible-playbook tomcat_install_ansible.yml'
            }
        }
       
        }
}
