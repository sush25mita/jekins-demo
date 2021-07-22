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
				maven(maven : 'maven'){
					sh 'mvn compile'
				}
			}
		}
	}
}
