pipeline {
   agent { docker { image 'python:3.5.1'}}
   environment {
      PROJECT_NAME = "test_project"
   }
   stages {
      stage('build') {
         steps {
            sh 'python --version'
            echo 'this is a test'
         }
      }
      stage('validate') {
         steps {
            sh "echo validated project $PROJECT_NAME"
         }
      }
   }
}
