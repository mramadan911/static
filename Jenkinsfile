pipeline {
  agent any
  stages {
  
	stage('lint HTML') {
	steps {
		tidy -q -e *.html
		}
	}
    stage('Upload to AWS') {
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
