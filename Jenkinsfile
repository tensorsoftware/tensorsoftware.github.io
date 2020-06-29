pipeline {
    agent { label 'www' }
    stages {
        stage('build') {
            steps {
                sh 'firefox index.html'
            }
        }
    }
}