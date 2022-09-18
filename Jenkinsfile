pipeline {

    agent any

    stages {    
        stage('Pull from SCM') {
            steps {
                git 'https://github.com/opendoc-tree/javademo.git'
            }
        }

        stage('Build') {
            steps { 
                sh 'mvn clean package'
            }
        }
        
        stage('Deploy') {
            steps {
                sh 'java -jar target/*.jar'
            }
        }        
    }
}

