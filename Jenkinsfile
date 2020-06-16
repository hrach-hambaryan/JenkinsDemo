pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'mkdir test11'
		}
	}
	stage('Test') {
		steps {
		    sh 'cd test11'
			sh 'echo "Hello World" >> test.txt'
			sh 'cat text.txt'
			}
		}
    }
}

