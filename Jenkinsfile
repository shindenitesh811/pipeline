pipeline {
	
	
	agent any
	stages {
		stage('BUILD'){
			steps {
				echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"			}
		}
		
		stage(TEST){
			steps {
				echo "Testing"
			}
		}
		
		stage (DEPLOY){
			steps {
				echo "Just deploy baby"
			}
		}
	}
}
