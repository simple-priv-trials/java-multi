pipeline {
	
	stages {
		stage('Checkout') {
			steps {
				git 'https://github.com/simple-priv-trials/java-multi.git'
			}
		}

		stage('Build') {
			steps {
				sh ' mvn clean install '
			}
		}
	}
}

