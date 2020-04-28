pipeline {
    agent any
    stages {
      stage(‘Lint_HTML’) {
        steps {
          sh ‘tidy -q -e *.html’
        }
      stage(‘Upload_to_AWS’) {
        steps {
          steps {
        sh 'echo "Hello World"'
        sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
      }
    }
   }
  }
}
