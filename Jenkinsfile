pipeline {
    agent any

    stages {

         stage('Checkout') {
            steps {
               git branch: "main"
               url : "https://github.com/merahsamia/Pipeline.git"

            }
        }
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
