pipeline {
  agent any
  
  stages {
  stage('Build') {
      steps {
        script {
          echo 'Building.....'
		  bat 'echo index.html'
		  echo 'Java script'
		  bat 'node hello.js'
        }
      }
    }
  }
}
