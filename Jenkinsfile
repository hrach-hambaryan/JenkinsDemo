pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
		sh 'pwd'		
		sh 'mkdir test1111'
		}
	}
	stage('Test') {
		steps {
			sh 'pwd'
		    sh 'cd test1111'
			sh 'pwd'
			sh "echo version := 1.0.${env.BUILD_ID} >> test1111/test.txt"
			sh 'pwd'
			sh 'cat test.txt'
			}
		}
    }
}

