pipeline {
    agent any

    stages {
        stage('Validar Jenkins') {
            steps {
                echo 'Jenkins funcionando!'
            }
        }

        stage('Validar projeto') {
            steps {
                sh 'pwd'
                sh 'ls -la'
                sh 'cat index.html'
            }
        }

        stage('Concluir') {
            steps {
                echo 'Pipeline concluido com sucesso!'
            }
        }
    }
}
