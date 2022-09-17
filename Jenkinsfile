pipeline {

    agent any

    stages {    
        stage('SCM') {
            steps {
                echo "git pull my code"
            }
        }

        stage('Deploy') {
            steps { 
                echo "Deploying my code"
            }
        }

        stage('Test') {
            steps {
                echo "Testing my code"
            }
        }
        
        stage('Deploy to Prod') {
            steps {
                echo "Deploying my code to prod"
            }
        }        
    }
}

