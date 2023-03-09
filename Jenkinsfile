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
      parallel {
        stage('test') {
          steps {
            echo 'test step'
          }
        }

        stage('test parallel') {
          steps {
            echo 'its run para'
          }
        }

      }
    }

    stage('deploy') {
      steps {
        echo 'deploying'
      }
    }

  }
}