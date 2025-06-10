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
    stages {
       stage("compile") {
         steps{
            sh'maven compile'
         }
       }
    stages {
        stage("test") {
            steps{
               sh'maven test'
            }
        }
   stages {
         stage("package") {
             steps{
               sh'maven package'
             }
         }
  }
}
