pipeline{
	agent any
	tools {
        	maven 'Maven_3.6.3' 
    	}
	stages{
	
		stage('print'){
			steps{
				echo 'Hello'
				bat 'mvn --version'
			}
		}
		
		stage('Package Stage'){
			steps{
					bat 'mvn clean package'
			}
		}
	}
}
