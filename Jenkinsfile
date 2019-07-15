pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''date
echo "Build Helloworld"'''
      }
    }
    stage('Test') {
      steps {
        sh '''date
echo "test for pass will continues"
java Helloword'''
      }
    }
  }
}