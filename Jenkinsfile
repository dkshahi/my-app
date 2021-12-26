pipeline {
    agent any
    stages {        
        stage('--clean the build'){
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
       
    }
}
