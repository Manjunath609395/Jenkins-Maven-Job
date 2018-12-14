pipeline {

	agent any 
	stages {
		stage ('Compile Stage') {
		
		steps {
			withMaven(maven : 'C:\Workables\apache-maven-3.3.1\bin'){
				sh 'mvn clean compile'
			}
		}
		
		}
	
	}
}