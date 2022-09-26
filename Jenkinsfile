// Jenkinsfile
pipeline {
    agent any
    stages {
        stage ('stage1'){
            steps{
                sh "touch multiple.txt"
            }
        }
        stage('stage2') {
            steps {
                sh "echo Hello >> multiple.txt"
                
            }
        }
        stage ("stage3"){
            steps{
                sh "echo Jenkin >> multiple.txt"

            }
        }
        stage ("stage4"){
            steps{
                sh "echo Workspace >> multiple.txt"

            }
        }
        stage ("stage5"){
            steps{
                sh "cat multiple.txt"

            }
        }
        
    }
}