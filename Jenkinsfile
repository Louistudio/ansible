pipeline{
    agent ansible
    stages{
        stage('git checkout'){
            steps{
                git branch: 'main'
                url: 'git@github.com:Louistudio/ansible.git'
            }
        }
        stage{
            steps{
                sh 'whoami'
            }
        }
    }
}