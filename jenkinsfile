pipeline {
    
    agent any 
    
    stages{
        
        stage('checkout'){
            
            steps{
                
                echo "this is git ccheckout stapes "
            }
        }
         stage('mvn package'){
             steps{
                 echo "mvn stage"
             }
             
         }
         
         stage('deploy'){
             steps{
                 
                 echo "deploy package"
             }
             
         }
        
               }
    
}
