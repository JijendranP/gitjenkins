pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }

    stages {
        stage('gitclone') { 
            steps { 
                echo "clone code from Git repository" 
            }
        }
        stage('Build') { 
            steps { 
                echo "build stage" 
            }
        }
        stage('Code Analysis') { 
            steps { 
                echo "degubbing the code and improvise it" 
            }
        }
        stage('Test'){
            steps {
               echo "Test stage"
            }
        }
        stage('Push artifacts to Nexus') { 
            steps { 
                echo "Artifacts" 
            }
        }
        stage('Push image') { 
            steps { 
                echo "Push image to docker registry" 
            }
        }
        stage('Deploy') {
            steps {
                echo "Deploy stage"
            }
        }
    }
}
