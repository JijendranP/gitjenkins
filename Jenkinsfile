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
      stage("deploy "){
            input {
                message 'deploy?'
                ok 'do it'
                parameters {
                    string(name:'TARGET_ENVIRONMENT', defaultvalue: 'PROD', description: 'Target deployment environment')
                }
            }
        }   
        
    }
    
}

