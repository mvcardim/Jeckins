pipeline{
    agent any
    stages{
        stage('IBuild Image') {
            steps {
                script{
                    dockerapp = docker.build("mvcardim/Iniciativa-Devops", '-f ./Aula01/src/Dockerfile ./src')                }
                echo 'iniciando a pipeline'
            }
        }
    }
}