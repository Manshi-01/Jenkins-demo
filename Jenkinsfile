pipeline {
    agent any 
    stages {
        stage('Clone') {
            steps {
                git 'https://github.com/Manshi-01/Jenkins-demo.git'
            }
        }
          stage('Build') {
              steps {
                  sh 'javac Hello.java'
              }
          }
          stage('Run') {
              steps {
                  sh 'java Hello'
              }
          }
      }
}
