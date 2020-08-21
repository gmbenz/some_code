pipeline {
  agent any
  triggers {
    cron('H/5 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger'
      }
    }

  }
}
