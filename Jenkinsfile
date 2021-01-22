pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        mail(subject: 'bule_ocean_test', body: 'bule_ocean_test')
      }
    }

    stage('') {
      steps {
        sh 'echo "test test test"'
      }
    }

  }
  environment {
    author = 'chenxu'
  }
}