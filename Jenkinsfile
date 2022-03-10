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
                sudo systemctl daemon-reload
                sudo systemctl start node-app.service
                sudo systemctl enable node-app.service
                '''
            }
        }
    }
}
