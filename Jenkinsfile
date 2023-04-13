pipeline {
  agent {
    docker { image 'httpd' }
  }
  stages {
    stage('Test') {
      steps {
        sh './source /usr/local/apache2/htdocs/'
      }
    }
  }
}
