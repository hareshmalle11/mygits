pipeline {
    agent any  

    stages {
        stage('Get Code') {  
            steps {
                git url: 'https://github.com/hareshmalle11/mygits', branch: 'main' 
            }
        }
        stage('Build') {  
            steps {
                echo 'Trying to build the project...'
                bat 'dir'  // List files (Windows equivalent of 'ls')
            }
        }
        stage('Test') {  
            steps {
                echo 'Running tests...'
            }
        }
        stage('Deploy') {  
            steps {
                echo 'Deploying the application...'
            }
        }
    }
}
