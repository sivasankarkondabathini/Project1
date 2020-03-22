pipeline {
   agent any

   stages {
      stage('Clone') {
         steps {
			checkout([$class: 'GitSCM', branches: [[name: '*/master']], doGenerateSubmoduleConfigurations: false, extensions: [], submoduleCfg: [], userRemoteConfigs: [[credentialsId: 'cd9cdf1a-38d8-479e-aa94-aebc81545c45', url: 'https://github.com/sivasankarkondabathini/Docker.git']]])
         }
      }
	  stage('Maven: Build'){
		 steps {		 
			echo "Build Maven"		 
		 }
	  }  
	  stage('Unit Tests'){
		 steps {		 
			echo "Build Maven"		 
		 }
	  }  
	  stage('SonarQube: Code Coverage'){
		 steps {		 
			echo "Build Maven"		 
		 }
	  }  
	  stage('Docker: Build'){
		 steps {		 
			echo "Build Maven"		 
		 }
	  }  
	  stage('Docker: Push'){
		 steps {		 
			echo "Build Maven"		 
		 }
	  }
	  stage('Deploy Dev'){
		 steps {		 
			echo "Build Maven"		 
		 }
	  }    	  
   }
}
