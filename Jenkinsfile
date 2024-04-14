pipeline {
  agent any
  stages {
    stage('Initialize') {
      steps {
        echo 'checkout code'
        git(url: 'https://github.com/mobiniqow/jenkins-test.git', branch: 'main')
      }
    }

  }
}