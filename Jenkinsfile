pipeline {
    agent any
    triggers {
        pollSCM('*/1 * * * *')
    }
    stages {
        stage("Unit Test") {
            steps {
                sh "python test_calculator.py"
            }
        }
    }
}