node {
	stage 'Checkout'
	checkout scm
	
	stage 'Build'
	sh 'About to build Java app'
	sh 'javac HelloWorld.java'
	
	stage 'Test'
	sh 'Checking application works'
	sh 'java HelloWorld | grep Hello'
}
