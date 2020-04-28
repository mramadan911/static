pipeline {
  agent any
  stages {
	stage(‘Lint_HTML’) {
        steps {
          tidy -q -e *.html
        }
	}
}
    stage('Upload_to_AWS') {
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
