pipeline{
    agent any   
    stages {    
        stage("verify branch "){
            steps{
                echo " $GIT_BRANCH & $BUILD_NUMBER "
            }
        }
          stage('create a poostgrtes') {
      agent any
      steps {
         
         echo " created"
          sh '''
             chmod +r test.sh
             ./test.sh
          
             '''
           
      }
    }
       
        
    }
    
}
