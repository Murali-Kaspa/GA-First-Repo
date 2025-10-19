@library ('my-shared-lib')
pipeline{
  agent any
  stages{
    stage('Welcome Page'){
      steps{
        echo "Hello World"
      }
    }
    stage('Library Test'){
      steps{
        sample()
      }
    }
  }
}  
