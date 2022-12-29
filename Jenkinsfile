// DECLARATIVE
pipeline {
	agent any

	stages {
		stage('Build') {
			steps {
				echo "Build"
				echo "Test"
				echo "Integration Test"
			}
		}
		stage ('Test') {
			steps {
				echo "Test"
				echo "Integration Test"
			}
		}
		stage ('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	}

	post {
		always {
			echo 'Im awesome. I run always'
		}
		success {
			echo 'I run when you are successfull'
		}
		failure {
			echo ' I run when you fail'
		}
	}
		
}
