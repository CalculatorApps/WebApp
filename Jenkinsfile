node {
   stage('Checkout') {
      //Checkout the code from a GitHub repository
      git credentialsId: 'venkat0007', url: 'https://github.com/DIGITALAPPLICATION/WebApp.git'
      }
   stage ('build')
   {
     sh /usr/apache-maven-3.5.4/mvn compile
   }
}
