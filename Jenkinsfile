pipeline { 
  
   agent ( node (label 'java'))

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           sh 'echo "deploying application..."'
           sh ' echo "Successfully deploying Node JS Application..."'
         }

     }
  
   	}

   }
