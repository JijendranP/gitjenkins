pipeline{
    agent any   
    stages {    
        stage("verify branch "){
            steps{
                echo " $GIT_BRANCH"
            }
        }
         sstage('Docker Build') {
      agent any
      steps {
        sh "docker images -a "
      }
    }
       
    }
    
}
