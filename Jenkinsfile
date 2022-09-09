pipeline {
  agent any
  stages {
    stage(' running maven') {
      parallel {
        stage(' running maven') {
          steps {
            sh 'mvn test'
          }
        }

        stage('maven version') {
          steps {
            sh 'mvn --version'
          }
        }

      }
    }

  }
}