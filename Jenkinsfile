pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                php index.php
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
