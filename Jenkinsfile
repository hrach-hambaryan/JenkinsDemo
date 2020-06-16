pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'mkdir test111'
		}
	}
	stage('Test') {
		steps {
		    sh 'cd test111'
			sh "echo version := 1.0.${env.BUILD_ID} >> test.txt"
			sh 'cat text.txt'
			}
		}
    }
}

