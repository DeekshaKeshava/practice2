pipeline {
    agent any

    stages {

        stage('Build') {
            steps {
                echo 'Building HTML Project'
            }
        }

        stage('View HTML File') {
            steps {
                bat 'type index.html'
            }
        }
    }
}