pipeline {
    agent any

    stages {
        stage('Debug') {
            steps {
                bat 'dir'
            }
        }

        stage('Build') {
            steps {
                bat 'javac *.java'
            }
        }

        stage('Run') {
            steps {
                bat 'java MainApp1'
            }
        }
    }
}

