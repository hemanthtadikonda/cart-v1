@Library('roboshop') _

demo ()
pipeline {
   agent any
   stages {
      stage('Code compile'){
         steps {
            echo 'Hello World'
         }
         script {
            demo.info 'Starting'
            demo.warning 'Nothing to do!'
         }
      }
   }
}
