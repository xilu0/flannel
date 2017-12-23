pipeline {
  agent {
    node {
      label 'docker'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'go get https://github.com/kubernetes/helm'
      }
    }
  }
}