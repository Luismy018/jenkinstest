pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running script'
                sh mysript.sh
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