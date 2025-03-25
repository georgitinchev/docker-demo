pipeline { 
agent any 
  stages {
    stage("run frontend") {
      steps {
        echo 'executing yarn...'
        nodejs('')
      }
    }
    stage('run backend') {
      steps {
        echo 'executing gradle...' 
      }
    }
  }
}
