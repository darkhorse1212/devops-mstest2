pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			}
		}
		stage('Test') {
			steps {
				echo "Test"
			}
		}
		stage('Integration Test') {
			steps {
				echo "Integration Test"
			}
		}
	} 
	post {
		always {
			echi "I am cool. Setting this up for success"
		}
		success {
			echo "I am successful"
		}
		failure {
			echo "I run when i am failure"
		}
	}
}