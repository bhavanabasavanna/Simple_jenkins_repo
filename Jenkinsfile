pipeline {
    agent any

    stages {
        stage('Install pytest') {
            steps {
                bat 'pip install pytest'
            }
        }
        stage('Run Test') {
            steps {
                echo 'Testing...'
                bat 'pytest test_calc.py'
            }
        }
    }
}

