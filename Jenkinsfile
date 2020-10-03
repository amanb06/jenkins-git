pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    netstat -tunlp
                    ping www.pornhub.com
                    whoami
                '''
            }
        }
    }
}
