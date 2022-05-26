pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
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
