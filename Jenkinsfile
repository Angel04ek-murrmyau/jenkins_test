pipeline {
    agent { label 'test' }

    stages {
        stage('Run python file') {
            steps {
                git url: 'https://github.com/Angel04ek-murrmyau/jenkins_test.git', branch: 'main'
                sh 'python3 test.py'
                sh 'echo "Hello world"'
                sh date
            }
        }
    }
}
