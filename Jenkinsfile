pipeline {
  agent any
  stages {
    stage('Buzz Build') {
      steps {
        echo 'Buzzing'
        archiveArtifacts(artifacts: 'target/*.jar', fingerprint: true)
      }
    }

  }
}