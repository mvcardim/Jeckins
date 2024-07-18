pipeline{
    agent any
    stages{
        stage('Buil Image') {
            steps {
                script{
                    dockerapp = docker.build("mvcardim/jeckins",-f ./src/Dokerfile ./src)"
                      }
                    }
                    
            }
        }
}                