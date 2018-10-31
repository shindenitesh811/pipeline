pipeline {
	def username = 'Nitesh'
	
	agent any
	stages {
		stage('BUILD'){
			steps {
				echo "$username is genius"
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
