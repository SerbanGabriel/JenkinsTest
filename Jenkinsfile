pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing.. branch 1'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
                sh 'sleep 60'
            }
        }
    }
}