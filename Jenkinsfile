pipeline {
    agent {
        node {
            label 'MAVEN'
        }
    }
    stages {
        stage('Clean and Compile') {
            steps {
                withMaven(maven: 'Maven 3.8.6') { // Replace with your Maven installation name
                    sh 'mvn clean compile'
                }
            }
        }
    }
}
