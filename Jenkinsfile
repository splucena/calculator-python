pipeline {
    agent any
    triggers {
        pollSCM('*/1 * * * *')
    }
    stages {
        stage("Unit Test") {
            steps {
                sh "python3 test_calculator.py"
            }
        }
    }
}