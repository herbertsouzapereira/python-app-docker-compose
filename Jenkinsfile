pipeline {
    agent any
    stages{
        stage ('Checking Docker Version'){
            steps{
                sh '''
                    docker --version
                    docker compose version
                    docker info
                    hostnamectl
                '''
            }
        }
    }
}
