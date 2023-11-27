pipeline {
    agent any
    parameters {
        string(name: 'NAME', defaultValue: 'OBI', description: 'Enter your name')
    }
    stages { 
        stage('Guest user'){
            steps {
                script {
                    def name = params.NAME
                    echo "Hello, $name"

                }
            }
        } 

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
