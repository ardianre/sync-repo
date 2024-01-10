pipeline {
    agent any

    stages {
        stage('Stage A') {
            steps{
                sh "We can do a lot here"
            }
        }
        stage('Stage B') {
            steps{
                sh "We can show the output here"
            }
        }
    }
    post {
        always {
            cleanWs()
        }
    }
}