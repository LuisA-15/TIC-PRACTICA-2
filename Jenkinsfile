pipeline {
    agent any
	stages {
		stage('version') {
			steps {
				sh 'python --version'
			}
		}
		stage('hello') {
			withPythonEnv('python') {
				sh 'python hello.py'
			}
		}
	}
}
