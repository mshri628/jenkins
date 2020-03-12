pipeline {
    agent any
    stages {
             stage('master stage') {
            when {
                branch 'master'
            }
            steps {
                echo 'master'
            }
        } 
        stage('dev stage') {
            when {
                branch 'dev'
            }
            steps {
                echo 'Dev'
            }
        }  
        }
    }
}
