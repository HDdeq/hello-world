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
                sh '''
                ls
                pwd
                '''
            }
        }
    }
}
