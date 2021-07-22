pipeline{
	agent any
	stages{
	
		stage('print'){
			steps{
				echo 'Hello'
			}
		}
		
		stage('Compile Stage'){
			steps{
				maven(maven : 'Maven_3.6.3'){
					sh 'mvn clean compile'
				}
			}
		}
	}
}
