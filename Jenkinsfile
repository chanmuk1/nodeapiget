pipeline {
    agent {
        docker {
            image 'node:18-alpine'
            args '-p 5000:5000'
        }
    }
    stages {
        stage('Build') {
            steps {
                sh 'npm install'
                sh 'node index.js'
            }
        }       
    }
}
