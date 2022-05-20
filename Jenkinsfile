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
        ls
        echo "Do something 2"
        pwd
        ls -lrt
        echo $password
        pwd
        uname
        hostname
        touch 1
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
