pipeline {
	 agent any 
	 
	 stages {
		stage("compile") {
			steps {
				echo "Compiling"
				bat """ javac hello_world.java """
				}
			}
			
		stage ("run") {
			steps {
				echo "Running"
				bat """ java hello_world"""
				}
			}
			
		}
	}
