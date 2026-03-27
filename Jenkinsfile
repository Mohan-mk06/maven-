pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Mohan-mk06/maven-.git'
            }
        }

        stage('Build and Test') {
            steps {
                bat 'mvnw.cmd clean test'
            }
        }
    }
}