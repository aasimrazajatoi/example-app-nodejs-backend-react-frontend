pipeline {
    agent any
    tools {nodejs "NodeJS"}
    stages {   
        stage ("install dependencies") {
            steps {
                sh 'npm install'
            }
        }
        stage ("build") {
            steps {
                sh 'npm run build'
            }
        }

        stage ("test") {
            steps {
                sh 'npm start'
            }
        }

        // stage ("deploy") {

        // }
    }
}
