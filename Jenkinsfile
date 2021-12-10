pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        withAnt(jdk: 'Oracle8.221', installation: 'Ant10') {
          sh '''
          cd build
          ant
          '''
        }

      }
    }

  }
}
