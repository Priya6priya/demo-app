pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat '"C:/Users/PRIYAJ/Downloads/apache-maven-3.9.16-bin/apache-maven-3.9.16/bin/mvn.cmd" clean compile'
bat '"C:/Users/PRIYAJ/Downloads/apache-maven-3.9.16-bin/apache-maven-3.9.16/bin/mvn.cmd" test'
            }
        }

        stage('Test') {
            steps {
                bat 'mvn test'
            }
        }
    }
}
