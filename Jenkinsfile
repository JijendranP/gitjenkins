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
          sh '''
         echo " created"
         cd /root
         ls
          chmod +r test.sh
          ./test.sh
          
          '''
           
      }
    }
       
        
    }
    
}
