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
cd /root/jenkins/Project
java Hello'''
      }
    }
  }
}