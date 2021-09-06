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
           
      }
    }
       
        stage("LINUX CMNDS "){
             agent any
            steps{
                sh '''
                echo " $GIT_BRANCH & $BUILD_NUMBER "
                echo " $GIT_BRANCH & $BUILD_ID "
                
            }
        }
        
    }
    
}
