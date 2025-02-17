pipeline {
	agent any {
		stage('Build') {
			steps {
				echo 'Build'
				echo 'Test'
				echo 'Integration test'
			}
		}
		stage('Test') {
			steps {
				echo 'Test'
			}
		}
		stage('Integration test') {
			steps {
				echo 'Integration test'
			}
		}
		post {
			always {
				echo 'I always run'
			}
			success {
				echo 'I run when succsessful'
			}
			failure {
				echo 'I run when failed'
			}
		}
	}
}