pipeline{
    agent any
    stages{
        stage('checkout'){
            steps{
                git 'https://github.com/Srivatchava/devops.git'
                bat ' echo chekcout git'
            }
        }
        stage('build'){
            steps{
                bat 'echo building '
            }
        }
        stage('deop'){
            steps{
                bat 'echo depl '
            }
        }
    }
}