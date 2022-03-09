pipeline {
    agent any

    stages {
        stage ('Deploy'){
            steps{
                sh '''
                echo "hello"
                git pull https://github.com/HDdeq/hello-world.git
                ls
                npm run build
                pwd
                '''
            }
        }
    }
}
