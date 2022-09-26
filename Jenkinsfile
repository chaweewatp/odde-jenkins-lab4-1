// Jenkinsfile
pipeline {
    agent any
    stages {
        stage('stage1') {
            steps {
                sh "echo Hello >> multiple.txt"
                
            }
        }
        stage ("stage2"){
            steps{
                sh "echo Hello >> multiple.txt"

            }
        }

        stage ("stage5"){
            steps{
                sh "cat multiple.txt"

            }
        }
        
    }
}