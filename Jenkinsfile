pipeline {
  agent any
  stages {
    stage('checkout') {
      steps {
        echo 'Hello World'
        git(url: 'https://github.com/CJRivas/jenkinspipeline', branch: 'master')
        sh 'mvn clean'
      }
    }
  }
}