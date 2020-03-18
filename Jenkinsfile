pipeline {
  agent any
  stages {
    stage('Setup') {
      parallel {
        stage('Setup') {
          steps {
            sh 'sleep 30'
          }
        }

        stage('setup1') {
          steps {
            sh 'sleep 30'
          }
        }

        stage('setup2') {
          steps {
            sh 'sleep 30'
          }
        }

        stage('setup3') {
          steps {
            sh 'sleep 30'
          }
        }

      }
    }

    stage('Print Message') {
      steps {
        echo 'Done'
      }
    }

  }
}