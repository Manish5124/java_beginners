pipeline {
  agent any
  stages{
	stage("Checkout"){
		git branch: 'main', url: 'https://github.com/Manish5124/java_beginners.git'
	}
	stage("Build"){
	 steps{
		script{
			java --verion
			javac Hello.java
			java Hello
			}
		  }
		}
	}
}