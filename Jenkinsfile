pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello Wangtp"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}