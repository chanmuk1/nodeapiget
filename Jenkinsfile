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
                bat 'npm install'
                bat 'node index.js'
            }
        }       
    }
}
