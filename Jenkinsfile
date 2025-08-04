pipeline {
    agent any

    stages {
        stage('Install pytest') {
            steps {
                sh 'pip3 install pytest'
            }
        }
        stage('Run Test') {
            steps {
                echo 'Testing...'
                sh 'pytest test_calc.py'
            }
        }
    }
}
