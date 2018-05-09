pipeline {
  agent none
  stages {
    stage('error') {
      steps {
        echo 'hi'
        writeFile(file: 'test', text: 'text ', encoding: 'utf-8')
      }
    }
  }
}