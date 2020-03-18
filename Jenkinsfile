pipeline {
  agent any
  stages {
    stage('Setup') {
      parallel {
        stage('Setup') {
          steps {
            sh 'sleep 30'
            echo 'Done'
          }
        }

        stage('setup1') {
          steps {
            sh 'sleep 30'
            echo 'Done1'
          }
        }

        stage('setup2') {
          steps {
            sh 'sleep 30'
            echo 'Done2'
          }
        }

        stage('setup3') {
          steps {
            sh 'sleep 30'
            echo 'Done3'
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