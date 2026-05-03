pipeline {
    agent any

    tools {
        jdk 'jdk17'
    }

    stages {
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
