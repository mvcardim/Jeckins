pipeline{
    agent any
    stages{
        stage('Buil Image') {
            steps {
                script{
                    dockerapp = docker.build("mvcardim/jeckins:${env.BUILD_ID}",'-f ./src/Dockerfile ./src')
                      }
                    }
                    
            }
        }
}                