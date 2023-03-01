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
                    sh 'echo "my first pipeline"'
                }
            }
        }
       
    }
}
