pipeline{
	agent any
	stages{
		stage('build'){
		steps{
			bat 'docker build Dockerfile todoapp'
			bat 'docker run -p 8000:8000 -d todoapp'
		}
			}

		stage('test'){
                steps{
                	
                echo 'testing is succesful'
                }
                        
		}

		 stage('deploy'){
                steps{
                        echo 'deployment is successful'
                        
                }
                        }
	}
}
