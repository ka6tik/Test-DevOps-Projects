@Library('Test-Shared-Library') _
pipeline {
agent any

  stages{
    stage('Build'){
      steps{
        script{
          build()
        }
      }
    }
    stage('Scan'){
      steps{
        script{
          scan()
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
