pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat '''
                del *.class 2>nul
                javac *.java
                '''
            }
        }

        stage('Run') {
            steps {
                echo 'Skipping program run (requires user input)'
            }
        }
    }
}

