@Library(['Test-Shared-Library', 'Test-Shared-Library2']) _
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
    stage('String'){
       steps{
        script{
          stringExample()
        }
      }
    }
  }
}
