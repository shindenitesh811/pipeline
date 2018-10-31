pipeline {
	agent any
	stages {
		stage('BUILD'){
			steps {
				sh 'uptime'
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
