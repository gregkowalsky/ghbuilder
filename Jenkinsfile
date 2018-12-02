
pipeline {
  agent {
    kubernetes {
      label 'jnk-slave-k8s'
      //defaultContainer 'jnlp'
    }
  }
  stages {
        stage('build') {
            steps {
                sh 'php --version'
            }
        }
    }
}
