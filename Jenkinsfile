pipeline {
    agent any
	//agent {
	    //docker 
		//{image 'node:16.3'} }
	stages {
		stage('Build'){
			steps {
			    //sh 'node --version'
				echo "Build"
				echo " PATH - $PATH"
				echo "BUILD_NUMBER - $env.BUILD_NUMBER"
				echo "BUILD_ID - $env.BUILD_ID"
				echo "JOB_NAME - $env.JOB_NAME"
				echo "BUILD_TAG - $env.BUILD_TAG"
				echo "BUILD_URL - $env.BUILD_URL"

			
			}
		}

		stage('Test'){
			steps {
		
				echo "Test"
				
			}
		}

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