pipeline {
  agent any
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sh '''date
echo "Build Helloworld"'''
          }
        }
        stage('Test') {
          steps {
            sh '''echo "test begin"
java HelloWorld'''
          }
        }
      }
    }
  }
}