pipeline {
  agent {
    docker {
      image 'centos:6'
    }
    
  }
  stages {
    stage('initialise') {
      steps {
        sh 'ping -c 3 google.com'
      }
    }
  }
}