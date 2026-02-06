pipeline {
    agent any 

    stages {
        stage('Build') {
            steps {
                sh 'mvn -B -DskipTests clean package' 
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
