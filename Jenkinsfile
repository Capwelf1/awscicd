pipeline {
  agent any
    stages {
      stage('git checkout'){
        steps{
      git branch: 'main', url: 'https://github.com/Capwelf1/awscicd.git'    
      
        }
      }
      stage ('test'){
        steps{
            sh 'echo test'
        }
      }
    }

}