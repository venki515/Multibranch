pipeline{
	agent any
	tools{
		maven 'apache-maven-3.5.3'
		}
	stages{
		stage('build'){
			steps{
				bat 'echo "Hello world"'
				}
			}
		stage('Production'){
			steps{
				bat 'echo "This is done in Production"'
				}
			}
		}
		
	}