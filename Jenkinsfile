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
javac Hello.java
java Hello'''
      }
    }
  }
}