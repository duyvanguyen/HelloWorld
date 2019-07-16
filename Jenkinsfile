pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''date
echo "Build Helloworld"
sleep 5
javac Hello.java'''
      }
    }
    stage('Test') {
      steps {
        sh '''date
cd /root/jenkins/Project
sleep 10
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