pipeline {
  agent any
  triggers {
    pollSCM('H/5 * * * *')
  }
  stages {
    stage('echo') {
      steps {
        echo 'hello from the trigger'
      }
    }

  }
}
