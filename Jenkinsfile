pipeline {
  agent any
  options {
    ansiColor('xterm')
  }

  stages {
    stage('create a job') {
      steps {
        sh 'ansible-playbook create-jobs.yml'
      }
    }

  }

}