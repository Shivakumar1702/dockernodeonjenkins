pipeline {
        agent { 
            docker { 
                image 'maven:3.3.3'
                customWorkspace 'C:\\'
                } 
            }
        stages {
            stage('build') {
                steps {
                    sh 'mvn --version'
                }
           }
        }
    }