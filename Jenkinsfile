pipeline {
    options {
        disableConcurrentBuilds()
    }
    agent cm10build
    stages {
        stage('DinD') {
            steps {
                container('docker-client') {
                    sh 'docker ps'
                }
            }
        }
    }
}