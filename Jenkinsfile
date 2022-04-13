pipeline {
   agent any

   stages{

      // For each commit
      stage('Lint Check') {
        steps{
            sh 'npm install eslint'
        }
      }
   } // end of stages
}