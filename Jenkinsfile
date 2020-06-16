pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'mkdir test1'
		}
	}
	stage('Test') {
		steps {
		    sh 'cd test1'
			sh 'echo "Hello World" >> test.txt'
			sh 'cat text.txt'
			}
		}
    }
}

