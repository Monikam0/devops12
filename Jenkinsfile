pipeline {
  agent any 

  stages {
    stage('build') {
          step {
            bat 'mvn clean build'
          }
          }
     stage('Deploy') {
       step {
         echo 'Applicationdeployes successfully"
       }
     }
  }
}
