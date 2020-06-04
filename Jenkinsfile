pipeline {
    agent any
    stages {
        stage ("Build"){
            steps{
                 mvn clean
            }
        }
        stage ("Test"){
            steps{
                mvn test
            }
        }
        stage ("Deploy"){
            steps{
                echo "Deployment Started"
                mvn package }
            }
        }
    }
}