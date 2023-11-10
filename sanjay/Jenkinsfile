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
                    sh 'bash new.sh'
                }
            }
        }
       
    }
