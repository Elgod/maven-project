pipeline{
	agent any 
	stages{
		stage ('Build'){
			steps{
				sh '/home/raul/maven/bin/mvn clean package'
				sh 'docker build . -t tomcatwebapp:test'
			}

		}
		
	}
}