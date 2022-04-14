@Library('roboshop-shared-library@main') _

pipeline {
   agent any

   stages{

      // For each commit
      stage('Lint Check') {
        steps{
           script{
              nodejs.lintChecks()
           }
        }
      }
   } // end of stages
}