pipeline{
    agent none
    stages {
        agent { label 'node1' }
        stage("Ansible-deploy"){
            steps{
			   echo 'Ansibleplaybook'
			   sh 'ansible-playbook tomcat_install_ansible.yml'
            }
        }
       
        }
}
