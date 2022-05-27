pipeline {
	agent { 
		docker { image 'node:13.8'} 
	}
	stages {
		stage('Build') {
			steps {
				sh 'node --version'
				echo 'Build'
			}
		}
		stage('Test') {
			steps {
				echo 'Test'
			}
		}
		stage('IntegrationTest') {
			steps {
				echo 'IntegrationTest'
			}
		}

	}

	post {
		always {
			echo 'always'
		}
		success {
			echo 'success'
		}
		failure {
			echo 'failure'
		}

	}
}
