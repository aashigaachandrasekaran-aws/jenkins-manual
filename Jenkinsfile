pipeline {
	agent any
	stages{
		stage('Build'){
			steps{
				echo 'Building'
        sh 'whoami'
			}
		}
		stage('Test'){
			steps{
				echo 'testing'
        sh 'hostname'
			}
		}
		stage('Deploy'){
			steps{
				echo 'Deploying'
        sh 'ls -la'
			}
		}

	}
}

