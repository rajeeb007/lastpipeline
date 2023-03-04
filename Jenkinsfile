
pipeline {
    agent any
    stages {
        stage('checkout') {           
            steps {
                checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: 'raji_git', url: 'https://github.com/rajeeb007/lastpipeline.git']]])  
            }
        }
        stage('Update Version') {
            steps {
             echo "this is rajeeb"
            }
        }   
    }  
  }
