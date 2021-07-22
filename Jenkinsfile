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
		
		stage('Compile Stage'){
			steps{
					sh 'mvn compile'
			}
		}
	}
}
