pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'mkdir test'
		}
	}
	stage('Test') {
		steps {
		    sh 'cd test'
			sh 'echo "Hello World" > test.txt'
			sh 'cat text.txt'
			}
		}
    }
}

