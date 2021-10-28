pipeline {
    agent any
    stages {
        stage('clean') {
            steps {
                sh "mvn clean"
            }
        }
        stage('--verify--') {
            steps {
                sh "mvn verify"
            }
        }
        stage('--package--') {
            steps {
                sh "mvn package"
            }
        }
    }
}

