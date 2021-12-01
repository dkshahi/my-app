pipeline {
    agent any
    stages {        
        stage('--clean--'){
            steps {
                
                sh 'mvn clean'
            }
        }
        stage('--test---'){
            steps {
                
                sh 'mvn test'
            }
        }
        stage('--Package---'){
            steps {
                
                sh 'mvn package'
            }
        }
       stage('--Deploy---'){
            steps {
                
                sh 'mvn deploy'
            }
        }
    }
}
