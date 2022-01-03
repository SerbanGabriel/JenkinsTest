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
            }
        }
        stage('Something'){
        steps {
             test()
            }
        }
        def test() {
            echo "Start"
            sleep(5)
            echo "Stop"
        }
    }
}