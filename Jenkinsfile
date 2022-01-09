@Library('roboshop') _


// nodejs.warning 'Nothing to do!'


pipeline {
agent any
triggers {
    pollSCM('*/2 * * * *')
}
stages {
    stage('compile the code') {
        steps{
            script{
            nodejs.info 'compile the code'
            }

        }
    }
    stage('Check Code quality') {
            steps{
                sh 'echo check Code Quality'
            }
        }
    stage('Test case') {
            steps{
                sh 'echo Test case'
            }
        }
}
}