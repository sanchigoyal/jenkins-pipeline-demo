pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/sanchigoyal/jenkins-pipeline-demo.git', branch: 'master')
      }
    }
  }
}