pipeline {
 agent any 

  stages {
   stage('git checkout'){
    steps{
        git branch git branch: 'main', url: 'https://github.com/lizandambs/awscicd.git'
    }
   }
   stage('test'){
    steps{
        sh 'echo test'
    }
   }
  }
}
