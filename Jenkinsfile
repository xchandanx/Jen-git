pipeline{
    agent any
    stages{
        stage("Get Code"){
            steps{
                checkout scm
            }
            }
            stage("Run Script"){
                steps{
                    sh "sh first.sh"
                }
            }
            stage("Notify"){
                steps{
                    sh 'echo "Script Ran Successfully"'
            }
        }
        stage("Complete"){
                steps{
                    echo "Job Completed"
            }
        }
    }
}
