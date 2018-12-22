pipeline {
  agent {
    docker {
      image 'qmaxquique/php_apache:7.2'
    }

  }
  stages {
    stage('get_repo') {
      steps {
        pwd()
      }
    }
  }
}