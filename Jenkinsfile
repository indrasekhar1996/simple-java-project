pipeline{
    agent any
    tools {
  maven 'maven'
}


stages{
    stage('Git Checkout Code'){
        steps{
            
            git 'https://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@github.com/indrasekhar1996/simple-java-project.git'
        }
    }
    stage('Build the Package'){
        steps{
            /*
            sh 'mvn clean install'
        */
        
        echo "Building the Package"
        
        }
    }
    stage('SonarQube Analysis'){
        steps{
        
        echo " scanning the code"
    }
    }
    stage('Deploy to Server'){
        steps{
        
        echo " Application Deployed"
    }
    }
}
}
