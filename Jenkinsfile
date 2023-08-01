pipeline {
	agent{ docker { image 'maven:3.6.3"}}
	stages{
		stage('Build') {
		      steps {
			 sh 'mvn --version'
			 echo "Build"
		      }
		}
	        stage('Test') {
		      steps {
			 sh 'mvn --version'
			 echo "Test"
		      }
		}
		stage('Integration Test') {
		      steps {
			 sh 'mvn --version'
			 echo "Integration Test"
		      }
		}
	
	}
}
	      
