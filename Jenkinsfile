pipeline {
    agent any
    
stages{
		
        stage('Build'){
            steps {
				echo "Jamal ..."
				
				echo "mvn"
            }
			post {
				success {
					echo "Now Archiving..."
					archiveArtifacts artifacts: '**/target/*.war'
				}
			}

        }

    }
}