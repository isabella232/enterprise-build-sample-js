#!groovy

node {
	stage('checkout')
	checkout scm
	
	stage('prebuild')
	withNPM() {
		sh 'npm install -g grunt-cli'
	
		sh 'npm install -g bower'
	}
}