pipeline {
    agent any 
    stages {
        stage('Build') { 
            steps {
                script{
                    sh """
                    echo " This is build"
                    """
                } 
            }
        }
        stage('Test') { 
            steps {
                 script{
                    sh """
                    echo " This is test"
                    """
                }  
            }
        }
        stage('Deploy') { 
            steps {
                 script{
                    sh """
                    echo " This is deploy"
                    """
                }  
            }
        }
    }
}