pipeline {
    agent { docker { image 'hello-word:latest' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}
