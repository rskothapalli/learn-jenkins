pipeline {
    agent{
        label 'Agent-1'
    }

    stages ('build'){
        stage {
            steps {
                sh 'echo this is build'
                
            }
        }
    }
    
    stages ('test'){
        stage {
            steps {
                sh 'echo this is test'
            }
        }
    }

    stages ('deploy'){
        stage {
            steps{
                sh 'echo this is deploy'
            }
        }
    }
}