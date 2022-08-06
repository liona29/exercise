pipeline{
    agent{
        label "jenkins-salve"
    }
    stages{
        stage("print"){
            steps{
                echo ${BUILD_ID}
                echo ${JOB_URL}
            }
        }
        stage("id"){
            steps{
                sh "whoami"
            }
        }
    }
}