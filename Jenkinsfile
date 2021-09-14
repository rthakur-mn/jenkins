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
          sh 'mvn deploy'
        }
      }
    }
}
