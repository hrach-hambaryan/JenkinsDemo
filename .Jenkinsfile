pipeline {
    agent any
	stages {
		stage('Deploy') {
			steps {
				sh 'echo "Hello World"'
			}
		}
		stage('BuildMore') {
			steps {
				input message: "Shall we build more??"
				sh '''
					echo "We are approved; continue!"
					ls -lah
				'''
			}
		}
	}
}

def func(){

}