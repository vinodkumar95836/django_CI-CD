pipeline {
    agent { dockerfile true }
    stages {
        stage('Test') {
            steps {
                bat 'node --version'
                bat 'svn --version'
            }
        }

stage('Build') {
            steps {
                echo 'Build is successful'
                
            }
        }
    }
}
