pipeline {
  agent any
  tools {
    maven 'Maven'
  stages {
    stage { 'Initialize'} {
      steps {
        sh '''
                 echo "PATH = $(PATH)"
                 echo "M2_Home = $(M2_HOME)"
           '''
           }
    }
           stage ('Build') {
             steps {
            sh 'mvn clean package'
            }
           }
          }
  }
  }
           
    
