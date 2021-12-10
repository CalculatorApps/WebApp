 node  {
  
 
    
          stage('Checkout') {
               //Checkout the code from a GitHub repository
               git credentialsId: 'venkat0007', url: 'https://github.com/DIGITALAPPLICATION/WebApp.git'
                           }
          stage('Example') {
              sh 'mvn clean'
              sh 'mvn package'
             sh 'mvn install'
	     sh 'echo venkat'
           
            
        }
    }



