pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running HelloWorld script...'
                bat 'type hello.txt'
            }
        }

        stage('Done') {
            steps {
                echo 'All steps completed!'
            }
        }
    }
}
