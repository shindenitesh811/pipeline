pipeline {
	agent any
	stages {
		stage('BUILD'){
			steps {
				sh 'make'
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
