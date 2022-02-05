
pipeline {
       
       agent any
   
    stages {
        
        stage('Cleanup Workspace') {
            steps {
                mvn clean
            }
        }

        stage('Code Checkout') {
            steps {
               mvn test
            }
        }

        stage('Code Build') {
            steps {
                mvn site
            }
        }
 
            }
        }