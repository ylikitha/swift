pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello, Jenkins!'
            }
        }
            stage('cat README') {
	  when {
	     branch "taylor*"
	  }
	  steps {
	     sh '''
	        cat README.md
             '''
	     }
        }
    }
}




