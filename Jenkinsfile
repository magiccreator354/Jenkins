pipeline {
    agent any

    stages {
        stage('Code') {
            steps {
                echo 'Cloning the code....'
            }
        }
        stage('Build') {
            steps {
                echo 'Hello Build started'    
            }
        }
        stage('Push to Docker Hub') {
           steps {
               echo 'Pushing image to Docker Hub'
           }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying the code to production host'
            }
        }
    }
}
