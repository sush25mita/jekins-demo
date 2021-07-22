pipeline{
	agent any
	tools {
        	maven 'Maven_3.6.3' 
    	}
	stages{
	
		stage('print'){
			steps{
				echo 'Hello'
			}
		}
		
		stage('Package Stage'){
			steps{
					sh 'mvn package'
			}
		}
	}
}
