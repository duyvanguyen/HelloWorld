pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''date
echo "Build Helloworld"
javac Hello.java'''
      }
    }
    stage('Test') {
      steps {
        sh '''date
cd /root/jenkins/Project
java Hello'''
      }
    }
    stage('deploy') {
      steps {
        sh '''date
echo "started deploy project"'''
      }
    }
  }
}