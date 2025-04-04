pipeline{
    agent {
        label 'ansible'
    }
    stages{
        /*stage('git checkout'){
            steps{
                git branch: 'main'
                url: 'git@github.com:Louistudio/ansible.git'
            }
        }*/
        stage('check'){
            steps{
                sh 'whoami'
            }
        stage('github'){
            steps{
                git branch: 'main'
                url: 'git@github.com:Louistudio/ansible.git'
            }

        }
        }
    }
}