pipeline{
    agent any   
    stages {    
        stage("verify branch "){
            steps{
                echo " $GIT_BRANCH"
            }
        }
         stage('Docker Build') {
         steps {
        
             docker images -a
            
         }
      }
       
    }
    
}
