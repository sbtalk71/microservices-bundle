pipeline{
    agent any
    stages{
        stage("checkout"){
            steps{
                git "https://github.com/sbtalk71/microservices-bundle.git"
            }
        }
        
         stage("package"){
            steps{
            sh "mvn clean package -DskipTests"
            }
        }
    }
 }
