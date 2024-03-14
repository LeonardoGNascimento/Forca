pipeline{
    agent Docker

    stages{
        stage('Build Docker Image') {
            steps {
                sh 'docker build .'
            }
        }
    }

}