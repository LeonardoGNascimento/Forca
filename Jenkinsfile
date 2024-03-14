pipeline{
    agent {
        docker {
            image 'maven:3.9.5-eclipse-temurin-17-alpine' 
            args '-v /root/.m2:/root/.m2' 
        }
    }

    stages{
        stage('Build Docker Image') {
            steps {
                sh 'docker build .'
            }
        }
    }

}