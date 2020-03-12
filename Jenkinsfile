pipeline {
    agent none
    stages {
        stage('master stage') 
            agent any
            when {
                branch 'master'
            }
            steps {
                echo "master"
                
        }
    }
    stage('dev stage') {
            agent any
        
            when {
                branch 'dev'
            }
            steps {
                echo "dev"
                
        }
    }
}
