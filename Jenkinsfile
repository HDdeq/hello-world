pipeline {
    agent any

    stages {
        stage ('Commit'){
            steps{
                 git scm
            }
        }
        stage ('Deploy'){
            steps{
                sh 'ls'
                sh 'systemctl start node-app.service'
            }
        }
    }
}