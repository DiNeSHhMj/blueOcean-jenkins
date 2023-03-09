pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''pwd                                                 
'''
        sh 'date'
      }
    }

    stage('test') {
      steps {
        echo 'test step'
      }
    }

    stage('deploy') {
      steps {
        echo 'deploying'
      }
    }

  }
}