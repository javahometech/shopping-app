pipeline{
    agent any
    stages{
        stage('Deploy Task'){
            steps{
                echo "Deployind to test environment"
            }
        }
        stage("Call Selenium Job"){
            steps{
                build 'selenium-job'
            }
        }
    }
}
