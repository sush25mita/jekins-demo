pipeline{
	agent any
	tools {
        	maven 'Maven_3.6.3' 
    	}
	stages{
	
		stage('print'){
			steps{
				echo 'Hello'
				sh 'mvn --version'
			}
		}
		
		stage('Package Stage'){
			steps{
					sh 'mvn clean package'
			}
		}
	}
}
