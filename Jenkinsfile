@Library('Test-Shared-Library') _
pipeline {
agent any

  stages{
    stage('Build'){
      steps{
        script{
          javabuild()
        }
      }
    }
    stage('Deploy'){
       steps{
        script{
          deploy()
        }
      }
    }
  }
}
