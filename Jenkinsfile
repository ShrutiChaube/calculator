pipeline {
  agent any
  
  stages {
    stage('Build') {
          steps {
            sh 'cd /var/www/html/'
            sh 'rm -rf calculator'
            sh 'git clone https://github.com/ShrutiChaube/calculator'
          }
    }
  }
}
  
