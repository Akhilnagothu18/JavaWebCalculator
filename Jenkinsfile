pipeline{
	agent { label 'node1' }
    stages {
	    stage("Ansible-deploy"){
            steps{
		 
                 echo 'Ansibleplaybook'
		 sh 'pwd'
	         sh 'ansible-playbook tomcat_ansible.yml'
            }
        }
       
        }
}
