pipeline {
	//agent any
	agent { docker { image 'maven:3.8.6'} }
	stages {
		stage('Build') {
			steps {
				sh 'mvn --version'
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