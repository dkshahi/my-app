pipeline {
    agent any
    stages {        
        stage('--clean the devop'){
            steps {
                
                sh 'mvn clean'
            }
        }
        stage('Building the code') {
            steps {
                retry(3) {
                    sh 'ls -la'
                    sh 'pwd'
                    sh './new.sh'
                }
            }
        }
       
    }
}
