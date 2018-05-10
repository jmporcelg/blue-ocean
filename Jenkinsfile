pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('test') {
      parallel {
        stage('stage 1') {
          steps {
            echo 'hi'
            writeFile(file: 'test', text: 'text ', encoding: 'utf-8')
          }
        }
        stage('stage 2') {
          steps {
            echo 'step 2 started'
          }
        }
      }
    }
  }
}