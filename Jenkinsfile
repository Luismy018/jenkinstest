pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running script'
                sh myscript.sh
            }
        }
        stage('Test') {
            steps { 
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying.... '
            }
        }
    }
}