pipeline {
  agent any
  stages {
    stage('') {
      parallel {
        stage('MAVEN-PROY') {
          steps {
            build 'MAVEN-PROYECTO'
          }
        }

        stage('JOB11') {
          steps {
            build 'JOB11'
          }
        }

      }
    }

    stage('JOB33') {
      steps {
        build 'JOB33'
      }
    }

  }
}