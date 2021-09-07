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
          '''
      }
    }
      stage('run-parallel-branches') {
  steps {
    parallel(
      a: {
        echo "This is branch a"
      },
      b: {
        echo "This is branch b"
      }
    )
  }
} 
        
    }
    
}

