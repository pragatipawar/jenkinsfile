pipeline {
	agent any
	stages{
		stage('ls commands'){
			steps{
				ls -l;/
				ls -a;/
				ls -li
			}
		}
	
		stage('mkdir command'){
			steps{
				mkdir abc;/
				mkdir xyx;/
				mkdir pqr
			}
	        }
		stage('rm command'){
			steps{
				rm -r abc;/
				rm -r xyx;/
				rm -r pqr
			}
		}
	}
}
