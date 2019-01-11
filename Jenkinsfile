pipeline {
    agent { docker { image '3pcc_tng:huigjin1.6' } }
    stages {
        stage('build') {
            steps {
                sh 'uname -a'
            }
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
