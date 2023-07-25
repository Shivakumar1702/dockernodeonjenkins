pipeline {
    agent {
        docker {
            image 'maven:latest'
        }
    }

    stages {
        stage ('build') {
            environment {
                  HOME="."
                }
            steps {
                sh 'mvn -v'
            }
        }
    }
}