pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Building the Weather App...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying the Weather App...'
            }
        }
    }
}
