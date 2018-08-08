pipeline {
  agent any
  stages {
    stage('Input_Stage') {
      steps {
        input(message: 'Do you want to continue', id: 'build_id', submitter: 'admin')
      }
    }
  }
}