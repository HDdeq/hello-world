pipeline {
    agent any

    stages {
        stage ('Deploy'){
            steps{
                sh 'systemctl start node-app.service'
            }
        }
    }
}