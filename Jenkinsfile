pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withAnt(jdk: 'Oracle8.222', installation: 'Ant10') {
          sh 'cd build'
        }

      }
    }

  }
}