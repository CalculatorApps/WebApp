 node  {
    
          stage('Checkout') {
               //Checkout the code from a GitHub repository
               git credentialsId: 'venkat0007', url: 'https://github.com/DIGITALAPPLICATION/WebApp.git'
                           }
         stage ('compile')
         {
         sh '"/usr/apache-maven-3.5.4/bin/mvn" -V clean compile'
          }
         stage ('package')
         {
         sh '"/usr/apache-maven-3.5.4/bin/mvn" -V package'
         }
         stage ('install')
         {
         sh '"/usr/apache-maven-3.5.4/bin/mvn" -V install '
         }

}

