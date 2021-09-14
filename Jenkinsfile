pipeline{
  agent any
    stages{
      stage('buidling'){
        steps{
          sh 'mvn clean compile'
        }
      }
      stage('Testing'){
        steps{
          sh 'mvn test'
        }
      }
      stage('Deploying'){
        steps{
          echo 'Deploying to the server'
        }
      }
    }
}
