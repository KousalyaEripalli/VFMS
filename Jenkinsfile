pipeline{
    agent any

    stages{
        stage('Maven test'){
            steps{
                sh "maven test"
            } 
        }
        stage('Maven Compile'){
            steps{
                sh"maven clean package"
            }
        }

        stage('Maven Deploy'){
            steps{
                sh "mvn deploy"
            }
        }
    }
}
