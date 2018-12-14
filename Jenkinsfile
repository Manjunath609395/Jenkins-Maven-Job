pipeline {

	agent any 
	
	 tools {
	 
	 maven 'C:\Workables\apache-maven-3.3.1\bin'
	 
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