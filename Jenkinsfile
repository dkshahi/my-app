pipeline {
    agent any
    stages {        
        stage('--clean the devop'){
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
