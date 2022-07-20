pipeline {

    agent {
        node {
            label 'master'
        }
    }


    stages {    
        stage('minikube on DEV Environment') {  
            
            when {
                branch 'dev'
            }
            
            steps {
                
                echo "Welcome to Windows 10! Minikube going to on start mode"
                bat "minikube start"
                bat "minikube dashboard"
            }   
        }
        
        stage('minikube on DEV Environment') {  
            
            when {
                branch 'main'
            }
            
            steps {
                
                echo "Welcome to Windows 10! Minikube going to on start mode"
                bat "minikube start"
                bat "minikube dashboard"
            }   
        }  
  
    }

}
