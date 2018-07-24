pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'Build'
          }
        }
        stage('Maven Build') {
          steps {
            sh '''echo "maven install step"
make.sh '''
          }
        }
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy'
      }
    }
    stage('Test') {
      steps {
        echo 'Test'
      }
    }
  }
}