pipeline {
   agent { docker { image 'python:3.5.1'}}
   stages {
      stage('build') {
         steps {
            sh 'python --version'
            echo 'this is a test'
         }
      }
      stage('validate') {
         steps {
            echo 'validated'
         }
      }
   }
}
