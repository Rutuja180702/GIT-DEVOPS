pipeline {
    agent { label 'agent-rs' }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello world'
            }
        }

        stage('Create Folder') {
            steps {
                sh "mkdir -p devops"
            }
        }

        stage('Bye') {
            steps {
                echo 'Bye bye'
            }
        }
    }
}
