pipeline {
    agent any 
    stages {
        stage('Compile') { 
            steps {
                withMaven(maven : 'Maven 3.6.5') {
                    sh 'mvn compile'
                }
            }
        }
    }
}