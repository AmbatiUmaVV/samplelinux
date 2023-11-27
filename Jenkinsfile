pipeline{
	agent any
	stages{
		stage('version'){
			steps{
                sh 'python3 --version'
			}
		}
        stage('build'){
            steps{
                sh 'python3 /home/weblogic/devOps/samplelinux/factorialnumber.py'
            }
        }
	}
}