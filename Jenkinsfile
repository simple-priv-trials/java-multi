pipeline {
    
	agent {
		label 'docker'
	}
	
	stages {
		stage('Checkout') {
			steps {
				git branch: 'b2', changelog: false, poll: false, url: 'https://github.com/simple-priv-trials/java-multi.git'
			}
		}

		stage('Build') {
			steps {
				sh ' mvn clean install '
			}
		}
	}
}
