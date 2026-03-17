pipeline {
    agent { label 'test' }

    stages {
        stage('Run python file') {
            steps {
                sh 'python3 test.py'
            }
        }
    }
}
