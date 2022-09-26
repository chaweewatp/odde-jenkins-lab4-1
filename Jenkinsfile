// Jenkinsfile
pipeline {
    agent any
    stages {
        stage ('stage1'){
            
            steps{
                script {
                    if (fileExists('multiple.txt')) {
                        sh 
                        """
                            echo multiple.txt file exist
                            echo remove multiple.txt
                            rm multiple.txt
                        """
                        // sh "rm multiple.txt"
                    }
                    sh
                    """
                        echo create new multiple.txt
                        touch multiple.txt
                    """
                    // sh "touch multiple.txt"
                    }
                
            }
        }
        stage ('stage2') {
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