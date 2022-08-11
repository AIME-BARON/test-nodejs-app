pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo AIMEbrice1980$ | sudo -S yum install npm' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
