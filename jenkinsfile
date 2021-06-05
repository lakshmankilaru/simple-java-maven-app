pipeline {
    agent any
    stages {
        stage('git') {
            steps{
                git 'https://github.com/lakshmankilaru/simple-java-maven-app.git'
            }
        }
        stage('maven build stage') {
            steps{
                sh 'mvn clean package'
            }
        }
    }
}
