pipeline {
	
	
	agent any
	environment{
	uname = 'nitesh'
	}
	stages {
		stage('BUILD'){
			steps {
				echo "Running ${env.BUILD_ID} on ${env.JENKINS_URL}"	
				echo "${uname}  is genius"
			}
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
