pipeline {
    agent any 
       tools {
        maven 'maven'
      }
    stages {
        stage("clean") {
           steps{
              sh'maven clean'
          }
        }
    stage("compile") {
         steps {
            sh'maven compile'
         }
       }
    stage("test") {
            steps {
               sh'maven test'
            }
        }
    stage("package") {
             steps {
               sh'maven package'
             }
         }
    }
}
