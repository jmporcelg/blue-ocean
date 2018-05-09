pipeline {
  agent {
    node {
      label 'master'
    }

  }
  stages {
    stage('error') {
      steps {
        echo 'hi'
        writeFile(file: 'test', text: 'text ', encoding: 'utf-8')
      }
    }
  }
}