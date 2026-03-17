pipeline {
    agent { label 'test' }

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Angel04ek-murrmyau/jenkins_test'
            }
        }

        stage('Run python file') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}
