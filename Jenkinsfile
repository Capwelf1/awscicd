pipeline {
  agent any


  environment{
    BRANCH_NAME = 'main'
    GIT_URL = 'https://github.com/Capwelf1/awscicd.git'
  }
    stages {
      stage('git checkout'){
        steps{
      git branch: "${BRANCH_NAME}", url: "${GIT_URL}"
        }
      }
      stage ('test'){
        steps{
            sh 'echo test'
        }
      }
    }

}