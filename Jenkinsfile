pipeline {
  agent any
  stages {
    stage('Example') {
      
      environment{
        GITHUB_COMMON_CREDS = credentials('jenkins-github-common-creds')
      }
      steps {
        sh 'printenv'
      }
    }
  }
}
