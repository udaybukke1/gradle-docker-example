pipeline {
    agent any

    triggers {
        pollSCM '* * * * *'
    }
    stages {
        stage('Build') {
            steps {
                echo "This is uday"
            }
        }
        stage('Test') {
            steps {
               echo "This is sudha"
            }
        }
    }
}
