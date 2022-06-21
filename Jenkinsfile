pipeline {
    agent any
    stages{
        stage ("scm ")
        {
            steps{
                git credentialsId: 'new', url: 'https://gitlab.cloudifyops.com/Adarshashok/java-maven-app.git'
            }
        }
    }
}
