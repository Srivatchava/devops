pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                git 'https://github.com/Srivatchava/devops_lab2.git'
                bat 'echo checkout succues'
            }
        }
        stage('build'){
            steps{
                 bat 'echo build success'
            }
            
        }
        stage('deploy'){
            steps{
                bat 'echo deployple'
            }
        }
    }
}