pipeline{
    agent any
        stage("Build"){
            steps{
                bat "mvn clean"
            }
        }
        stage("Test"){
            steps{
                bat "mvn test"
            }
        }
        stage("Package"){
            steps{
                bat "mvn package"
            }
        }
}