pipeline {
  agent any
  stages {
    stage('Hello Word') {
      steps {
        echo 'Hello word'
      }
    }

    stage('compile') {
      steps {
        sh 'mvn clean isntall'
      }
    }

    stage('Ended') {
      steps {
        echo 'terminado'
      }
    }

  }
}