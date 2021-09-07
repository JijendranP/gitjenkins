pipeline{
    agent any   
    environment {
        hi = 'bye'
    }
    stages {    
        stage("verify branch "){
            steps{
                echo " $GIT_BRANCH & $BUILD_NUMBER "
            }
        }
          stage('create a poostgrtes') {
              steps{
   
          echo "$hi"
      }
    }
       stage('script') {
              steps{
   
          sh '''
         
         ls
         test2.sh
          '''
      }
    }
        
    }
    
}

