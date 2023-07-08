pipeline {
    agent { node { label 'workstation' } }
    environment {
    SSH = credentials{'SSH'}
    }
    stages {
        stage('Hello-1') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post {
    always {
    sh 'echo post'
    }
    }
 }
