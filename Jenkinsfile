pipeline {

	agent any 
	 
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