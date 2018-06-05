pipeline {
	agent any
	stages{
		steps(ls commands){	
			ls -l;/
			ls -a;/
			ls -li
		}
	
		steps(mkdir command){
			mkdir abc;/
			mkdir xyx;/
			mkdir pqr
	        }
		steps(rm command){
			rm -r abc;/
			rm -r xyx;/
			rm -r pqr
		}
	}
}
