// @Library('roboshop') _
//
// //variable
// env.COMPONENT = 'cart'
//
// env.BUILD_LABEL = 'WORKSTATION'
//
// // nodejs.warning 'Nothing to do!'
//
// // Library groovy file
// nodejs()
// ----------------------------------------
@Library('roboshop') _
pipeline{
agent { label 'WORKSTATION' }

triggers {  pollSCM('*/2 * * * *') }

stages {

stage('Compile Code'){
steps{
 sh 'echo Compile the code'
}
}

stage('Code Chek'){
steps{
 sh 'echo Code check'
}
}

stage('Test Cases'){
steps{
 sh 'echo Test case'
}
}


}
}



