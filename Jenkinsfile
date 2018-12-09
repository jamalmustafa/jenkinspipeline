pipeline {
    agent any
    
stages{

		echo 'Jamal ...'
        stage('Build'){
            steps {
				sh 'mvn clean package'
            }
			post {
				success {
					echo 'Now Archiving...'
					archiveArtifacts artifacts: '**/target/*.war'
				}
			}

        }

    }
}