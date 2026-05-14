pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building Project'
            }
        }

        stage('Deploy') {
            steps {
                bat 'mkdir C:\\DeployHTML'
                bat 'copy index.html C:\\DeployHTML'
            }
        }
    }
}