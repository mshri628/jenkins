pipeline {
    agent any
    stages {
        stage('all Build') {
            steps {
                echo 'Hello all'
            }
        }
        stage('dev stage') {
            when {
                branch 'dev'
            }
            steps {
                echo 'hello dev'
            }
        }
    }
}
