pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Do something"
      }
    }
    stage('Test') {
      steps {
        sh '''
        echo "Do something 2"
        hostname
        '''
      }
    }
    stage('Deploy') {
      steps {
        echo "Do something 3"
      }
    }
  }
}
