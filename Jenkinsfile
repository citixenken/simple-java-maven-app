pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package'
            }
        }
        // stage('Test') {}
        // stage('Deliver') {}
    }
}