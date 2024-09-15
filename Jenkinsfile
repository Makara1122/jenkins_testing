pipeline {
    agent { docker { image 'maven:3.9.9-eclipse-temurin-21-alpine' } }
    stages {
        stage('build') {
            steps {
                sh 'mvn --version'
            }
        }
        stage('Hello World') {
            steps {
                sh 'echo "Jenkins hello makara"'
            }
        }
    }
}
