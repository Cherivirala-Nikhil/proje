pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Running HelloWorld script...'
                bat 'helloworld.bat'
            }
        }

        stage('Done') {
            steps {
                echo 'All steps completed!'
            }
        }
    }
}
