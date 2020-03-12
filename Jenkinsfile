pipeline {
    agent any
    stages {
        stage('all Build') {
            steps {
                echo 'Hello all'
            }
        }
        stage('master stage') {
            when {
                branch 'master'
            }
            steps {
                echo 'hello dev'
            }
        }
    }
}
