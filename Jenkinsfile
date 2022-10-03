pipeline {
    agent any
    tools {nodejs "NodeJS"}
    stages {   
        stage ("install dependencies") {
            steps {
                sh 'npm install'
                sh 'npm install jest'
            }
        }
        stage ("build") {
            steps {
                sh 'npm run build'
            }
        }

        stage ("test") {
            steps {
                sh 'npm test'
            }
        }

        // stage ("deploy") {

        // }
    }
}
