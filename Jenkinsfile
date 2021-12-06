pipeline {
    agent { docker 'node:12' }
    stages {
        stage('build') {
            steps {
                sh 'npm server.js'
            }
        }
    }
}
