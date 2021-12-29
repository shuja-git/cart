pipeline {
    agent { lable 'WORKSTATION' }

    triggers { pollSCM('*/2 * * * *') }

    stages {
        stage('compile the code') {
            steps {
                sh 'compile code'
            }
            stage('check the code quality') {
                steps {
                    sh 'check the code quality'
                }
                stage('Test cases') {
                    steps {
                        sh 'Test cases'
                    }
                }
            }
        }
    }
}