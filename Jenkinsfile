	pipeline {
	// agent any
	agent { docker { image 'maven:3.8.1'} }
	stages{
	stage('Build') {
		steps{
			sh "mvn --version"
		echo "Build"
		}
	}

	stage('Test') {
	steps{
		echo "Test"
		}
	}

	stage('Integration Test') {
		steps{
		echo "Integration Test"
		}
	}
	
}
}

