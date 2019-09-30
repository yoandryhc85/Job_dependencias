pipeline{
    agent any
    stages{
        
        stage('Job primario de test'){
            
            steps{
                
                build job: 'Job_secundario_test', wait: true
            }
        }
         stage('Job de espera'){
            
            steps{
                
               echo "Esto es una prueba"
            }
        }
        
        stage('Job de confirmacion'){
            
            steps{
                
               echo "Realizado exitosamente"
            }
        }
        
    }
   
 }
