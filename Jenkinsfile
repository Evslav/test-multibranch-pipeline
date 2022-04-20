pipeline {
    agent none 
    stages {
        stage('Example Build') {
            agent { label 'linux' } 
            steps {
                echo 'Hello, Linux'
                sh 'env'
            }
        }
        stage('Example Test') {
            agent { label 'windows' } 
            steps {
                echo 'Hello, Windows'
                sh 'env'
            }
        }
    }
}
