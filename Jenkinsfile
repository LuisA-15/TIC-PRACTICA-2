pipeline {
    agent any
	stages {
		stage('hello') {
			steps {
				withPythonEnv('python') {
					sh 'python hello.py'
				}
			}
		}
	}
}
