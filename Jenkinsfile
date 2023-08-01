pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh './gradlew clean test'
            }
        }
        stage('test') {
             steps {
                 sh './gradlew clean test'
             }
        }
        stage('deploy') {
            steps {
                 sh './gradlew clean test'
            }
        }
    }
}