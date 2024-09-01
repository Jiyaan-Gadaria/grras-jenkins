pipeline {
    agent any
    environment {
        name = 'jayendra'
    }

    stages {
        stage('Unit-Test') {
            steps {
                sh '''
                date
                pwd
                touch grras.txt
                '''
            }
        }
    stage('build') {
            steps {
                sh 'echo "${BUILD_ID}"'
                sh 'jayendraa'
            }
        } 
    stage('Dev-Server') {
        environment {
        username = 'gadaria'
    }
            steps {
                sh 'echo "${name}"'
                sh 'echo "${username}"'
            }
        }  
    stage('Prod-Server') {
      
            steps {
                sh 'echo "${name}"'
            }
        }    
        
    }
}
