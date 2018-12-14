pipeline {

	agent any 
	
	 tools {
	 
	 maven 'Maven-3.3.1'
	 
	 } 
	 
	stages {
		stage ('Compile Stage') {
		
		steps {
			withMaven(maven : 'maven-3.3.1'){
				sh 'mvn clean install'
			}
		}
		
		}
	
	}
}