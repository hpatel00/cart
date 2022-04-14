pipeline {
   agent any

   stages{

      // For each commit
      stage('Lint Check') {
        steps{
            sh '''
                ~/node_modules/jslint/bin/jslint.js server.js
            '''
        }
      }
   } // end of stages
}