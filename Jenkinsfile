stage('Tests') {
    parallel {
        stage ('unit') {
            steps {
                sh 'echo  Running unit tests'
            }
        }
        stage('Intergration') {
            steps {
                sh 'echo Running integration tests'
            }
        }
    }
}
