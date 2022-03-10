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
                systemctl daemon-reload
                systemctl start node-app.service
                systemctl enable node-app.service
                '''
            }
        }
    }
}
