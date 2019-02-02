pipeline {
  agent any
  stages {
    stage('hello world') {
      steps {
        node('macos') {
          sh 'echo "macos hello world"'
        }
        node('linux') {
          sh 'echo "macos hello world"'
        }
      }
    }
  }
}
