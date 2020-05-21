pipeline {
	agent any 
	
	stages {
		stage('Build'){
			steps{
				git 'https://github.com/adityaiit2015/test.git'
				sh 'python heelo.py'
				sh 'python proj1.py'
			}
		}
		stage('Test'){
			steps{
				git 'https://github.com/adityaiit2015/test.git'
				sh 'python heelo.py'
				sh 'python proj1.py'
			}
		}
		stage('Deploy'){
			steps{
				git 'https://github.com/adityaiit2015/test.git'
				sh 'python heelo.py'
				sh 'python proj1.py'
			}
		}
	}
}
	
