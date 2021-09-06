pipeline{
    agent any   
    stages {    
        stage("verify branch "){
            steps{
                echo " $GIT_BRANCH & $BUILD_NUMBER "
            }
        }
          stage('create a poostgrtes') {
   
      steps {
         sh '''
         echo" hi "
         echo " created"
         chmod +w test.sh
      }
    }
       
        
    }
    
}

