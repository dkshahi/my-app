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
                sh 'echo "my first pipeline"'
                sh '''
                    echo "By the way, I can do more stuff in here"
                    ls -ltrh
                '''
            }
        }
       
    }
}
