pipeline {
    agent any

    stages {
        stage ('Build'){
            steps{
                sh '''
                git pull https://github.com/HDdeq/hello-world.git
                ls
                pwd
                '''
            }
        }
        stage ('Deploy'){
            steps{
                sh '''
                systemctl start node-app.service
                '''
            }
        }
    }
}
