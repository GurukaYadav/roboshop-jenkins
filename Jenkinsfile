pipeline {
  agent any
  ansiColor('xterm') {
  stages {
    stage('create a job') {
      steps {
        sh 'ansible-playbook create-jobs.yml'
      }
    }
  }
  }
}

