pipeline {
  agent {
    docker {
      image 'alpine'
    }

  }
  stages {
    stage('') {
      steps {
        echo 'hi'
        writeFile(file: 'test', text: 'text ', encoding: 'utf-8')
      }
    }
  }
}