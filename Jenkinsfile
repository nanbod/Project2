pipeline {

	agent any
	
	stages{
		stage ('Compile'){
			steps {
				bat "javac Sample.java"
			      }
		}

		stage ('Execute'){
			steps {
				bat "java Sample"
			      }
		}

	}
}
