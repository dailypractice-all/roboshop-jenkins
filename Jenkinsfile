pipeline {
  agent java-job-project
  options {
    ansiColor('xterm')
  }
  stages {
    stage ('Create jobs') {
      steps {
        sh 'ansible-playbook create-jobs.yml'
      }
    }
  }
}
