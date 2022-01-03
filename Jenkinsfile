pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage ("wait_prior_starting_smoke_testing") {
         steps {
                     def time = params.SLEEP_TIME_IN_SECONDS
                                 echo "Waiting ${SLEEP_TIME_IN_SECONDS} seconds for deployment to complete prior starting smoke testing"
                                 sleep time.toInteger() // seconds
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
            }
        }
    }
}