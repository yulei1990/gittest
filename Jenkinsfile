pipeline {
  agent any
  stages {
    stage('before') {
      parallel {
        stage('before') {
          steps {
            echo 'hello world test2'
          }
        }

        stage('after') {
          steps {
            echo 'test ok'
          }
        }

      }
    }

  }
}