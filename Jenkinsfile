pipeline {
	agent any
	stages {
		stage('Build'){
			steps {
				echo "Build"
			
			}
		}
		stages {
		stage('Test'){
			steps {
		
				echo "Test"
				
			}
		}
		stages {
		stage('Integration Test'){
			steps {
			
				echo "Integration Test"
			}
		}
	}
	post {
		always {
			echo 'Im awesome.i run always'
		}
		success {
			echo 'i run only when you are successful'
		}
		failure {
			echo ' i run only when you fail'
		}
	}
  }	
}
}