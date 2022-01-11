pipeline {
  agent any
  stages {
    stage('Deploy') {
      parallel {
        stage('Deploy') {
          steps {
            echo 'Print message to check deploy'
          }
        }

        stage('') {
          steps {
            bat 'mvn -v'
          }
        }

      }
    }

  }
}