pipeline{
    
    agent any 
    
    stages {
        
        stage('Git Checkout'){
            
            steps{
            
                    
                git branch: 'main', url: 'https://github.com/sivachandra422/demo-counter-app.git'

            }
        }

        stage('Unit Testing'){
            
            steps{

                sh 'mvn test'

            }

        }

        stage('Integration Testing'){

            steps{

                sh 'mvn verify -DskipUnitTests'

            }

        }

        stage('Maven Build'{

            steps{

                sh 'mvn clean install'

            }

        })
        
    }
        
}