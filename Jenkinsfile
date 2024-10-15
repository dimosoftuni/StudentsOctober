pipeline {
   agent any
   stages {  
      stage('NPM Install') {
         steps {
            bat 'npm install'
         }
         steps {
            bat 'npm test'
         }
      }
   }
}
