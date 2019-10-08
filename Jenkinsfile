 node  {
    
          stage('Checkout') {
               //Checkout the code from a GitHub repository
               git credentialsId: 'venkat0007', url: 'https://github.com/DIGITALAPPLICATION/WebApp.git'
                           }
         agent any
    tools {
        maven 'apache-maven-3.0.1' 
    }
    stages {
        stage('Example') {
            steps {
                sh 'mvn --version'
            }
        }
    }
}

}

