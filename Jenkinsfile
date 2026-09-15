pipeline {
    agent any 
    stages {
        stage('Test') {
            steps {
                sh 'echo Running tests'
            }
        }
        stage ('Approve') {
            steps {
                input message: 'Tests passed. deploy to production ?'
            }
        }
        stage ('Deploy') {
            steps {
                sh 'echo deploying to production'
            }
        }
    }
                
    
   
