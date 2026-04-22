pipeline {
    agent any
    stages {
        stage('Build & Push') {
            steps {
                sh 'docker build -t jackjack1331/app5:latest .'
                sh 'docker push jackjack1331/app5:latest'
            }
        }
    }
}
