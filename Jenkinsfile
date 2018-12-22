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
    stage('mail') {
      steps {
        mail(subject: 'testing from jenkins', body: 'sarasa sarasa', to: 'enrique.conci@hdmz.com', from: 'enrique.conci@hdmz.com')
      }
    }
  }
}