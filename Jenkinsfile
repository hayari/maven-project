pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy to pré-prod') {
            steps {
                echo 'Deploying to staging....'
            }
        }
         stage('Deploy to prod') {
            steps {
                echo 'Deploying to production'
            }   
         }
       
        }
    post {
            always {
                echo "c'est le ${currentBuild.fullDisplayName}"
            }
    }
    
}
