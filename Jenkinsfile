pipeline {
    agent any
    
stages{
		
        stage('Build'){
            steps {
				echo "Jamal ..."
				sh 'mvn clean package'
				echo "mvn"
            }
			post {
				success {
					echo "Now Archiving..."
					
				}
			}

        }

    }
}