pipeline {
    agent {
        docker { image 'node:7-alpine' }
    }
    stages {
        stage('build') {
            steps {
                node --version
            }
        }
    }
}
