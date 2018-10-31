pipeline {
	agent any
	stages {
		stage('BUILD'){
			steps {
				archiveArtifacts artifacts: '**/target/*.jar', fingerprint: true
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
