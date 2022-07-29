/* node {
	stage('Build') {
		echo "Build"
	}
	stage('Test') {
		echo "Test"
	}
	stage('deploy') {
	echo "Integration test latest 4"
	}
} */

pipeline {
	agent any
	stages { 
		stage('build') {
			steps {
			echo "Build success"
			}
		}
		post {
			always {
				echo "pass build success"
			}
		}
	}
}