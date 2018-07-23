pipeline {
  agent any
  stages {
    stage('BuildCode') {
      steps {
        git(url: 'https://github.com/CJRivas/jenkinspipeline.git', branch: 'master', poll: true)
      }
    }
  }
  environment {
    test1 = ''
  }
}