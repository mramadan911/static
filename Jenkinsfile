pipeline {
    agent any
    stages {
        stage('Lint HTML') {
            sh 'tidy -q -e 8.html'
        }
    }
}
