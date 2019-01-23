pipeline {
    agent any
    stages {
        stage('Build') {
                steps {
                checkout scm 
                withMaven(maven: 'maven_3_5_1') {
                    bat 'mvn clean compile'
                }
            }
        }
    }
}
