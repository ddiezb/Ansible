pipeline{
	agent any
	triggers{
		pollSCM('* * * * *')
	}
	stages {
		stage('Check syntax stage'){
			steps{
				build job: 'Check_syntax'
			}
		}
	}
}
