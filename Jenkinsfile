pipeline {
  agent any
  stages {
    stage('Initialize') {
      parallel {
        stage('Initialize') {
          steps {
            echo '=======================start======================='
            sh '''who
echo $ANDROID_HOME
pwd'''
          }
        }
        stage('Initialize2') {
          steps {
            echo '=========start2========'
          }
        }
      }
    }
    stage('TheEnd') {
      steps {
        echo '=======================end======================='
      }
    }
  }
}