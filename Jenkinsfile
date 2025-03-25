pipeline { 
agent any 
  stages {
    stage("run frontend") {
      steps {
        echo 'executing yarn...'
        nodejs('NodeJS 23.10.0')
      }
    }
    stage('run backend') {
      steps {
        echo 'executing gradle...' 
      }
    }
  }
}
