pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
                
                script{
                    
                    git branch: 'main', url: 'https://github.com/sivachandra422/demo-counter-app.git'
                }
            }
        }
        
    }
        
}