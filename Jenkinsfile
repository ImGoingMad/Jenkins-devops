pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				echo "Build"
			
			}
		}
	}
	post {
		always {
			echo 'Sugamano?'
		}
		success {
			echo 'Good job ma boi'
		}
		failiure {
			echo 'Boi you suck'
		}
	}
}