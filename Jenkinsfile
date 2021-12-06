pipeline {
    agent { docker 'node:10' }
    stages {
        stage('build') {
            steps {
                sh 'npm server.js'
            }
        }
    }
}
