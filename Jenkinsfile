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