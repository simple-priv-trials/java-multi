pipeline {
	
	agents {
		label 'docker'
	}
	
	stages {
		stage('Build') {
			steps {
				sh ' mvn clean install '
			}
		}
	}
}

