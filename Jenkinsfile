pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                slackSend color: "good", message: "Message from Jenkins Pipeline - Avi" 
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}