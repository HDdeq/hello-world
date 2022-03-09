pipeline {
    agent any

    stages {
        stage ('Deploy'){
            steps{
                sh '''
                echo "hello"
                git pull https://github.com/HDdeq/hello-world.git
                ls
                cp -r . /home/ubuntu/myapp
                ls /home/ubuntu/myapp && npm run build
                '''
            }
        }
    }
}
