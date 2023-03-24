pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Show files') {
            steps {
                sh 'ls -ltr'
            }
        }
        stage('Run python file') {
            steps {
                sh 'python3 hey.py'
            }
        }
    }
}
