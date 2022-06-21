pipeline {
    agent any
    stages{
        stage ("scm ")
        {
            steps{
                git credentialsId: 'new', url: 'https://gitlab.cloudifyops.com/clops-training/java-maven-app.git'
            }
        }
    }
}
