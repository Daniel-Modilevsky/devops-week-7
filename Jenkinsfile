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
                cd 'cd /Users/modilevskydaniel/.jenkins/workspace/devops_lesson_7'
                sh 'python3 hey.py'
            }
        }
    }
}
