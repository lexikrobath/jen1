node {
	stage 'Checkout'
	checkout scm
	
	stage 'Build'
	sh 'javac HelloWorld.java'
	
	stage 'Test'
	sh 'java HelloWorld | grep Hello'
}
