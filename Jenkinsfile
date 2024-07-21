pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat "php index.php"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}
