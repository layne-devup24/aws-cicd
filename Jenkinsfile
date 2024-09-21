pipeline {
    agent any
    
    stages {
        stage('git checkout'){
            steps{
                git branch: 'main', url: 'https://github.com/layne-devup24/aws-cicd.git'
            }
        }
        stage('test'){
            steps{
                sh 'echo test'
            }
        }
    }
}