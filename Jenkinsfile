pipeline {
	//agent any
	agent { docker { image 'node:13.8'} }
	stages {
		stage('Build') {
			steps {
				sh 'node --version'
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
		failure {
			echo 'Boi you suck'
		}
	}
}