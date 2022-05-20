pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Do something branch3"
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
        echo "nuevo mensage"
        echo "new new"
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
