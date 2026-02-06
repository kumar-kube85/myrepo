pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
               
                 sh 'mvn clean '
            }
        }
        stage('Test') {
            steps {
                // Assuming your project has unit tests and a maven test phase
                sh 'mvn test'
            }
        }
    }
}
