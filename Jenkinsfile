pipeline {
    agent { docker { image 'docker-compose-1-7-1-yad' } }
    stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
