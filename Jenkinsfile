pipeline {
  agent any
  stages {
    stage('bnc') {
      parallel {
        stage('bnc') {
          steps {
            echo 'hi'
          }
        }

        stage('') {
          steps {
            sh 'echo "hi"'
          }
        }

      }
    }

  }
  environment {
    env = ''
  }
}