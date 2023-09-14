pipeline {
    agent any
    stages {
        stage('Build') { 
            steps {
                echo 'BUILD DONE' 
            }
        }
        stage('Test') {
            steps {
                echo 'TEST DONE'
            }
        }
        stage('Deliver') {
            steps {
                input message: 'Finished using the web site? (Click "Proceed" to continue)'
            }
        }
    }
}
