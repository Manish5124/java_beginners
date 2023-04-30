pipeline {
  agent any
  stages{
// 	stage("Checkout"){
// 		//CHECKOUT
// 	}
	stage("Build"){
	 steps{
		script{
			sh """
			java --verion
			javac Hello.java
			java Hello
			"""
			}
		  }
		}
	}
}