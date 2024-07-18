pipeline{
    agent any
    stages{
        stage('Buil Image') {
            steps {
                script{
                    dockerapp = docker.build("mvcardim/Jeckins",'-f ./src/Dokerfile ./src')
                      }
                    }
                    
            }
        }
}                