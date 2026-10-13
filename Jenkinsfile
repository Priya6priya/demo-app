pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Priya6priya/demo-app.git'
            }
        }

        stage('Build') {
            steps {
                bat 'mvn clean compile'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}
