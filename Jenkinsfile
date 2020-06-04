pipeline{
    agent any
    stages {
        stage("Build"){
            steps{
                 "mvn clean"
            }
        }
        stage("Test"){
            steps{
                "mvn test"
            }
        }
        stage("Package"){
            steps{
                "mvn package"
            }
        }
    }
}