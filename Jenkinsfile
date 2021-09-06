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
         
         
          mv test.sh test1.sh
          ls
          chmod +r test1.sh
          '''
      }
    }
        
    }
    
}

