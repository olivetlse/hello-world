pipeline {  
       agent any
       tools {
              maven 'maven'
       }
    stages {       
        stage('Cleanup Workspace') {
            steps {
               sh 'mvn clean'
            }
        }
        stage('Code test') {
            steps {
              sh 'mvn test'
            }
        }
        stage('Code Build') {
            steps {
             sh 'mvn package'
            }
        }          
    } 
}
