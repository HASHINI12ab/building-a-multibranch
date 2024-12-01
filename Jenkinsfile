pipeline {
    agent any
    environment {
        CI ='true'
    }
    stages {
        stage('Build') {
            steps {
                bat 'npm install'
            
            }
        }
        stage ('test'){
            steps{
                bat '"C:\Program Files\Git\bin\bash.exe" -c "./jenkins/scripts/test.sh"'
            }
        }
    }
}
