pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "we building"'
        load 'dev.groovy'
      }
    }
    stage('Test') {
      steps {
        sh 'echo "ho"'
      }
    }
    stage('Deploy') {
      steps {
        sh 'echo "the merry o"'
      }
    }
  }
}