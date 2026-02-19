pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                bat 'javac StudentInfo.java'
                bat 'java StudentInfo'
            }
        }
    }
}
