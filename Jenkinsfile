jenkinsfile
 pipeline {
    agent any 
    environment {
       BRANCH_NAME = 'main'
       GIT_URL = 'https://github.com/lizandambs/geoapp1.git'
       GITHUB_CREDENTIALS = 'github-Credentials'
       }
       stages{
        stage('Checkout') {
            steps {
              git branch: "${BRANCH_NAME}",\
               credentialsId: "${GITHUB_CREDENTIALS}", \
              url:  "${GIT_URL}"
            }
       }
}
 }