#!groovy

pipeline {
	agent any

	stages {
	   stage('Build') {
	   	steps { 
	   		sh 'pwd'
	        }
	   }
		
	   stage('Test') {
	   	steps {
			sh 'ls'
		}
	   }	
	   stage('Deploy') {
	   	steps{
			sh 'java -version'
		}
	   }
      }
}	 
