pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'hare krishna pipeline'
      }
    }
    stage('qa') {
      steps {
        retry(count: 2)
      }
    }
  }
}