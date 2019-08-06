node
{
   checkout scm
 
   stage ('Package')
   { 
      sh 'mvn clean package'    
   }
   stage ('site')
   {
   sh 'mvn site'
   }
   
}  
 







