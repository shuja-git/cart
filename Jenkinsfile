pipeline {
    agent { lable 'WORKSTATION' }

    triggers { pollSCM('*/2 * * * *') }

    stages {
        stage('compile the code') {
            steps {
                sh 'echo compile code'
            }
            stage('check the code quality') {
                steps {
                    sh 'echo check the code quality'
                }
                stage('Test cases') {
                    steps {
                        sh 'echo Test cases'
                    }
                }
            }
        }
    }
}