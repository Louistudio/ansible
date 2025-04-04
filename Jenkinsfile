pipeline{
    agent {
        label 'ansible'
    }
    stages{
        stage('check'){
            steps{
                sh 'whoami'
            }
        }
        stage('ansible'){
            steps{
                sh 'ansible-playbook role_test.yaml'
            }
        }
        /*stage('github'){
            steps{
                git 
                    branch: 'main'
                    url: 'git@github.com:Louistudio/ansible.git'
            }

        }
        }*/
    }
}