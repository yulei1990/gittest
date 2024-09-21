pipeline {
  agent any
  stages {
    stage('before') {
      parallel {
        stage('before') {
          steps {
            echo 'hello world hahahahaha'
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