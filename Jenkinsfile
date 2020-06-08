pipeline {
    agent any
    stages{
         stage('build'){
              steps{
                 sh 'echo ----------------------------------'
                 sh 'echo hello folks this is building stage'
                 sh 'echo ----------------------------------'
              }
         }
         stage('Test'){
              steps{
                 sh 'echo ----------------------------------'
                 sh 'echo hello folks this is Testing stage'
                 sh 'echo ----------------------------------'
              }
         }
         stage('Deploy'){
              steps{
                 sh 'echo ----------------------------------'
                 sh 'echo hello folks this is Deployement stage'
                 sh 'echo ----------------------------------'
              }
         }
    }
}
