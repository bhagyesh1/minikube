pipeline {

    agent any

    stages {    
        stage('minikube on DEV Environment') {  
            
            when {
                branch 'dev'
            }
            
            steps {
                
                echo "Welcome to Windows 10! Minikube going to on start mode"
                bat "minikube start"
                bat "kubectl get no"
                bat "kubectl get ns"
            }   
        }
        
        stage('minikube on Master(main) Environment') {  
            
            when {
                branch 'main'
            }
            
            steps {
                
                echo "Welcome to Windows 10! Minikube going to on start mode"

            
            }   
        }  
  
    }

}
